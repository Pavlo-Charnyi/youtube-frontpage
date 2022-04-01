<template>
	<div class="video__container">
		<div class="video__wrapper">
			<img src="http://picsum.photos/400/200" class="video__image" />
			<span class="video__time">17:04</span>
		</div>
		<h4 class="video__title">Watching a new meme every day for 5 years</h4>
		<span class="video__author">Pavlo Charnyi</span>
		<div class="video__views_publication">
			<span class="video__views_count">1.3 bilion views</span>
			<span class="video__publish_date">2 days ago</span>
		</div>
	</div>
</template>

<style>
.video__container,
.video__views_publication {
	font-family: 'Roboto', 'Arial', sans-serif;
	color: #606060;
	font-size: 12px;
}
.video__title {
	color: #000;
	margin-top: 0;
	margin-bottom: 0;
	font-size: 14px;
}
.video__image {
	max-width: 255px;
	max-height: 144px;
	/* remember this */
	object-fit: cover;
	aspect-ratio: 2 / 1;
	display: block;
	min-width: 100%;
}
.video__time {
	background-color: black;
	color: white;
	padding: 2px;
	font-size: 10px;
	position: absolute;
	bottom: 3px;
	right: 3px;
	border-radius: 3px;
	/* height: 12px; */
}
.video__wrapper {
	position: relative;
	display: inline-block;
}
.video__author {
	display: inline-block;
}
.video__views_count::after {
	content: '•';
	margin: 0 2px;
}
</style>
