<template>
  <div id="wrapper">
    <nav class="navbar navbar-default">
      <titlebar></titlebar>
    </nav>
      <tablebar></tablebar>
  </div>
</template>

<script>
  import Titlebar from './components/Titlebar.vue'
  import Tablebar from './components/Tablebar.vue'
  export default {
    components: { 'titlebar': Titlebar, 'tablebar': Tablebar }
  }
</script>
