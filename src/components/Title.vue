<style lang="scss" scoped>
	.heading {
		h1 {
			background-image: linear-gradient(to right, coral, tomato);
			color: transparent;
			-webkit-background-clip: text;
			display: inline-block;
			letter-spacing: 2px;
			transition: all 0.2s;

			&:hover {
				transform: skewY(2deg) skewX(15deg) scale(1.1);
				text-shadow: 5px 10px 20px rgba(black, 0.2);
			}
		}
	}

	.center-text {
		text-align: center;
	}
</style>

<template>
	<header class="heading center-text">
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