<script>
export default {
	props: {
		textToVisualize: String,
	},
};
</script>

<template>
	<div class="text">{{ textToVisualize }}</div>
</template>

<style>
.text {
	min-height: 5rem;
	background-color: salmon;
}
</style>
