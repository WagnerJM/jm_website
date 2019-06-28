<template>
  <div id="app">
    <div class="topnav">
      <a class="active">Jean-Marc Wagner</a>
      <router-link style="float: right;" to="/about">Über mich</router-link>
    </div>
    <router-view></router-view>
    <div class="footer">
      &copy; {{ new Date().getFullYear() }} J-M. Wagner
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
