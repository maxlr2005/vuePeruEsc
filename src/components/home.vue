<template>
<div>
<banner/>
<parallax01/>
<v-img
:src="require('../assets/Logo.png')"
height="120"
width="auto"></v-img>
</div>
</template>

<script>
import banner from './homepage/banner'
import ondemand from './homepage/ondemand'
import parallax01 from './homepage/parallax01'
import parallax02 from './homepage/parallax02'
export default {
  components:
  {
    banner,
    ondemand,
    parallax01,
    parallax02
  }
  }
</script>

<style>
</style>
