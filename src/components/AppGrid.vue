<script setup>
import AppVideo from './AppVideo.vue';
</script>

<template>
	<div
		class="p-4 grid gap-5 grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 bg-gray-50"
	>
		<AppVideo
			title="Frontend developer roadmap: all you need to know about FrontEnd Development"
			author="Pavlo Charnyi"
			views="700k"
			publish_date="week ago"
			avatar="https://picsum.photos/seed/one1/36/36"
			video_image_url="https://picsum.photos/seed/one/1920/1080"
		>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew Luca"
			views="1.3 Million"
			publish_date="month ago"
			avatar="https://picsum.photos/seed/two2/36/36"
			video_image_url="https://picsum.photos/seed/two/1920/1080"
		>
		</AppVideo>
		<AppVideo
			title="Building own IronMan suit at home"
			author="Tony Stark"
			views="2 Billion"
			publish_date="1 year ago"
			avatar="https://picsum.photos/seed/three3/36/36"
			video_image_url="https://picsum.photos/seed/three/1920/1080"
		>
		</AppVideo>
		<AppVideo
			title="In Search of Holy Grail"
			author="Indiana Jones"
			views="77 views"
			publish_date="1 day ago"
			avatar="https://picsum.photos/seed/four4/36/36"
			video_image_url="https://picsum.photos/seed/four/1920/1080"
		>
		</AppVideo>
		<AppVideo
			title="Secrets of moving to Linux"
			author="Linus Torvalds"
			views="10 Billion"
			publish_date="10 years ago"
			avatar="https://picsum.photos/seed/five/36/36"
			video_image_url="https://picsum.photos/seed/five/1920/1080"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/test/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew"
			views="1.3 Billion"
			publish_date="week ago"
			avatar="https://picsum.photos/seed/six/36/36"
			video_image_url="https://picsum.photos/seed/six/1920/1080"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/test/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew"
			views="1.3 Billion"
			publish_date="week ago"
			avatar="https://picsum.photos/seed/seven/36/36"
			video_image_url="https://picsum.photos/seed/seven/1920/1080"
		>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew"
			views="1.3 Billion"
			publish_date="week ago"
			avatar="https://picsum.photos/seed/eight/36/36"
			video_image_url="https://picsum.photos/seed/eight/1920/1080"
		>
		</AppVideo>
	</div>
</template>
