<template>
    <footer class="app-footer gap-1">
        <sign-up-modal />
        <section clas="main-layout ">
            <div class="footer-content">

                <div class="footer-title-container">
                    <img class="web-icon" src="../images/logo.svg" alt="">
                </div>
                <div class="footer-links">
                    <div class="footer-loc items-start gap-1">
                        <img class="footer-icon" src="../images/icon-location.svg" alt="">
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                            labore
                            et dolore magna aliqua</p>
                    </div>
                    <div class="flex flex-col">
                        <div class="flex items-center gap-1 collect">
                            <img class="footer-icon" src="../images/icon-phone.svg" alt="">
                            <span class="txt">+1-543-123-4567</span>
                        </div>
                        <div class="flex items-center gap-1 collect">
                            <img class="footer-icon" src="../images/icon-email.svg" alt="">
                            <span class="txt">example@fylo.com</span>
                        </div>
                    </div>
                    <ul class="clean-list footer-list">
                        <li>About Us</li>
                        <li>Jobs</li>
                        <li>Press</li>
                        <li>Blog</li>
                    </ul>
                    <ul class="clean-list footer-list">
                        <li>Contact Us</li>
                        <li>Terms</li>
                        <li>Privacy</li>
                    </ul>
                    <ul class="clean-list flex gap-1">
                        <li> <img class="brand-icon" src="../images/facebook-brands.svg" alt=""> </li>
                        <li> <img class="brand-icon" src="../images/instagram-brands.svg" alt=""> </li>
                        <li> <img class="brand-icon" src="../images/twitter-brands.svg" alt=""> </li>
                    </ul>

                </div>
            </div>
        </section>
    </footer>
</template>

<script>
import signUpModal from '../components/sign-up-modal.vue'
export default {
    components: {
        signUpModal
    }
}
</script>

