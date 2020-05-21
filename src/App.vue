<template>
	<div id="app">
		<Navbar></Navbar>
		<Content></Content>
		<Footer></Footer>
	</div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Content from "./components/Content.vue";
import Footer from "./components/Footer.vue";

export default {
	name: "App",
	components: {
		Navbar,
		Content,
		Footer
	}
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
