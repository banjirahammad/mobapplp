<script setup>

const section = {
    title: 'Experienced and Skilled',
    sub_title: `Feature Integration`,
    desc: `An nullam tempor sapien, eget gravida donec enim ipsum porta justo integer at odio velna vitae auctor integer congue magna undo impedit. Gravida magna lacus odio ac risus auctor tempus dolor feugiat lacinia risus orci auctor purus pretium ligula`,
    short_desc: `An nullam tempor sapien, eget gravida donec enim ipsum porta justo integer at odio velna vitae auctor integer congue gravida donec enim ipsum porta justo integer at odio velna`
}

const img = 'images/image-07.png'

</script>
<template>
    <!-- CONTENT-2
			============================================= -->
    <section id="content-2" class="bg-scroll bg-lightgrey wide-60 content-section division">
        <div class="container">
            <div class="row d-flex align-items-center">


                <!-- CONTENT IMAGE -->
                <div class="col-md-6 animated" data-animation="fadeInRight" data-animation-delay="500">
                    <div class="content-img">
                        <img class="img-fluid" :src="img" alt="content-image" />
                    </div>
                </div>


                <!-- CONTENT TEXT -->
                <div class="col-md-6">
                    <div class="content-txt ind-45">


                        <!-- Title -->
                        <h2 class="h2-xs animated" data-animation="fadeInLeft" data-animation-delay="300">
                            {{ section.title }}
                        </h2>

                        <!-- Text -->
                        <p class="animated" data-animation="fadeInLeft" data-animation-delay="400">
                            {{ section.desc }}
                        </p>

                        <!-- Title -->
                        <h5 class="h5-md animated" data-animation="fadeInLeft" data-animation-delay="500">
                            {{ section.sub_title }}
                        </h5>

                        <!-- Text -->
                        <p class=" animated" data-animation="fadeInLeft" data-animation-delay="600">
                            {{ section.short_desc }}
                        </p>


                    </div>
                </div> <!-- END CONTENT TEXT -->


            </div> <!-- End row -->
        </div> <!-- End container -->
    </section> <!-- END CONTENT-2 -->
</template>

<style scoped></style>