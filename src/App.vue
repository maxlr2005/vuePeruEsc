<template>
  <v-app>
    <v-toolbar app fixed prominent>
    <v-img
      :src="require('./assets/Logo.png')"
      class="my-3"
      contain
      height="60"
      ></v-img>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat color="primary" active>Home</v-btn>
      <v-btn flat color="primary">About Us</v-btn>
      <v-btn flat color="primary">Our Properties</v-btn>
      <v-btn flat color="primary">Locations</v-btn>
      <v-btn flat color="primary">Blog</v-btn>
      <v-btn flat color="primary">EN
        <v-img
        :src="require('./assets/en.png')"
        >
      </v-img>
      </v-btn>
    </v-toolbar-items>
    </v-toolbar>
    <v-content>
      <home/>
    </v-content>
  </v-app>
</template>

<script>
import home from './components/home'
export default {
  name: 'App',
  components:
  {
    home,
  },
  data () {
    return {
      //
    }
  }
}
</script>
