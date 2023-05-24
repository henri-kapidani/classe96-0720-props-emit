<script>
export default {
	// data() {
	// 	return {
	// 		inputText: '',
	// 	};
	// },
};
</script>

<template>
	<div>
		<input
			type="text"
			@keyup="$emit('visualizeInputText', $event.target.value)"
		/>
		<!-- <button @click="$emit('visualizeInputText', $event.target)">
			Visualizza testo input nello spazio sotto
		</button> -->
	</div>
</template>

<style></style>
