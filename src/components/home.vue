<template>
  <v-carousel hide-controls hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
    data () {
      return {
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
