<script setup>
defineProps({
	title: String,
	author: String,
	views: String,
	publish_date: String,
	avatar: String,
	video_image_url: String,
});
</script>

<template>
	<div>
		<div class="relative">
			<slot name="video_image">
				<img :src="video_image_url" class="object-cover aspect-video" />
			</slot>

			<span class="video__time">14:10</span>
		</div>

		<div class="flex gap-3 items-start mt-2">
			<img :src="avatar" class="rounded-full" />

			<div class="grow">
				<h4 class="line-clamp-2 video__title">
					{{ title }}
				</h4>

				<div class="text-sm text-gray-500">
					<div>{{ author }}</div>
					<div>
						<span class="video__views_count">{{ views }}</span>
						<span>{{ publish_date }}</span>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.video__title {
	font-size: 14px;
	margin-top: 0px;
	margin-bottom: 0px;
	font-weight: 500;
}

.video__time {
	background-color: black;
	color: white;
	padding: 5px;
	font-size: 14px;
	position: absolute;
	bottom: 0px;
	right: 0px;
}
.video__views_count::after {
	content: '•';
	margin: 0 2px;
}
</style>
