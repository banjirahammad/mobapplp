<script setup></script>
<template>
    <!-- BOTTOM QUICK FORM
			============================================= -->
    <div id="quick-form">
        <div class="bottom-form">


            <!-- QUICK FORM HEADER -->
            <div class="bottom-form-header">
                <span class="pe-7s-chat"></span>
                <p>Quick Contact Form</p>
            </div>


            <!-- QUICK FORM -->
            <div class="bottom-form-holder">
                <form name="contactform" class="quick-contact-form">

                    <!-- Contact Form Input -->
                    <div id="bottom-input-name">
                        <input type="text" name="name" class="bottom-form-control bname" placeholder="Your Name*">
                    </div>

                    <div id="bottom-input-email">
                        <input type="text" name="email" class="bottom-form-control bemail" placeholder="Email Address*">
                    </div>

                    <div id="bottom-input-message">
                        <textarea class="bottom-form-control bmessage" name="message" rows="4"
                            placeholder="Your Message ..."></textarea>
                    </div>

                    <!-- Contact Form Button -->
                    <div class="m-top-15 form-btn text-right">
                        <button type="submit" class="btn btn-lightgreen submit">Send</button>
                    </div>

                    <!-- Contact Form Message -->
                    <div class="contact-form-msg"><span class="loading"></span></div>

                </form>
            </div>

        </div>
    </div> <!-- END BOTTOM QUICK FORM -->
</template>

<style scoped></style>