<script setup>
const hero = {
	imgUrl: 'images/hero-10-img.png',
	youtubeUrl: 'https://www.youtube.com/watch?v=kuceVNBTJio'
}
const green = 'green-color'
const animate = 'h2-xs animated'
</script>
<template>
	<!-- HERO-10
			============================================= -->
	<section id="hero-10" class="bg-fixed bg-lightgrey hero-section division">
		<div class="container">
			<div class="row d-flex align-items-center">


				<!-- HERO TEXT -->
				<div class="col-md-7 col-lg-6">
					<div class="hero-txt">


						<!-- Title -->
						<h2 :class="animate" data-animation="fadeInUp" data-animation-delay="300">
							We make amazing landing pages <span :class="green">for your mobile App</span>
						</h2>

						<!-- Video Link -->
						<div class="modal-video grey-color animated" data-animation="fadeInUp" data-animation-delay="500">
							<a class="video-popup" :href="hero.youtubeUrl">
								<!-- Change the video link HERE!!! -->
								<span><i class="far fa-play-circle"></i></span>
								Watch the Overview
							</a>
						</div>


					</div> <!-- End row -->
				</div> <!-- End container -->


				<!-- HERO IMAGE -->
				<div class="col-md-5 col-lg-4 offset-lg-2 animated" data-animation="fadeInRight" data-animation-delay="500">
					<div class="hero-img">
						<img class="img-fluid" :src="hero.imgUrl" alt="hero-image">
					</div>
				</div>


			</div> <!-- End row -->
		</div> <!-- End container -->
	</section> <!-- END HERO-10 -->
</template>

<style scoped></style>