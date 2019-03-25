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
            src: "../../assets/portada/p1.jpeg"
          },
          {
            src: "../../assets/portada/p2.jpeg"
          },
          {
            src: 'https://raw.githubusercontent.com/maxlr2005/vuePeruEsc/master/src/assets/portada/03.png'
          }
        ]
      }
    }
  }
</script>
// ################################# STYLE ##################################
// ###########################################################################
<style>

</style>
