<template>
  <v-app>
    <v-app-bar
      app
      flat
    >
    <Header/>
    </v-app-bar>

    <v-content>
      <Hero/>
      <Gallery/>
    </v-content>
  </v-app>
</template>

<script>
import Header from './components/Header';
import Hero from './components/Hero';
import Gallery from './components/Gallery';

export default {
  name: 'App',

  components: {
    Header,
    Hero,
    Gallery
  },

  data: () => ({
    //
  }),
};
</script>
