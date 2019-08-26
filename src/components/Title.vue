<style lang="scss" scoped>
</style>

<template>
	<header>
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