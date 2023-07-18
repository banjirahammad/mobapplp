<script setup>
const section = {
    title: `Press About MobiCom`,
    sub_title: `Aliquam a augue suscipit, luctus neque purus ipsum neque dolor primis libero tempus, tempor posuere ligula varius`
}
const delay = 300
const press = [
    'images/press-1.png',
    'images/press-2.png',
    'images/press-3.png',
    'images/press-4.png'
]
</script>
<template>
    <!-- PRESS-1
			============================================= -->
    <div id="press-1" class="bg-grey wide-100 press-section division">
        <div class="container">


            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-md-10 offset-md-1 section-title">

                    <!-- Title 	-->
                    <h2 class="h2-lg">{{ section.title }}</h2>

                    <!-- Text -->
                    <p>{{ section.sub_title }}</p>

                </div>
            </div> <!-- END SECTION TITLE -->


            <div class="row">


                <!-- PRESS LOGO IMAGE -->
                <div class="col-sm-6 col-md-3 animated" data-animation="fadeInUp" v-for="(pres, index) in press"
                    :key="index" :data-animation-delay="delay += 100">
                    <div class="press-logo">
                        <a href="#">
                            <img class="img-fluid" :src="pres" alt="press-logo" />
                        </a>
                    </div>
                </div>



            </div> <!-- End row -->


            <!-- PRESS TEXT -->
            <div class="row">
                <div class="col-lg-10 offset-lg-1">
                    <div class="press-txt text-center m-top-20">

                        <!-- Text -->
                        <p class="p-md">Semper lacus cursus porta, feugiat primis in luctus ultrice tellus potenti neque
                            dolor
                            primis in posuere magna nec augue ipsum primis risus auctor purus pretium ligula rutrum
                        </p>

                        <!-- Button -->
                        <a href="#reviews-2" class="btn btn-lightgreen">What Our Clients Say</a>

                    </div>
                </div>
            </div> <!-- END PRESS TEXT -->


        </div> <!-- End container -->
    </div> <!-- END PRESS-1 -->
</template>

<style scoped></style>