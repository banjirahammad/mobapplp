<script setup>
const section = {
    title: `Awesome Screenshots`,
    sub_title: `Aliquam a augue suscipit, luctus neque purus ipsum neque dolor primis libero tempus,
                        tempor posuere ligula varius`
}
const frame = 'images/portfolio/screen-8.jpg'
const screenShots = [
    'images/portfolio/screen-1.jpg',
    'images/portfolio/screen-2.jpg',
    'images/portfolio/screen-3.jpg',
    'images/portfolio/screen-4.jpg',
    'images/portfolio/screen-5.jpg',
    'images/portfolio/screen-6.jpg',
    'images/portfolio/screen-7.jpg',
    'images/portfolio/screen-8.jpg',
]
</script>
<template>
    <!-- SCREENSHOTS-1
			============================================= -->
    <section id="screens-1" class="bg-scroll bg-green screens-section division"
        style="background-image: url(images/tra-bg-1.png);">


        <!-- SECTION TITLE -->
        <div class="container">
            <div class="row">
                <div class="col-md-10 offset-md-1 white-color section-title">

                    <!-- Title 	-->
                    <h2 class="h2-lg">{{ section.title }}</h2>

                    <!-- Text -->
                    <p>{{ section.sub_title }}
                    </p>

                </div>
            </div> <!-- End row -->
        </div> <!-- END SECTION TITLE -->


        <!-- SCREENSHOTS CAROUSEL -->
        <div class="screenshots-wrap">
            <div class="screens-carousel">


                <!-- Screen #1 -->
                <div class="carousel-item" v-for="(screnShot, index) in screenShots" :key="index">
                    <img :src="screnShot" alt="screenshot">
                </div>

            </div>


            <!-- IPHONE FRAME -->
            <div class="iphone-frame">
                <img src="/src/assets/images/iphone.png" alt="iphone-image">
            </div>


        </div> <!-- END SCREENSHOTS CAROUSEL -->


    </section> <!-- END SCREENSHOTS-1 -->
</template>

<style scoped></style>