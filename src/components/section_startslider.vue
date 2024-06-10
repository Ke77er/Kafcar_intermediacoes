<template>
	<!-- Section Started Slider -->
	<section class="section kf-started-slider" id="Inicio">
		<div class="swiper-container">
			<div class="swiper-wrapper">
				<div class="swiper-slide">

					<div class="kf-started-item">
						<div class="slide" style="background-image: url(./src/assets/images/1feed1.png);"></div>
						
					</div>

				</div>
				<div class="swiper-slide">

					<div class="kf-started-item">
						<div class="slide" style="background-image: url(./src/assets/images/1feed2.png);"></div>
						
					</div>

				</div>
				<div class="swiper-slide">

					<div class="kf-started-item">
						<div class="slide" style="background-image: url(./src/assets/images/1feed3.png);"></div>
						
					</div>

				</div>
			</div>

			<div class="swiper-button-prev"></div>
			<div class="swiper-button-next"></div>

		</div>
	</section>
</template>

<script>
export default {
	name: "SectionStartSlider",
	data() {
		return {
		};
	},
	methods: {
	}
}
</script>

<style scoped>
.js-parallax{
	width: 100%;
}

</style>