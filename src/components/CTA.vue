<template>
	<div class="slider-section">
		<section class="home-slider slider center-caption">
			<b-carousel
            label-next=""
            label-prev=""
            :interval="4000"
            style="text-shadow: 0px 0px 2px #000"
            controls
            indicators
            >
                <b-carousel-slide img-src="https://www.cgv.vn/media/banner/cache/1/b58515f018eb873dafa430b6f9ae0c1e/t/r/trum-cuoi-sieu-dang-980wx448h.jpg"></b-carousel-slide>
				<b-carousel-slide img-src="https://www.cgv.vn/media/banner/cache/1/b58515f018eb873dafa430b6f9ae0c1e/x/e/xem_phim_web_980x448.jpg"></b-carousel-slide>
			</b-carousel>
		</section>
	</div>
</template>

<script>


export default {

}
</script>
