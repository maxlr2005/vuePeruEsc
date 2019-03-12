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
            src: '../assets/portada/01.jpeg'
          },
          {
            src: '../assets/portada/02.jpeg'
          },
          {
            src: '../assets/portada/03.png'
          }
        ]
      }
    }
  }
</script>

<style>
</style>
