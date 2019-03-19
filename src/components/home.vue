<template>
    <v-container grid-list-md text-xs-center>
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
        <v-flex xs12>
          <h4 class="display-1 font-weight-medium"> our lattest houses </h4>
        </v-flex>
        <v-flex xs12>
          <v-parallax
          dark
          src="../assets/portada/02.jpeg">
          <v-layout
            align-center
            column
            justify-center>
            <h1 class="display-2 font-weight-medium mb-3">Leave all in our hands and enjoy</h1>
            <h4 class="display-1"> we offer you the best options for your relax </h4>
          </v-layout>
          </v-parallax>
        </v-flex>
      </v-layout>
    </v-container>
</template>

<script>
export default {
    data () {
      return {
// ### Se tiene que cambiar esto por las fotos de portada original, hay que pedirselas a los chicos de marketing ###
        items: [
          {
            src: 'https://raw.githubusercontent.com/maxlr2005/vuePeruEsc/master/src/assets/portada/01.jpeg'
          },
          {
            src: 'https://raw.githubusercontent.com/maxlr2005/vuePeruEsc/master/src/assets/portada/02.jpeg'
          },
          {
            src: 'https://raw.githubusercontent.com/maxlr2005/vuePeruEsc/master/src/assets/portada/03.png'
          }
        ]
      }
    }
  }
</script>

<style>
</style>
