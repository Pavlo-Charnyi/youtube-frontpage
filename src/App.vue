<script setup>
import AppVideo from './components/AppVideo.vue';
</script>

<template>
	<div class="app__grid">
		<AppVideo v-for="i in 10" />
	</div>
</template>

<style scoped>
.app__grid {
	display: grid;
	grid-template-columns: repeat(5, 1fr);
	column-gap: 15px;
	row-gap: 60px;
}
</style>
