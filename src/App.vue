<template>
  <div id="app">
	<navigation-menu></navigation-menu>
	<div class="container">
    	<!-- <router-view></router-view> -->
	</div>
  </div>
</template>

<script>
import NavigationMenu from './components/NavigationMenu.vue';

export default {
  name: 'app',
  components: {
	  NavigationMenu
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  top:50%;
  left:50%;
  height: 75%;
  width: 75%;
  transform: translate(17%, 17%);
  background-color: #ffffff;
  border:2px solid #2c3e50;
}
</style>
