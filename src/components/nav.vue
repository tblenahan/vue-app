<template>
  <div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <img src="../assets/km-str-logo 2.png" style="height: auto; max-width: 120px;">

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Link</b-nav-item>
        <b-nav-item href="#" disabled>Disabled</b-nav-item>
      </b-navbar-nav>
    
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>

export default {
  name: 'navbar',
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- <style scoped>
 h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
} 
</style> -->