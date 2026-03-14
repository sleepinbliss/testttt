<template>
	<div>
		<label for="username"></label>
		<input type="text" name="" id="username" class="TextInput" />
	</div>
</template>
<script>
export default {
	name: "FormInput",
	props: {},
	data() {},
	computed: {},
	methods: {},
};
</script>
<style>
.TextInput {
	width: 100%;
	height: 2rem;
	outline: 0;
	border: 0;
	border-radius: 5px;
}
.TextInput.focus {
}

.TextInput.hover {
}
</style>
