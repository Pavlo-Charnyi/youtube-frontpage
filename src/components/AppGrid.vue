<script setup>
import AppVideo from './AppVideo.vue';
</script>

<template>
	<div
		class="p-4 grid gap-5 grid-cols-1 sm:grid-cols2 md:grid-cols3 lg:grid-cols-4"
	>
		<AppVideo v-for="i in 8" />
	</div>
</template>
