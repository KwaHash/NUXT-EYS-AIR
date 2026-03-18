<template>
	<div class="card-outline flex justify-center items-center bg-white">
		<slot></slot>
	</div>
</template>

<style scoped>
.card-outline {
	box-shadow: 5px 10px 10px 0px rgba(0, 0, 0, 0.05);
	border: none;
}
</style>