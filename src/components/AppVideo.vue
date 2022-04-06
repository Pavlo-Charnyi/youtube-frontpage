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
				<h4 class="line-clamp-2 video__title">
					Watch me developing own youtube application. Live and free of charge.
				</h4>

				<div class="text-sm text-gray-500">
					<div>Super User</div>
					<div>
						<span class="video__views_count">1.3 billion views</span>
						<span>2 days ago</span>
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
