<template>
  <link type="image/png" sizes="16x16" rel="icon" :href="require('@/assets/favicon.png')" >
  <title>HTML Elements Reference</title>
  <nav-bar/>
  <home-page/>
</template>

<script>
import HomePage from "@/components/Home";
import NavBar from "@/components/NavBar";

export default {
  name: 'App',
  components: {
    NavBar,
    HomePage,
  },
  mounted() {
      document.title = "Welcome to my page"
  },
}
</script>

<style>

</style>
