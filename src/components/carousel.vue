

<template>
	<div class="imageCarousel">
	<carousel>
		<slide><img src="../assets/img/22_1757913161.jpg" height="640" width="960"></slide>
		<slide><img src="../assets/img/22_1990865450.jpg" height="640" width="960"></slide>
		<slide><img src="../assets/img/22_2127280541.jpg" height="640" width="960"></slide>
		<slide><img src="../assets/img/22_475379696.jpg" height="640" width="960"></slide>
		<slide><img src="../assets/img/22_576039877.jpg" height="640" width="960"></slide>
	</carousel>
</div>
</template>

<script>
	import { Carousel, Slide } from 'vue-carousel';

	export default {
		name: "imageCarousel",
		components: {
			Carousel,
			Slide
		}
	}
</script>

<style>
.VueCarousel-slide {
  position: relative;
  color: #fff;
  font-family: Arial;
  font-size: 24px;
  text-align: center;
  min-height: 100px;
}

.label {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>