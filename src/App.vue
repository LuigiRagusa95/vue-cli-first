<template>
	<div id="app">
		<Title />
	</div>
</template>

<script>
import Title from "./components/Title.vue";
export default {
	components: {
		Title,
	},
};
</script>

<style lang="scss">
*,
*::before,
*::after {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

html,
body {
	width: 100%;
	height: 100%;
	font-family: sans-serif;
}

body {
	min-height: 100vh;
}
</style>
