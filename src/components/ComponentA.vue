<script>
export default {
	data() {
		return {
			inputText: '',
		};
	},
};
</script>

<template>
	<div>
		<input type="text" v-model="inputText" />
		<button @click="$emit('visualizeInputText', inputText)">
			Visualizza testo input nello spazio sotto
		</button>
	</div>
</template>

<style></style>
