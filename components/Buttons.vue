<template>
	<div class="buttons">
		<router-link tag="button" to="/t2">T2</router-link>
		<router-link tag="button" to="/tea">Tea</router-link>
		<router-link tag="button" to="/hat">Hat</router-link>
	</div>
</template>
<script>
export default {
	name: 'Buttons'
};
</script>
<style scoped>
.buttons {
	width: 100%;
}

button {
	padding: 16px 32px;
	border-radius: 4px;
	font-size: 16px;
	font-weight: 500;
	color: #777;
}
</style>
