<!-- Layout -->
<template>
	<div class="container">
		<h2>Massive Testing</h2>
		<form action="">
			<!-- Create Input + label molecule components -->
			<FormInput></FormInput>
		</form>
	</div>
</template>

<!-- Logic -->
<script>
import FormInput from "./FormInput.vue";
// Component for each input + label in the form.
export default {
	name: "FormPage",
	components: {
		FormInput,
	},
	props: {
		// no props are passed.
	},

	data() {
		return {
			formOptions: {
				username: "",
				password: "",
				email: "",
			},
		};
	},

	computed: {
		// Total Characters in a input
	},

	methods: {},
};
</script>

<!-- Styling -->
<style lang="css" scoped>
.container {
	background: rgb(14, 14, 14);
	height: 90dvh;
	margin-top: 1rem;
	padding: 1rem;
}
</style>
