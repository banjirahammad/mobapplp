<script setup>
const section = {
    title: 'Our Executive Team',
    sub_title: `Aliquam a augue suscipit, luctus neque purus ipsum neque dolor primis libero tempus, tempor posuere ligula varius`
}
const delay = 300;

const teams = [
    {
        imgUrl: 'images/team-1.jpg',
        name: 'Jonathan Barnes',
        title: 'Founder',
    },
    {
        imgUrl: 'images/team-2.jpg',
        name: 'Hannah Harper',
        title: 'Project Manager',
    },
    {
        imgUrl: 'images/team-3.jpg',
        name: 'Matthew Anderson',
        title: 'Programmer',
    },
    {
        imgUrl: 'images/team-4.jpg',
        name: 'Megan Coleman',
        title: 'Graphic designer',
    },

]
</script>
<template>
    <!-- TEAM-1
			============================================= -->
    <section id="team-1" class="bg-fixed bg-lightgrey wide-100 team-section division">
        <div class="container">


            <!-- SECTION TITLE -->
            <div class="row">
                <div class="col-md-10 offset-md-1 section-title">

                    <!-- Title 	-->
                    <h2 class="h2-lg">O{{ section.title }}</h2>

                    <!-- Text -->
                    <p>{{ section.sub_title }}
                    </p>

                </div> <!-- End row -->
            </div> <!-- END SECTION TITLE -->


            <div class="row">


                <!-- TEAM MEMBER #1 -->
                <div class="col-md-6 col-lg-3 animated" data-animation="fadeInUp" :data-animation-delay="delay += 100"
                    v-for="(team, index) in teams">
                    <div class="team-member green-hover">
                        <div class="box-line"></div>

                        <!-- Team Member Photo -->
                        <div class="team-member-photo">
                            <img class="img-fluid" :src="team.imgUrl" alt="team-member-foto">
                        </div>

                        <!-- Team Member Meta -->
                        <div class="team-img-meta">
                            <h5 class="h5-sm">{{ team.name }}</h5>
                            <span>{{ team.title }}</span>

                            <!-- Social Icons -->
                            <div class="tm-social clearfix">
                                <ul class="text-center clearfix">
                                    <li><a href="#" class="ico-facebook"><i class="fab fa-facebook-f"></i></a></li>
                                    <li><a href="#" class="ico-twitter"><i class="fab fa-twitter"></i></a></li>
                                    <li><a href="#" class="ico-dribbble"><i class="fab fa-dribbble"></i></a></li>

                                    <!--
											<li><a href="#" class="ico-behance"><i class="fab fa-behance"></i></a></li>										
											<li><a href="#" class="ico-instagram"><i class="fab fa-instagram"></i></a></li>
											<li><a href="#" class="ico-pinterest"><i class="fab fa-pinterest-p"></i></a></li>
											<li><a href="#" class="ico-google-plus"><i class="fab fa-google-plus-g"></i></a></li>
											<li><a href="#" class="ico-linkedin"><i class="fab fa-linkedin-in"></i></a></li>
											<li><a href="#" class="ico-tumblr"><i class="fab fa-tumblr"></i></a></li>
											<li><a href="#" class="ico-youtube"><i class="fab fa-youtube"></i></a></li>
											<li><a href="#" class="ico-vk"><i class="fab fa-vk"></i></a></li>-->
                                </ul>
                            </div>

                        </div>

                    </div>
                </div> <!-- END TEAM MEMBER #1 -->

            </div> <!-- End row -->


            <!-- JOIN TEAM BUTTON -->
            <div class="row">
                <div class="col-lg-10 offset-lg-1">
                    <div class="join-team text-center m-top-25">

                        <!-- Title -->
                        <h4 class="h4-md"><span>We Are Hiring!</span> Become part of our talented team</h4>

                        <!-- Text -->
                        <p class="p-md">Gravida enim tempor sapien eget gravida donec enim ipsum porta justo at odio
                            velna auctor congue
                            vitae magna at risus enim ipsum porta justo integer
                        </p>

                        <!-- Button -->
                        <a href="#contacts-1" class="btn btn-lightgreen">Join Our Team</a>

                    </div>
                </div>
            </div> <!-- END JOIN TEAM BUTTON -->


        </div> <!-- End container -->
    </section> <!-- END TEAM-1 -->
</template>

<style scoped></style>