<style lang="scss" scoped>
	.heading {
		background-image: linear-gradient(to right, coral, tomato);
	}
</style>

<template>
	<header class="heading">
		<h1 v-text="msg"></h1>
	</header>
</template>

<script>
	export default {
		props: {
			msg: {
				type: String,
				default: "Title"
			}
		},
		name: "Title"
	};
</script>