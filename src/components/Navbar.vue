<template>
  <nav>
    <div class="nav-wrapper">
      <a href="#" class="brand-logo">Vuyo Funeral</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="sass.html">Menu 1</a></li>
        <li><a href="badges.html">Menu 2</a></li>
        <li><a href="collapsible.html">Menu 3</a></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
      msg: 'Welcome to form'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
