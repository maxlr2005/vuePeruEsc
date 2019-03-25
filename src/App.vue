<template>
  <v-app>
    <v-toolbar app fixed>
      <v-toolbar-title class="headline text-uppercase">
        <span>Peru Escape logo</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>

      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-toolbar>

    <v-content>
  <!--  <HelloWorld/> -->
      <home/>
    </v-content>
  </v-app>
</template>

<script>
import banner from './components/homepage/banner'
import HelloWorld from './components/HelloWorld'
import home from './components/home'

export default {
  name: 'App',
  components:
  {
    HelloWorld,
    home
  },
  data () {
    return {
      //
    }
  }
}
</script>
