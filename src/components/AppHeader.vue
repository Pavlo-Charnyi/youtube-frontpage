<script setup>
import AppLogo from './AppLogo.vue';
import SearchIcon from '../icons/SearchIcon.vue';
import BellIcon from '../icons/BellIcon.vue';
import GridIcon from '../icons/GridIcon.vue';
import MenuIcon from '../icons/MenuIcon.vue';
import VideoCameraIcon from '../icons/VideoCameraIcon.vue';
import TestIcon from '../icons/TestIcon.vue';
</script>

<template>
	<header>
		<div class="flex gap-4 justify-between items-center">
			<button>
				<MenuIcon class="h-6 w-6" />
			</button>

			<AppLogo class="w-24" />
		</div>
		<form class="w-1/3 justify-between">
			<input type="text" class="w-full" />
			<button class="form_button">
				<SearchIcon class="h-6 w-6" />
			</button>
		</form>
		<div class="flex gap-4 h-9 justify-between items-center">
			<button>
				<VideoCameraIcon class="h-6 w-6" />
			</button>
			<button>
				<GridIcon class="h-6 w-6" />
			</button>
			<button>
				<BellIcon class="h-6 w-6" />
			</button>
			<img src="https://picsum.photos/100/100" class="w-8 h-8 rounded-full" />
		</div>
	</header>
</template>

<style scoped>
header {
	position: sticky;
	top: 0;
	z-index: 1;
	background-color: rgba(255, 255, 255, 0.9);
	padding: 1rem;
	display: flex;
	justify-content: space-between;
	align-items: center;
}

form {
	display: flex;
	border: 1px solid #ccc;
}

.form_button {
	background-color: #f0f0f0;
	padding: 10px;
	height: 100%;
}
</style>
