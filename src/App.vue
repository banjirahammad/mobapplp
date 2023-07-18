<script setup>
import Header from './components/partials/Header.vue';
import Hero from './components/partials/Hero.vue'
import Features from './components/partials/Features.vue';
import Feedback from './components/partials/Feedback.vue';
import Experienced from './components/partials/Experienced.vue';
import ScreenShots from './components/partials/ScreenShots.vue';
import Countdown from './components/partials/Countdown.vue';
import Press from './components/partials/Press.vue';
import Team from './components/partials/Team.vue';
import ContactForm from './components/partials/ContactForm.vue'
import Footer from './components/partials/Footer.vue';
</script>

<template>
    <div id="page" class="page">
        <Header />

        <Hero />

        <Features />

        <Experienced />

        <ScreenShots />

        <Team />

        <Countdown />


        <!-- VIDEO-4
			============================================= -->
        <div id="video-4" class="bg-scroll bg-grey video-section division">
            <div class="container">


                <div class="row">
                    <div class="video-inner-bg">
                        <div class="col-xl-12">
                            <div class="video-content">


                                <!-- VIDEO PREVIEW -->
                                <div class="video-preview text-center">


                                    <!-- Change the link HERE!!! -->
                                    <a class="video-popup" href="https://www.youtube.com/watch?v=kuceVNBTJio">

                                        <!-- Play Icon -->
                                        <div class="video-block-wrapper">
                                            <div class="play-icon-green"></div>
                                        </div>

                                        <!-- Preview Image -->
                                        <img class="img-fluid" src="/src/assets/images/video-4-img.jpg" alt="video-preview">

                                    </a>


                                </div> <!-- END VIDEO PREVIEW -->


                            </div> <!-- End video-content -->
                        </div> <!-- END CONTENT TEXT -->
                    </div> <!-- End Inner Background -->
                </div> <!-- End row -->


                <div class="row">
                    <div class="col-lg-10 offset-lg-1 text-center m-top-100">

                        <!-- Text -->
                        <p class="p-md">Integer at odio velna vitae auctor integer congue magna at risus auctor purus
                            pretium
                            ligula rutrum arcu aenean primis in pharetra ultrice ligula luctus blandit congue magna undo
                            impedit
                            varius feugiat nulla arcu
                        </p>

                        <!-- Store Badges -->
                        <div class="stores-badge m-top-30">

                            <!-- AppStore -->
                            <a href="#" class="store">
                                <img class="appstore-original" src="/src/assets/images/store_badges/appstore.png"
                                    width="160" height="50" alt="appstore-logo" />
                            </a>

                            <!-- Google Play -->
                            <a href="#" class="store">
                                <img class="googleplay-original" src="/src/assets/images/store_badges/googleplay.png"
                                    width="171" height="50" alt="googleplay-logo" />
                            </a>

                            <!-- Aamazon Market 
								<a href="#" class="store">
									<img class="amazon-original" src="/src/assets/images/store_badges/amazon.png" width="158" height="50" alt="amazon-logo" />
								</a>  -->

                            <!-- Windows Market  
								<a href="#" class="store">
									<img class="windows-original" src="/src/assets/images/store_badges/windows.png" width="164" height="50" alt="windows-logo" />
								</a> -->

                        </div>

                    </div>
                </div>


            </div> <!-- End container -->
        </div> <!-- END VIDEO-4 -->


        <Feedback />

        <!-- DOWNLOAD-3
			============================================= -->
        <section id="download-3" class="bg-lightgrey wide-100 download-section">
            <div class="bg-scroll bg-inner bg-dark division">
                <div class="container white-color">
                    <div class="row d-flex align-items-center">


                        <!-- DOWNLOAD IMAGE -->
                        <div class="col-md-5 col-lg-4 animated" data-animation="fadeInRight" data-animation-delay="500">
                            <div class="download-3-img text-center ind-15">
                                <img class="img-fluid" src="/src/assets/images/image-10.png" alt="download-image">
                            </div>
                        </div>


                        <!-- DOWNLOAD TXT -->
                        <div class="col-md-7 col-lg-7 offset-lg-1">
                            <div class="download-txt ind-30">


                                <!-- Title -->
                                <h2 class="h2-xs animated" data-animation="fadeInLeft" data-animation-delay="300">
                                    It’s perfect time to join MobiCom
                                </h2>

                                <!-- Text -->
                                <p class="p-lg animated" data-animation="fadeInLeft" data-animation-delay="400">
                                    Feugiat eros, ac tincidunt ligula massa in faucibus orci luctus posuere cubilia
                                    curae integer
                                    congue leo metus
                                </p>

                                <!-- HERO STORE BADGES -->
                                <div class="stores-badge animated" data-animation="fadeInLeft" data-animation-delay="500">

                                    <!-- AppStore -->
                                    <a href="#" class="store">
                                        <img class="appstore-grey" src="/src/assets/images/store_badges/appstore-grey.png"
                                            width="158" height="50" alt="appstore-logo">
                                    </a>

                                    <!-- Google Play -->
                                    <a href="#" class="store">
                                        <img class="googleplay-grey"
                                            src="/src/assets/images/store_badges/googleplay-grey.png" width="168"
                                            height="50" alt="googleplay-logo">
                                    </a>

                                </div>


                            </div>
                        </div> <!-- END DOWNLOAD TXT -->


                    </div> <!-- End row -->
                </div> <!-- End container -->
            </div> <!-- End Inner Background -->
        </section> <!-- END DOWNLOAD-3 -->
        
        <!-- FAQs-1
			============================================= -->
        <section id="faqs-1" class="bg-fixed bg-lightgrey wide-60 faqs-section division"
            style="background-image: url(/src/assets/images/tra-waves.png);">
            <div class="container">


                <!-- SECTION TITLE -->
                <div class="row">
                    <div class="col-md-10 offset-md-1 section-title">

                        <!-- Title 	-->
                        <h2 class="h2-lg">Troubles with MobiCom?</h2>

                        <!-- Text -->
                        <p>Aliquam a augue suscipit, luctus neque purus ipsum neque dolor primis libero tempus,
                            tempor posuere ligula varius
                        </p>

                    </div> <!-- End row -->
                </div> <!-- END SECTION TITLE -->


                <div class="row">


                    <!-- QUESTIONS HOLDER -->
                    <div class="col-lg-6">
                        <div class="questions-holder ind-30">


                            <!-- QUESTION #1 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="300">

                                <!-- Question -->
                                <h5 class="h5-sm">Lobortis sit magna ornare magna egestas?</h5>

                                <!-- Answer -->
                                <p>Etiam sit amet mauris suscipit sit amet in odio. Integer congue leo metus. Vitae arcu
                                    mollis blandit
                                    ultrice ligula egestas magna suscipit lectus magna suscipit luctus undo blandit
                                    vitae purus laoreet
                                </p>

                            </div>


                            <!-- QUESTION #2 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="400">

                                <!-- Question -->
                                <h5 class="h5-sm">Placeat axime facere omnis volute?</h5>

                                <!-- Answer -->
                                <p>An augue egestas an ipsum vitae emo ligula volute ante ipsum primis in faucibus sit
                                    ametn in odio.
                                    Integer congue leo metus, eu mollis lorem viverra suscipit lectus magna
                                </p>

                            </div>


                            <!-- QUESTION #3 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="500">

                                <!-- Question -->
                                <h5 class="h5-sm">An interdum lobortis pretium ornare?</h5>

                                <!-- Answer -->
                                <p>Feugiat eros, ac tincidunt ligula massa in faucibus orci luctus et ultrices posuere
                                    cubilia curae</p>

                            </div>


                            <!-- QUESTION #4 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="600">

                                <!-- Question -->
                                <h5 class="h5-sm">Interdum lobortis pretium ornare?</h5>

                                <!-- Answer -->
                                <p>Praesent semper, lacus sed cursus porta, odio augue ligula massa risus laoreet.
                                    Laoreet auctor massa
                                    varius egestas amet mauris suscipit semper lacus sed cursus porta feugiat primis
                                </p>

                            </div>


                        </div>
                    </div> <!-- END QUESTIONS HOLDER -->


                    <!-- QUESTIONS HOLDER -->
                    <div class="col-lg-6">
                        <div class="questions-holder ind-30">


                            <!-- QUESTION #5 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="300">

                                <!-- Question -->
                                <h5 class="h5-sm">Aliquam dapibus pretium ornare?</h5>

                                <!-- Answer -->
                                <p>Feugiat eros ligula massa lipsum primis in orci luctus et ultrices posuere cubilia
                                    curae
                                    congue lorem. ante ipsum primis in faucibus bibendum sit amet in odio
                                </p>

                            </div>


                            <!-- QUESTION #6 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="400">

                                <!-- Question -->
                                <h5 class="h5-sm">Pretium purus lacus tempor an ipsum vitae augue egestas emo ligula?
                                </h5>

                                <!-- Answer -->
                                <p>Praesent semper lacus sed cursus porta, feugiat primis in orci luctus ligula eros ac
                                    ligula
                                    massa in faucibus orci luctus et ultrices posuere ante ipsum primis in faucibus
                                    bibendum sit
                                    amet in odio.
                                </p>

                            </div>


                            <!-- QUESTION #6 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="500">

                                <!-- Question -->
                                <h5 class="h5-sm">Dapibus lobortis pretium ornare?</h5>

                                <!-- Answer -->
                                <p>Praesent semper, lacus sed cursus porta,feugiat primis in faucibus orci luctus
                                    tincidunt ligula
                                    ultrice sapien egestas lobortis magna
                                </p>

                            </div>


                            <!-- QUESTION #7 -->
                            <div class="question animated" data-animation="fadeInUp" data-animation-delay="600">

                                <!-- Question -->
                                <h5 class="h5-sm">Interdum lobortis pretium ornare?</h5>

                                <!-- Answer -->
                                <p>Feugiat eros, ac tincidunt ligula massa in faucibus orci luctus et ultrices posuere
                                    cubilia curae
                                    integer congue leo metus, eu mollis lorem primis in orci
                                </p>

                            </div>


                        </div>
                    </div> <!-- END  QUESTIONS HOLDER -->


                </div> <!-- End row -->



            </div> <!-- End container -->
        </section> <!-- END FAQs-1 -->

        <Press />

        <!-- NEWSLETTER-2
			============================================= -->
        <section id="newsletter-2" class="bg-scroll bg-green newsletter-section division">
            <div class="container white-color">
                <div class="row d-flex align-items-center">


                    <!-- NEWSLETTER TEXT -->
                    <div class="col-lg-6">
                        <div class="newsletter-txt">

                            <!-- Title -->
                            <h3 class="h3-xs">Stay up to date with our news, ideas and updates</h3>

                        </div>
                    </div>


                    <!-- NEWSLETTER FORM -->
                    <div class="col-lg-6">
                        <form class="newsletter-form p-left-30">

                            <div class="input-group">
                                <input type="email" class="form-control" placeholder="Your email address" required
                                    id="s-email">
                                <span class="input-group-btn">
                                    <button type="submit" class="btn"><i class="fas fa-arrow-right"></i></button>
                                </span>
                            </div>

                            <!-- Newsletter Form Notification -->
                            <label for="s-email" class="form-notification"></label>

                        </form>
                    </div>


                </div> <!-- End row -->
            </div> <!-- End container -->
        </section> <!-- END NEWSLETTER-2 -->


        <Footer />


        <ContactForm />

    </div>
</template>

<style scoped></style>