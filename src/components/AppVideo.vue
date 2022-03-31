<script>
let img = 'http://picsum.photos/400/200';
</script>
<template>
	<div>
		<div class="video__wrapper">
			<img src="{{img}}" class="video__image" />
			<span class="video__time">17:04</span>
		</div>
		<h4 class="video__title">Watching Andrew's lessons all day long :)</h4>
	</div>
</template>

<style>
.video__title {
	margin-top: 0;
	margin-bottom: 0;
}
.video__image {
	/* width: 400px; */
	/* height: 200px; */
	/* remember this */
	object-fit: cover;
	aspect-ratio: 2 / 1;
	display: block;
	min-width: 100%;
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
.video__wrapper {
	position: relative;
	display: inline-block;
}
</style>
