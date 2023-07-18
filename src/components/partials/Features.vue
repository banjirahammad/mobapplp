<script setup>
const section = {
	title: 'Features Never Stop',
	sub_title: `Aliquam a augue suscipit, luctus neque purus ipsum neque dolor primis libero tempus, tempor posuere ligula varius`
}
const delay = 100;

const features = [{
	icon: 'pe-7s-piggy',
	title: 'Super Affordable',
	desc: `Semper lacus cursus porta, feugiat primis in ultrice ligula risus auctor tempus`
},
{
	icon: 'pe-7s-expand1',
	title: 'Fast Turnaround',
	desc: `Semper lacus cursus porta, feugiat primis in ultrice ligula risus auctor tempus`
},
{
	icon: 'pe-7s-refresh-2',
	title: 'Free Updates',
	desc: `Semper lacus cursus porta, feugiat primis in ultrice ligula risus auctor tempus`
},
{
	icon: 'pe-7s-help2',
	title: 'Fast Support',
	desc: `Semper lacus cursus porta, feugiat primis in ultrice ligula risus auctor tempus`
},
]
</script>

<template>
	<!-- FEATURES-2
			============================================= -->
	<section id="features-2" class="bg-lightgrey p-top-60 p-bottom-60 featuress-section division">
		<div class="container">


			<!-- SECTION TITLE 	-->
			<div class="row">
				<div class="col-md-10 offset-md-1 section-title">

					<!-- Title 	-->
					<h2 class="h2-lg">{{ section.title }}</h2>

					<!-- Text -->
					<p>{{ section.sub_title }}
					</p>

				</div>
			</div> <!-- END SECTION TITLE -->


			<div class="row">



				<div class="col-md-6 col-lg-3 animated" v-for="(feature, index) in      features  " :key="index"
					data-animation="fadeInUp" :data-animation-delay="delay += 100">
					<div class="fbox-2 box-icon-lg green-icon">

						<!-- Icon -->
						<span :class="feature.icon"></span>

						<!-- Title -->
						<h5 class="h5-md">{{ feature.title }}</h5>

						<!-- Text -->
						<p class="grey-color">{{ feature.desc }}</p>

					</div>
				</div>


			</div> <!-- End row -->


		</div> <!-- End container -->
	</section> <!-- END FEATURES-2 -->
</template>

<style scoped></style>