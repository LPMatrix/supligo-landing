<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div id="wrapper">
    <Header></Header>
      <section id="slider" class="slider-element slider-parallax swiper_wrapper min-vh-75" data-loop="true">

      <div class="swiper-container swiper-parent">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <div class="container">
              <div class="slider-caption">
                <div>
                  <h2>Welcome to Supligo</h2>
                  <p class="d-none d-sm-block">At Supligo, we believe in the extraordinary potential of solar energy to transform the way we power our lives. As a leading solar company, we are dedicated to providing innovative, sustainable, and cost-effective solar solutions for homeowners and businesses alike.</p>
                </div>
              </div>
            </div>
            <div class="swiper-slide-bg" style="background-image: url('images/slider/2.jpg'); background-position: center top;"></div>
          </div>
          <div class="swiper-slide">
            <div class="container">
              <div class="slider-caption slider-caption-right">
                <div>
                  <h2>Welcome to Supligo</h2>
                  <p class="d-none d-sm-block">With the ever-increasing demand for clean and renewable energy, Supligo is at the forefront of the solar revolution. Our team of experienced professionals is passionate about helping you take advantage of the abundant power of the sun to reduce your carbon footprint and achieve energy independence.</p>
                </div>
              </div>
            </div>
            <div class="video-wrap no-placeholder">
              <video id="slide-video" poster="images/videos/1.jpg" preload="auto" loop autoplay muted playsinline>
                <source src='images/videos/1.webm' type='video/webm'>
                <source src='images/videos/1.mp4' type='video/mp4'>
              </video>
              <div class="video-overlay" style="background-color: rgba(0,0,0,0.1);"></div>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="container">
              <div class="slider-caption">
                <div>
                  <h2>Explore the Power of Solar with Supligo</h2>
                  <p class="d-none d-sm-block">Whether you're a homeowner looking to reduce your electricity bills or a business aiming to increase your sustainability efforts, Supligo is here to guide you on your solar journey. Together, let's harness the power of the sun and pave the way for a brighter and cleaner future.</p>
                </div>
              </div>
            </div>
            <div class="swiper-slide-bg" style="background-image: url('images/slider/1.jpg'); background-position: center bottom;"></div>
          </div>
        </div>
        <div class="slider-arrow-left"><i class="uil uil-angle-left-b"></i></div>
        <div class="slider-arrow-right"><i class="uil uil-angle-right-b"></i></div>
      </div>

    </section>

    <!-- Content
    ============================================= -->
    <section id="content">
      <div class="content-wrap">

        <div class="promo promo-light promo-full promo-uppercase p-5 mb-6 header-stick">
          <div class="container">
            <div class="row align-items-center">
              <div class="col-12 col-lg">
                <h3 style="letter-spacing: 2px;">Start Your Journey to a Sustainable Power Supply with Us</h3>
                <span>Harness the Power of the Sun for a Brighter Future</span>
              </div>
              <div class="col-12 col-lg-auto mt-4 mt-lg-0">
                <a href="contact" class="button button-large button-circle button-black m-0">Contact Us</a>
              </div>
            </div>
          </div>
        </div>

        <div class="container">

          <div class="row justify-content-center col-mb-50">
            <div class="col-sm-6 col-lg-4">
              <div class="feature-box media-box">
                <div class="fbox-media">
                  <img class="rounded" src="images/services/1.jpg" alt="Why choose Us?">
                </div>
                <div class="fbox-content px-0">
                  <h3>Skilled Professionals.<span class="subtitle">Your Property in Good Hands.</span></h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi rem, facilis nobis voluptatum est voluptatem accusamus molestiae eaque perspiciatis mollitia.</p>
                </div>
              </div>
            </div>

            <div class="col-sm-6 col-lg-4">
              <div class="feature-box media-box">
                <div class="fbox-media">
                  <img class="rounded" src="images/services/1.jpg" alt="Effective Planning">
                </div>
                <div class="fbox-content px-0">
                  <h3>Effective Planning.<span class="subtitle">Construction Process Organized.</span></h3>
                  <p>Porro repellat vero sapiente amet vitae quibusdam necessitatibus consectetur, labore totam. Accusamus perspiciatis asperiores labore esse.</p>
                </div>
              </div>
            </div>

            <div class="col-sm-6 col-lg-4">
              <div class="feature-box media-box">
                <div class="fbox-media">
                  <img class="rounded" src="images/services/2.jpg" alt="Why choose Us?">
                </div>
                <div class="fbox-content px-0">
                  <h3>Risk Management.<span class="subtitle">We have got you Covered.</span></h3>
                  <p>Quos, non, esse eligendi ab accusantium voluptatem. Maxime eligendi beatae, atque tempora ullam. Vitae delectus quia, consequuntur rerum quo.</p>
                </div>
              </div>
            </div>
          </div>

        </div>

        <div class="section parallax dark" style="padding: 120px 0;">
          <img src="images/slider/1.jpg" class="parallax-bg">

          <div class="fslider" data-arrows="false" style="z-index: 2;">
            <div class="owl-carousel carousel-widget text-center mw-xs mx-auto dark" data-items="1" data-autoplay="5000" data-nav="false">
              <div class="row">
                <div class="col-12">
                  <img class="rounded-circle mx-auto w-auto mb-4" src="images/testimonials/1.jpg" width="64" height="64" alt="Customer Testimonails">
                  <h3 class="mb-4 lh-base fw-normal font-secondary">Seamlessly Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia rerum porro est delectus ad in vitae neque nostrum nesciunt.</h3>
                </div>
                <div class="d-flex align-items-center justify-content-center">
                  <div>
                    <h4 class="h6 mb-0 fw-medium">Alex Coman</h4>
                    <small class="text-white-50">Apple Inc.</small>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12">
                  <img class="rounded-circle mx-auto w-auto mb-4" src="images/testimonials/2.jpg" width="64" height="64" alt="Customer Testimonails">
                  <h3 class="mb-4 lh-base fw-normal font-secondary">Seamlessly conceptualize multimedia based web services for optimal human capital. Collaboratively evisculate e-business value.</h3>
                </div>
                <div class="d-flex align-items-center justify-content-center">
                  <div>
                    <h4 class="h6 mb-0 fw-medium">John Coman</h4>
                    <small class="text-white-50">Apple Inc.</small>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12">
                  <img class="rounded-circle mx-auto w-auto mb-4" src="images/testimonials/3.jpg" width="64" height="64" alt="Customer Testimonails">
                  <h3 class="mb-4 lh-base fw-normal font-secondary">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Molestias facilis ea voluptatem cum.</h3>
                </div>
                <div class="d-flex align-items-center justify-content-center">
                  <div>
                    <h4 class="h6 mb-0 fw-medium">Ricky Coman</h4>
                    <small class="text-white-50">Apple Inc.</small>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="video-wrap" style="z-index: 1;">
            <div class="video-overlay" style="background: rgba(241,128,82,0.9);"></div>
          </div>

        </div>

        <div class="container">

          <div class="row align-items-stretch col-mb-50">
            <div class="col-lg-4 col-md-6">
              <div class="feature-box fbox-plain">
                <div class="fbox-icon">
                  <a href="#"><img src="images/icons/building.png" alt="Concrete Developments"></a>
                </div>
                <div class="fbox-content">
                  <h3>Expertise and Excellence</h3>
                  <p>With years of industry experience, our knowledgeable team is well-versed in the latest solar technologies, ensuring that you receive the most efficient and reliable solar solutions tailored to your specific needs.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-6">
              <div class="feature-box fbox-plain">
                <div class="fbox-icon">
                  <a href="#"><img src="images/icons/bank.png" alt="Finance Assistance"></a>
                </div>
                <div class="fbox-content">
                  <h3>High-Quality Products</h3>
                  <p>We partner with reputable manufacturers to provide top-of-the-line solar panels, inverters, and other components. Our commitment to quality ensures that your solar system operates optimally for decades, delivering maximum performance and durability.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-6">
              <div class="feature-box fbox-plain">
                <div class="fbox-icon">
                  <a href="#"><img src="images/icons/drawer.png" alt="Interiorly Designed"></a>
                </div>
                <div class="fbox-content">
                  <h3>Customized Solutions</h3>
                  <p>Every customer is unique, and we understand that one size does not fit all. Our experts work closely with you to design and install customized solar systems that seamlessly integrate with your property, maximizing energy generation and cost savings.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-6">
              <div class="feature-box fbox-plain">
                <div class="fbox-icon">
                  <a href="#"><img src="images/icons/paper-money.png" alt="Cost Effective Solutions"></a>
                </div>
                <div class="fbox-content">
                  <h3>Financial Benefits</h3>
                  <p>Investing in solar power not only helps the environment but also offers significant financial advantages. Supligo assists you in navigating available incentives, tax credits, and financing options, making solar energy an affordable and smart investment.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-6">
              <div class="feature-box fbox-plain">
                <div class="fbox-icon">
                  <a href="#"><img src="images/icons/traffic-cone.png" alt="Smart Builders"></a>
                </div>
                <div class="fbox-content">
                  <h3>Ongoing Support</h3>
                  <p>Our relationship doesn't end after the installation. Supligo provides comprehensive post-installation support, including system monitoring, maintenance, and troubleshooting, ensuring your solar investment continues to perform optimally year after year.</p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-6">
              <div class="feature-box fbox-plain">
                <div class="fbox-icon">
                  <a href="#"><img src="images/icons/paint-brush.png" alt="Quality Infrastructure"></a>
                </div>
                <div class="fbox-content">
                  <h3>Commitment to Sustainability</h3>
                  <p>We are committed to making a positive impact on the environment by promoting clean energy alternatives. By choosing Supligo, you contribute to a greener and more sustainable future for generations to come.</p>
                </div>
              </div>
            </div>
          </div>

        </div>

        <div class="section mb-0">
          <h2 class="text-center mb-0 ls-1">Some of Our Esteemed Projects:</h2>
        </div>

        <div id="portfolio" class="portfolio row grid-container g-0">

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-media pf-icons">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/1.jpg" alt="The Atmosphere">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3><a href="#">The Atmosphere</a></h3>
                <span>Chicago, USA</span>
              </div>
            </div>
          </article>

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-illustrations">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/2.jpg" alt="Wavelength Structure">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3>Wavelength Structure</h3>
                <span>Madrid, Spain</span>
              </div>
            </div>
          </article>

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-graphics pf-uielements">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/3.jpg" alt="Greenhouse Garden">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3>Greenhouse Garden</h3>
                <span>Bali, Indonesia</span>
              </div>
            </div>
          </article>

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-icons pf-illustrations">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/4.jpg" alt="Industrial Hub">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3>Industrial Hub</h3>
                <span>Beijing, China</span>
              </div>
            </div>
          </article>

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-uielements pf-media">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/5.jpg" alt="Corporate Headquarters">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3>Corporate Headquarters</h3>
                <span>California, USA</span>
              </div>
            </div>
          </article>

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-graphics pf-illustrations">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/6.jpg" alt="Space Station">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3>Space Station</h3>
                <span>Moscow, Russia</span>
              </div>
            </div>
          </article>

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-uielements pf-icons">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/7.jpg" alt="Bent Architecture">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3>Bent Architecture</h3>
                <span>Melbourne, Australia</span>
              </div>
            </div>
          </article>

          <article class="portfolio-item col-12 col-sm-6 col-md-4 col-lg-3 pf-graphics">
            <div class="grid-inner">
              <div class="portfolio-image">
                <img src="images/projects/8.jpg" alt="Lakeview Center">
                <div class="bg-overlay">
                  <div class="bg-overlay-content dark" data-hover-animate="fadeIn">
                    <a href="#" class="overlay-trigger-icon bg-light text-dark" data-hover-animate="zoomIn" data-hover-animate-out="zoomOut" data-hover-speed="350"><i class="uil uil-ellipsis-h"></i></a>
                  </div>
                  <div class="bg-overlay-bg dark" data-hover-animate="fadeIn"></div>
                </div>
              </div>
              <div class="portfolio-desc">
                <h3>Lakeview Center</h3>
                <span>Auckland, New Zealand</span>
              </div>
            </div>
          </article>

        </div>

        <a href="contact" class="button button-3d border-bottom-0 button-full text-center text-end mb-6 fw-light font-primary" style="font-size: 26px;">
          <div class="container">
            Start Your Journey to a Sustainable Power Supply with Us <strong>Enquire Here</strong> <i class="uil uil-angle-right-b" style="top:3px;"></i>
          </div>
        </a>


        <div class="line mt-4"></div>

        <div class="section bg-transparent mt-0 p-0 footer-stick">
          <div class="container">

            <div class="row">
              <div class="col-lg-7">
                <img src="images/services/bottom-trust.jpg" alt="Bottom Trust">
              </div>
              <div class="col-lg-5 mt-4">
                <div class="heading-block border-bottom-0">
                  <h2>You're in Good Hands.</h2>
                  <span class="ls-1">Five Points that define Our Reliability.</span>
                </div>

                <ul class="iconlist iconlist-large iconlist-color">
                  <li><i class="fa-solid fa-check"></i> Experience</li>
                  <li><i class="fa-solid fa-check"></i> Quality Assurance</li>
                  <li><i class="fa-solid fa-check"></i> Customer Satisfaction</li>
                  <li><i class="fa-solid fa-check"></i> Proven Track Record</li>
                  <li><i class="fa-solid fa-check"></i> Ongoing Support</li>
                </ul>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section><!-- #content end -->
    <Footer></Footer>
  </div>
</template>