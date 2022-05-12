<template>
  <b-navbar type="dark" variant="dark" class="navbar">
    <b-navbar-brand href="#">Inventory</b-navbar-brand>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="/">
          <b-button type="button" class="inv-button">INVENTORY</b-button>
        </b-nav-item>
        <b-nav-item href="#">
          <b-button type="button" class="inv-button">HEALTH</b-button>
        </b-nav-item>
        <b-nav-item href="#">
          <b-button type="button" class="inv-button">SKILLS</b-button>
        </b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">BACK</b-nav-item>
        
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  name: 'AppNavbar',
  props: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .navbar {
    padding-bottom: 0;
    padding-top: 3px;

    .nav-link {
      padding: 0!important;
      padding-top: 3px;
      
      button {
        border-radius: 0!important;
      }

    }

  }
</style>
