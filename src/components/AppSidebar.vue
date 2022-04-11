<script setup>
import AppMenuItem from './AppMenuItem.vue';
import LibraryIcon from '../icons/LibraryIcon.vue';
import HomeIcon from '../icons/HomeIcon.vue';
import ExploreIcon from '../icons/ExploreIcon.vue';
import ShortsIcon from '../icons/ShortsIcon.vue';
import SubscriptionsIcon from '../icons/SubscriptionsIcon.vue';
</script>

<template>
	<aside>
		<div class="menu__block">
			<AppMenuItem title="Home">
				<template #icon>
					<HomeIcon class="w-6 h-6" />
				</template>
			</AppMenuItem>

			<AppMenuItem title="Explore">
				<template #icon>
					<ExploreIcon class="w-6 h-6" />
				</template>
			</AppMenuItem>
			<AppMenuItem title="Shorts">
				<template #icon>
					<ShortsIcon class="w-6 h-6" />
				</template>
			</AppMenuItem>
			<AppMenuItem title="Subscriptions">
				<template #icon>
					<SubscriptionsIcon class="w-6 h-6" />
				</template>
			</AppMenuItem>
		</div>

		<div class="menu__block">
			<h3>Subscriptions</h3>
			<AppMenuItem title="Library">
				<template #icon>
					<LibraryIcon class="w-6 h-6" />
				</template>
			</AppMenuItem>
			<AppMenuItem title="History" />
			<AppMenuItem title="Your Videos" />
			<AppMenuItem title="Watch Later" />
		</div>

		<div class="menu__block">
			<h3>More from YouTube</h3>
			<AppMenuItem title="Liked Videos" />
			<AppMenuItem title="Gaming" />
			<AppMenuItem title="Live" />
			<AppMenuItem title="Learning" />
		</div>
	</aside>
</template>

<style scoped>
.menu__block {
	padding: 1rem;
}

.menu__block + .menu__block {
	border-top: 1px solid gray;
}

.menu__block > h3 {
	display: none;
}

@media (min-width: 640px) {
	.menu__block > h3 {
		display: block;
		font-weight: 700;
		color: gray;
		text-transform: uppercase;
		font-size: 0.9rem;
		margin-bottom: 0.5rem;
	}
}
</style>
