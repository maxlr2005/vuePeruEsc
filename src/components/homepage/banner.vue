// ################################# TEMPLATE ##################################
// ###########################################################################
<template>
  <v-layout row wrap>
    <v-flex xs12>
      <v-carousel hide-controls hide-delimiters>
        <v-carousel-item
          v-for="(item,i) in items"
          :key="i"
          :src="item.src"
        ></v-carousel-item>
      </v-carousel>
    </v-flex>
  </v-layout>
</template>
// ################################# SCRIPT ##################################
// ###########################################################################
<script>
export default {
    data () {
      return {
// ### Se tiene que cambiar esto por las fotos de portada original, hay que pedirselas a los chicos de marketing ###
        items: [
          {
            src: require('../../assets/portada/p1.jpeg')
          },
          {
            src: require('../../assets/portada/p2.jpeg')
          }
        ]
      }
    }
  }
</script>
// ################################# STYLE ##################################
// ##########################################################################
<style>

</style>
