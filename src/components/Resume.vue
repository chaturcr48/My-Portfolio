<template>
  <v-container class="main-container">

    <Header />
    <v-divider style="margin-top: 20px"></v-divider>
    <Intro />
    <v-divider style="margin-top: 10px"></v-divider>

    <v-row class="margin">
      <Projects />
      <SkillSection />
    </v-row>

    <v-divider style="margin-top: 20px"></v-divider>
    
    <Footer />

  </v-container>
</template>

<script>
import Footer from './Footer.vue';
import Header from './Header.vue';
import Intro from './Intro.vue';
import Projects from './Projects.vue';
import SkillSection from './SkillSection.vue';

export default {
  name: 'App',
  components: {
    Footer,
    Header,
    Intro,
    Projects,
    SkillSection
  }
}
</script>

<style>
.f-name {
  font-size: 55px;
  font-weight: bold;
  color: green;
}
.vl {
  border-left: 1.5px solid rgba(0, 0, 0, 0.158);
  margin-right: 5px;
}
.main-container {
  margin-top: 30px;
  margin-bottom: 30px;
  padding: 35px;
  box-shadow: 0px 0px 50px -20px green;
}
.details {
  font-size: 13px;
}
.border {
  border: 2px solid black;
}
.border-left {
  border-left: 1px solid rgba(0, 0, 0, 0.192);
}
.details-margin {
  margin: 3px;
}
.s-row-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
}
.padding {
  padding: 20px;
}
.margin {
  margin-top: 10px;
}
.padding-x {
  padding: 0px 10px;
}
.margin-top {
  margin-top: 10px;
}
a {
  text-decoration: none;
  color: green;
}
.link {
  color: green;
}
.span-sub-topic {
  color: rgba(0, 0, 0, 0.596);
}
.footer-link {
  color: black;
}
.footer-link:hover {
  color: green;
  font-weight: bold;
}
</style>