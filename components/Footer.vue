<template>
    <footer class="footer-area bg-img-cover" :style="{ backgroundImage: `url('/images/photos/bg-footer.jpg')` }">
        <div class="footer-top" data-aos="fade-up" data-aos-duration="1000">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="contact-info-content">
                            <div class="contact-info-item">
                                <div class="icon">
                                    <img class="icon-img" src="/images/icons/c1.png" alt="Icon">
                                </div>
                                <div class="content">
                                    <h4>Call Us.</h4>
                                    <img class="line-icon" src="/images/shape/line-s1.png" alt="Icon">
                                    <a href="tel://0123456789">0123456789</a>
                                    <a href="tel://0123456789">0123456789</a>
                                </div>
                            </div>
                            <div class="contact-info-item">
                                <div class="icon">
                                    <img class="icon-img" src="/images/icons/c2.png" alt="Icon">
                                </div>
                                <div class="content">
                                    <h4>Email.</h4>
                                    <img class="line-icon" src="/images/shape/line-s1.png" alt="Icon">
                                    <a href="mailto://support@gmail.com">support@gmail.com</a>
                                    <a href="mailto://demo@gmail.com">demo@gmail.com</a>
                                </div>
                            </div>
                            <div class="contact-info-item">
                                <div class="icon">
                                    <img class="icon-img" src="/images/icons/c3.png" alt="Icon">
                                </div>
                                <div class="content">
                                    <h4>Location.</h4>
                                    <img class="line-icon" src="/images/shape/line-s1.png" alt="Icon">
                                    <p>92 St., New York, <br>Ny 10013, USA</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container" data-aos="fade-up" data-aos-duration="1000">
            <div class="row">
                <div class="col-md-9 col-lg-4 col-xl-4">
                    <div class="widget-item mt-0">
                        <div class="about-widget">
                            <n-link to="/" class="footer-logo">
                                <img src="/images/logo/logo.png" alt="Logo">
                            </n-link>
                            <p>Lorem Ipsum is simply dummy text of the and typesetting industry. Lorem Ipsum has industry's standard dummy text ever printer took a galley.</p>
                            <div class="widget-newsletter">
                                <form>
                                    <input type="email" class="form-control" placeholder="Enter your email">
                                    <button type="submit" class="btn btn-theme">
                                        Subscribe Now <i class="icon icofont-long-arrow-right"></i>
                                    </button>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-8 col-lg-6 col-xl-6">
                    <div class="widget-item menu-wrap-two-column">
                        <h4 class="widget-title">All Services</h4>
                        <img class="line-shape" src="/images/shape/line-s1.png" alt="shape">
                        <nav class="widget-menu-wrap">
                            <div class="row">
                                <div class="col-md-6">
                                    <ul class="nav-menu nav">
                                        <li><n-link to="/service-details">Business Management</n-link></li>
                                        <li><n-link to="/service-details">Web Development</n-link></li>
                                        <li><n-link to="/service-details">Business Consultation</n-link></li>
                                        <li><n-link to="/service-details">Digital Marketing</n-link></li>
                                        <li><n-link to="/service-details">Brand Identity</n-link></li>
                                        <li><n-link to="/service-details">Insurance & Banking</n-link></li>
                                    </ul>
                                </div>
                                <div class="col-md-6">
                                    <ul class="nav-menu nav">
                                        <li><n-link to="/service-details">Website Optimization</n-link></li>
                                        <li><n-link to="/service-details">Social Media Marketing</n-link></li>
                                        <li><n-link to="/service-details">Link Building Services</n-link></li>
                                        <li><n-link to="/service-details">Pay Per Click Advertising</n-link></li>
                                        <li><n-link to="/service-details">Search Engine Marketing</n-link></li>
                                        <li><n-link to="/service-details">Content Marketing</n-link></li>
                                    </ul>
                                </div>
                            </div>
                        </nav>
                    </div>
                </div>
                <div class="col-md-4 col-lg-2 col-xl-2 lg-pr-0">
                    <div class="widget-item menu-wrap-column">
                        <h4 class="widget-title">Useful Links</h4>
                        <img class="line-shape" src="/images/shape/line-s1.png" alt="Virtuf-HasTech">
                        <nav class="widget-menu-wrap">
                            <ul class="nav-menu nav">
                                <li><n-link to="/">Group Profile</n-link></li>
                                <li><n-link to="/">Vision & Values</n-link></li>
                                <li><n-link to="/">Company History</n-link></li>
                                <li><n-link to="/">Careers</n-link></li>
                                <li><n-link to="/">Winning Awards</n-link></li>
                                <li><n-link to="/">Sustainability</n-link></li>
                            </ul>
                        </nav>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container">
                <div class="footer-bottom-content">
                    <div class="row align-items-center">
                        <div class="col-md-6 order-2 order-md-1">
                            <div class="widget-copyright">
                                <p>© 2021 <span>VIRTUF</span> Made with <i class="icofont-heart"></i> by <a href="#">HasThemes</a></p>
                            </div>
                        </div>
                        <div class="col-md-6 order-1 order-md-2">
                            <div class="widget-social-icons">
                                <a href="#"><i class="icofont-facebook"></i></a>
                                <a href="#"><i class="icofont-skype"></i></a>
                                <a href="#"><i class="icofont-instagram"></i></a>
                                <a href="#"><i class="icofont-twitter"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {

    };
</script>