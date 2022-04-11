<script setup>
import AppVideo from './AppVideo.vue';
</script>

<template>
	<div
		class="p-4 grid gap-5 grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 bg-gray-50"
	>
		<AppVideo
			title="Frontend developer roadmap: all you need to know about FE"
			author="Pavlo Charnyi"
			views="700k"
			publish_date="week ago"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/1/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew Luca"
			views="1.3 Million"
			publish_date="month ago"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/2/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="Building own IronMan suit at home"
			author="Tony Stark"
			views="2 Billion"
			publish_date="1 year afo"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/3/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="In Search of Holy Grail"
			author="Indiana Jones"
			views="77 views"
			publish_date="1 day ago"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/4/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="Secrets of moving to Linux"
			author="Linus Torvalds"
			views="10 Billion"
			publish_date="10 years ago"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/5/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew"
			views="1.3 Billion"
			publish_date="week ago"
		>
			<template #video_image> </template>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew"
			views="1.3 Billion"
			publish_date="week ago"
		>
			<template #video_image>
				<img
					src="https://picsum.photos/seed/7/1920/1080"
					class="object-cover aspect-video"
				/>
			</template>
		</AppVideo>
		<AppVideo
			title="Master VUE in 30 days: use best modern practices"
			author="Andrew"
			views="1.3 Billion"
			publish_date="week ago"
		>
			<template #video_image> </template>
		</AppVideo>
	</div>
</template>
