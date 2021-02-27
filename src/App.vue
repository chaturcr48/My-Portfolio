<template>
  <v-app>
    <v-main>
      <Resume/>
    </v-main>
  </v-app>
</template>

<script>
import Resume from './components/Resume';

export default {
  name: 'App',

  components: {
    Resume,
  },

  data: () => ({
    //
  }),
};
</script>
