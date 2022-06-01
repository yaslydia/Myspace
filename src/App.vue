<template>
  <NavBar />
  <router-view/>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap';
import NavBar from './components/Navbar';

export default {
  name: "App",
  components: {
    NavBar,
  }
}

</script>

<style>
</style>
