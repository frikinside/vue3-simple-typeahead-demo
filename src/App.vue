<template>
	<a href="https://github.com/frikinside/vue3-simple-typeahead" class="fork-in-github"
		><img
			loading="lazy"
			width="149"
			height="149"
			src="https://github.blog/wp-content/uploads/2008/12/forkme_right_darkblue_121621.png?resize=149%2C149"
			class="attachment-full size-full"
			alt="Fork me on GitHub"
			data-recalc-dims="1"
	/></a>

	<header>
		<section class="container">
			<img alt="Logo" src="./assets/logo.png" />
			<h2><img alt="Vue icon" src="./assets/vue-logo.png" /> vue3-simple-typeahead</h2>
			<div class="badges">
				<a href="https://www.npmjs.com/package/vue3-simple-typeahead"><img src="https://img.shields.io/npm/v/vue3-simple-typeahead.svg" alt="npm"/></a>
				<a href="https://v3.vuejs.org/"><img src="https://img.shields.io/badge/vue-3.x-brightgreen.svg" alt="vue3"/></a>
				<!-- <a href="https://www.npmjs.com/package/vue3-simple-typeahead?activeTab=dependencies"><img src="https://img.shields.io/david/frikinside/vue3-simple-typeahead" alt="no-dependecies"/></a> -->
				<a href="https://en.wikipedia.org/wiki/MIT_License"><img src="https://img.shields.io/npm/l/vue3-simple-typeahead" alt="License"/></a>
				<a href="https://www.npmjs.com/package/vue3-simple-typeahead"><img src="https://img.shields.io/npm/dt/vue3-simple-typeahead.svg" alt="npm"/></a>
				<a href="https://www.npmjs.com/package/vue3-simple-typeahead"><img src="https://img.shields.io/bundlephobia/min/vue3-simple-typeahead?color=brightgreen" alt="npm bundle size"/></a>
			</div>
		</section>
	</header>
	<section class="container">
		<form>
			<demo-1></demo-1>
			<demo-2></demo-2>
			<demo-3></demo-3>
		</form>
	</section>
</template>

<script>
	import Demo1 from './components/Demo1.vue';
	import Demo2 from './components/Demo2.vue';
	import Demo3 from './components/Demo3.vue';

	export default {
		name: 'App',
		components: {
			Demo1,
			Demo2,
			Demo3,
		},
	};
</script>

<style>
	#app {
		font-family: Avenir, Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		color: #2c3e50;
	}
	#app .fork-in-github {
		position: absolute;
		right: 0;
		z-index: 9;
	}
	#app header {
		padding: 4rem 0 2rem 0;
		margin-bottom: 4rem;
		text-align: center;
		background: #f4f5f6;
		border: 0.1rem solid #d1d1d1;
	}
	#app header h2 {
		margin-top: 20px;
	}
	#app header h2 img {
		vertical-align: middle;
	}
	#app header .badges a {
		vertical-align: text-top;
	}
	#app header .badges a + a {
		margin-left: 5px;
	}
	#app .demo:not(:last-child) {
		border-bottom: 0.1rem dashed #d1d1d1;
		padding-bottom: 2rem;
		margin-bottom: 4rem;
	}
</style>
