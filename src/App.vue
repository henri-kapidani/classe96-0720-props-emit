<script>
import ComponentA from './components/ComponentA.vue';
import ComponentB from './components/ComponentB.vue';

export default {
	data() {
		return {
			textInInput: '',
		};
	},
	components: {
		ComponentA,
		ComponentB,
	},
	methods: {
		changeTextInput(valueFromEmit) {
			console.log(valueFromEmit);
			this.textInInput = valueFromEmit;
		},
	},
};
</script>

<template>
	<ComponentA @visualizeInputText="changeTextInput" />
	<ComponentB :textToVisualize="textInInput" />
</template>

<style></style>

<!-- eleForm.addEventListener('submit', function(event) {
	event.preventDefault();
}) -->
