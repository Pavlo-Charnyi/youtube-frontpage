<script setup>
import AppHeader from './components/AppHeader.vue';
import AppGrid from './components/AppGrid.vue';
import AppBadge from './components/AppBadge.vue';
</script>

<template>
	<div class="page_content">
		<AppHeader />
		<div class="main__content">
			<aside class="p-4 bg-yellow-100">
				<ul>
					<li>1</li>
					<li>2</li>
					<li>3</li>
					<li>4</li>
					<li>5</li>
				</ul>
			</aside>
			<div class="main_content">
				<div>
					<div class="badge__container">
						<AppBadge v-for="i in 20"> Comedies {{ i }}</AppBadge>
					</div>
					<AppGrid />
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.page_content {
}
.main__content {
	display: grid;
	grid-template-columns: auto minmax(0, 1fr);
}
.badge__container {
	display: flex;
	gap: 14px;
	padding: 0.5rem 1rem;
	position: sticky;
	top: 78px;
	z-index: 1;
	background-color: rgba(255, 255, 255, 0.9);
	overflow-x: auto;
}
</style>
