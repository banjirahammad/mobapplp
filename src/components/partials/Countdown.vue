<script setup>

const image = 'images/portfolio/screen-8.jpg'
const progress = [
    {
        icon: 'pe-7s-smile',
        digit: 1154,
        title: 'Happy Clilents',
    },
    {
        icon: 'pe-7s-help2',
        digit: 409,
        title: 'Tickets Closed',
    },
    {
        icon: 'pe-7s-users',
        digit: 869,
        title: 'Followers',
    },
    {
        icon: 'pe-7s-coffee',
        digit: 901,
        title: 'Cup of Coffee',
    },

]
const delay = 300
const location = (area) => {
    if (1 === area)
        return 'b-bottom b-right'
    else if (2 === area)
        return 'b-bottom'
    else if (3 === area)
        return 'b-right'
}
</script>
<template>
    <!-- STATISTIC-2
			============================================= -->
    <div id="statistic-2" class="bg-lightgrey wide-60 statistic-section division">
        <div class="container">
            <div class="row d-flex align-items-center">


                <div class="col-md-6 m-bottom-40">
                    <div class="row">


                        <!-- STATISTIC BLOCK #1 -->
                        <div class="col-sm-6 " v-for="(progres, index) in progress" :class="location(++index)" :key="index">
                            <div class="statistic-block text-center box-icon green-icon animated" data-animation="fadeInUp"
                                :data-animation-delay="delay += 100">
                                <span :class="progres.icon"></span>
                                <div class="statistic-number">{{ progres.digit }}</div>
                                <p class="p-md">{{ progres.title }}</p>
                            </div>
                        </div>

                    </div>
                </div> <!-- END STATISTIC BLOCKS -->


                <!-- STATISTIC IMAGE -->
                <div class="col-md-6 col-lg-5 offset-lg-1 animated" data-animation="fadeInLeft" data-animation-delay="400">
                    <div class="statistic-img text-center m-bottom-40">
                        <img class="img-fluid" :src="image" alt="content-image" />
                    </div>
                </div> <!-- END STATISTIC IMAGE -->


            </div> <!-- End row -->
        </div> <!-- End container -->
    </div> <!-- END STATISTIC-2 -->
</template>

<style scoped></style>