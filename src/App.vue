<template>
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
  }
}
</script>

<style>

</style>
