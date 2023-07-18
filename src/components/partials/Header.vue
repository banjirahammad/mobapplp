<script setup>
const logo = {
    url: 'images/logo.png',
    'alt': 'Header Logo'
}
</script>

<template>
    <!-- HEADER
			============================================= -->
    <header id="header" class="header">
        <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-tra">
            <div class="container">


                <!-- LOGO IMAGE -->
                <!-- For Retina Ready displays take a image with double the amount of pixels that your image will be displayed (e.g 260 x 60 pixels) -->
                <a href="#hero-10" class="navbar-brand logo-white"><img :src="logo.url" width="130" height="30"
                        :alt="logo.alt"></a>
                <a href="#hero-10" class="navbar-brand logo-black"><img :src="logo.url" width="130" height="30"
                        :alt="logo.alt"></a>


                <!-- Responsive Menu Button -->
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                    aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>


                <!-- Navigation Menu -->
                <div id="navbarSupportedContent" class="collapse navbar-collapse">
                    <ul class="navbar-nav ml-auto">

                        <li class="nav-item nl-simple"><a class="nav-link" href="#features-2">Features</a></li>
                        <li class="nav-item nl-simple"><a class="nav-link" href="#screens-1">Screens</a></li>
                        <li class="nav-item nl-simple"><a class="nav-link" href="#team-1">Our Team</a></li>
                        <li class="nav-item nl-simple"><a class="nav-link" href="#reviews-2">Reviews</a></li>
                        <li class="nav-item nl-simple"><a class="nav-link" href="#faqs-1">FAQs</a></li>

                        <!-- AppStore Badge -->
                        <li class="nav-item">
                            <a href="#" class="header-store">
                                <img class="appstore-button" src="/src/assets/images/store_badges/header-appstore.png"
                                    width="141" height="44" alt="appstore-logo">
                            </a>
                        </li>

                    </ul>
                </div> <!-- End Navigation Menu -->


            </div> <!-- End container -->
        </nav> <!-- End navbar  -->
    </header> <!-- END HEADER -->
</template>

<style scoped></style>