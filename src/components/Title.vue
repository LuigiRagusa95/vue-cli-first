<template>
	<h1>{{ title }}</h1>
</template>

<script>
export default {
	name: "Title",
	data() {
		return {
			title: "La mia prima app con Vue CLI!",
		};
	},
};
</script>

<style lang="scss" scoped>
h1 {
	font-size: 2rem;
	line-height: 2.5rem;
}
</style>
