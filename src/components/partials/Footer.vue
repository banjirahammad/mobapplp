<script setup>
const logo = {
    url: 'images/logo.png',
    'alt': 'Header Logo'
}
const linkimg = {
    appstore: 'images/store_badges/appstore.png',
    gplay: 'images/store_badges/googleplay.png',
}

const dateFunc = function () {
    const date = new Date()
    return date.getFullYear()
}
</script>
<template>
    <!-- FOOTER-1
			============================================= -->
    <footer id="footer-1" class="bg-lightgrey wide-60 footer division">
        <div class="container">


            <!-- FOOTER CONTENT -->
            <div class="row">


                <!-- FOOTER INFO -->
                <div class="col-lg-5">
                    <div class="footer-info p-right-45 m-bottom-40">

                        <!-- Footer Logo -->
                        <!-- For Retina Ready displays take a image, with double the amount of pixels that your image will be displayed (e.g 346 x 80 pixels) -->
                        <img :src="logo.url" width="173" height="40" :alt="logo.alt">

                        <!-- Text -->
                        <p class="m-top-20">An orci nullam tempor sapien, eget gravida integer donec ipsum porta justo
                            at odio
                            integer congue orci magna undo auctor gravida velna magna lacus odio ac risus auctor tempus
                            dolor feugiat
                        </p>

                    </div>
                </div>


                <!-- FOOTER LINKS -->
                <div class="col-md-4 col-lg-2">
                    <div class="footer-links m-bottom-40">

                        <!-- Title -->
                        <h5 class="h5-md">Useful Links</h5>

                        <!-- Footer Links -->
                        <ul class="foo-links clearfix">
                            <li><a href="#">How It Works?</a></li>
                            <li><a href="#">Privacy Policy</a></li>
                            <li><a href="#">Terms of Service</a></li>
                            <li><a href="#">Site Map</a></li>
                        </ul>

                    </div>
                </div>
                


                <!-- FOOTER LINKS -->
                <div class="col-md-4 col-lg-2">
                    <div class="footer-links m-bottom-40">

                        <!-- Title -->
                        <h5 class="h5-md">Support</h5>

                        <!-- Footer Links -->
                        <ul class="foo-links clearfix">
                            <li><a href="#">FAQs</a></li>
                            <li><a href="#">Editor Help</a></li>
                            <li><a href="#">Life Chatting</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>

                    </div>
                </div>


                <!-- FOOTER STORE BADGES -->
                <div class="col-md-4 col-lg-3">
                    <div class="footer-stores-badge text-right m-bottom-40">

                        <!-- AppStore -->
                        <a href="#" class="store">
                            <img class="appstore-original" :src="linkimg.appstore" width="160" height="50"
                                alt="appstore-logo" />
                        </a>

                        <!-- Google Play -->
                        <a href="#" class="store">
                            <img class="googleplay-original" :src="linkimg.gplay" width="171" height="50"
                                alt="googleplay-logo" />
                        </a>

                    </div>
                </div> <!-- END FOOTER STORE BADGES -->


            </div> <!-- END FOOTER CONTENT -->


            <!-- BOTTOM FOOTER -->
            <div class="bottom-footer">
                <div class="row">

                    <!-- FOOTER COPYRIGHT -->
                    <div class="col-md-12">
                        <div class="footer-copyright">
                            <p>&copy; {{ dateFunc() }} <span>MobiCom</span>. All Rights Reserved</p>
                        </div>
                    </div>

                </div>
            </div> <!-- END BOTTOM FOOTER -->


        </div> <!-- End container -->
    </footer> <!-- END FOOTER-1 -->
</template>

<style scoped></style>