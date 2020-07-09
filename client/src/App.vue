<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>

<script>
import Header from "./components/Header"

export default {
  components: {
    Header
  }
  
}
</script>

<style>

html, body {
  margin: 0;
  padding: 0;
}

body {
  background-color: #f4f7f7;
}

</style>
