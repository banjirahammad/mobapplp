<script setup>
const section = {
    title: 'Customers Feedback',
    sub_title: `Aliquam a augue suscipit, luctus neque purus ipsum neque dolor primis libero tempus, tempor posuere ligula varius`,
}

const feedbacks = [
    {
        image: 'images/review-author-1.jpg',
        name: `pebz13`,
        title: `Programmer`,
        s_comment: `Super Support!`,
        comment: `Etiam sapien sem at sagittis congue augue massa varius egestas magna suscipit magna tempus aliquet porta rutrum sodales auctor integer risus auctor rutrum`,
    },
    {
        image: 'images/review-author-2.jpg',
        name: `Evelyn Martinez`,
        title: `Housewife`,
        s_comment: `Simple and Useful!`,
        comment: `At sagittis congue augue egestas egestas magna ipsum vitae purus ipsum primis in cubilia laoreet augue egestas luctus donec diam ociis ultrice ligula magna suscipit lectus gestas augue in cubilia laoreet`,
    },
    {
        image: 'images/review-author-3.jpg',
        name: `Robert Peterson`,
        title: `SEO Manager`,
        s_comment: `Great Flexibility!`,
        comment: `Mauris donec ociis et magnis sapien etiam sapien sem sagittis congue augue egestas et ultrice ligula egestas magna suscipit lectus gestas magna suscipit luctus undo`,
    },
    {
        image: 'images/review-author-4.jpg',
        name: `Leslie Serpas`,
        title: `Internet Surfer`,
        s_comment: `I love this App!`,
        comment: `An augue in cubilia laoreet magna suscipit egestas magna ipsum vitae purus ipsum primis in cubilia laoreet augue ultrice ligula egestas magna suscipit lectus gestas magna viverra dolor neque est gravida`,
    },
    {
        image: 'images/review-author-5.jpg',
        name: `Marisol19`,
        title: `Senior UX/UI Designer`,
        s_comment: `Best App for Around!`,
        comment: `Egestas egestas magna ipsum vitae purus efficitur ipsum primis in cubilia laoreet augue egestas luctus donec augue in cubilia laoreet ociis vitae purus diam`,
    },
    {
        image: 'images/review-author-6.jpg',
        name: `Dan Hodges`,
        title: `Graphic Designer`,
        s_comment: `Minimalistic & Beautiful!`,
        comment: `Augue egestas volutpat egestas et augue in cubilia laoreet magna suscipit luctus undo blandit vitae purus non diam tempus aliquet porta rutrum gestas neque est gravida`,
    },
    {
        image: 'images/review-author-7.jpg',
        name: `Amelie Peterson`,
        title: `Senior UX/UI Designer`,
        s_comment: `Awesome Design!`,
        comment: `Egestas et lobortis magna suscipit luctus undo blandit vitae purus lobortis non diam tempus aliquet porta rutrum arcu aenean primis in augue in cubilia laoreet`,
    },

]

</script>
<template>
    <!-- TESTIMONIALS-2
			============================================= -->
    <section id="reviews-2" class="wide-100 bg-lightgrey reviews-section division">
        <div class="container">


            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-md-10 offset-md-1 section-title">

                    <!-- Title 	-->
                    <h2 class="h2-lg">{{ section.title }}</h2>

                    <!-- Text -->
                    <p> {{ section.sub_title }} </p>

                </div>
            </div> <!-- END SECTION TITLE -->


            <!-- TESTIMONIALS CAROUSEL -->
            <div class="reviews-carousel">
                <div class="center slider">


                    <!-- TESTIMONIAL  -->
                    <div class="review-2" v-for="(feedback, index) in feedbacks" :key="index">

                        <!-- Testimonial Text -->
                        <div class="review-txt">

                            <!-- Title -->
                            <h5 class="h5-lg">{{ feedback.s_comment }}</h5>

                            <!-- Testimonial Text -->
                            <p>{{ feedback.comment }}</p>

                        </div>

                        <!-- Testimonial Author Avatar -->
                        <div class="testimonial-avatar text-center">
                            <img :src="feedback.image" alt="review-author-avatar">
                            <p class="testimonial-autor">{{ feedback.name }}</p>
                            <span>{{ feedback.title }}</span>
                        </div>

                        <!-- App Rating -->
                        <div class="app-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>

                    </div> <!-- END TESTIMONIAL -->


                </div>
            </div> <!-- TESTIMONIALS CAROUSEL -->


        </div> <!-- End container -->
    </section> <!-- END TESTIMONIALS-2 -->
</template>

<style scoped></style>