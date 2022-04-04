<template>
	<div>
		<div class="relative">
			<img
				src="https://picsum.photos/1080/1920"
				class="object-cover aspect-video"
			/>
			<span class="video__time">14:10</span>
		</div>

		<div class="flex gap-3 items-start mt-2">
			<img src="https://picsum.photos/36/36" class="rounded-full" />

			<div class="grow">
				<h4 class="line-clamp-2 video_title">
					Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique,
					voluptatem facere! Natus maiores perspiciatis reprehenderit
					consectetur similique esse tempora ex architecto ducimus maxime
					commodi rem id, distinctio itaque, nesciunt laudantium!
				</h4>

				<div class="text-sm text-gray-500">
					<div>supeuser</div>
					<div>10m . 2 days ago</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.video_title {
	font-size: 14px;
}
.video__title {
	margin-top: 0px;
	margin-bottom: 0px;
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
</style>
