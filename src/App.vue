<style lang="scss" scoped>
	$color-gray-light: #f7f7f7;

	.section-about {
		background-color: $color-gray-light;
		padding: 10rem 0;
	}
</style>

<template>
	<div id="app">
		<main>
			<section class="section-about">
				<main-heading msg="Exiting tours for adventorous people"></main-heading>
			</section>
		</main>
	</div>
</template>

<script>
	import Title from "./components/Title";

	export default {
		name: "app",
		components: {
			"main-heading": Title
		}
	};
</script>
