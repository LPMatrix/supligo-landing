<template>
    <!-- Top Bar
    ============================================= -->
    <div id="top-bar">
      <div class="container">

        <div class="row justify-content-between">
          <div class="col-12 col-md-auto">

            <!-- Top Social
            ============================================= -->
            <ul id="top-social">
              <li><a href="#" class="h-bg-facebook"><span class="ts-icon"><i class="fa-brands fa-facebook-f"></i></span><span class="ts-text">Facebook</span></a></li>
              <li><a href="#" class="h-bg-twitter"><span class="ts-icon"><i class="fa-brands fa-twitter"></i></span><span class="ts-text">Twitter</span></a></li>
              <li><a href="#" class="h-bg-instagram"><span class="ts-icon"><i class="fa-brands fa-instagram"></i></span><span class="ts-text">Instagram</span></a></li>
            </ul><!-- #top-social end -->

          </div>

          <div class="col-12 col-md-auto">

            <!-- Top Links
            ============================================= -->
            <div class="top-links">
              <ul class="top-links-container">
                <li class="top-links-item"><a href="faqs">FAQs</a></li>
                <li class="top-links-item"><a href="contact">Contact</a></li>
              </ul>
            </div><!-- .top-links end -->

          </div>
        </div>

      </div>
    </div><!-- #top-bar end -->

    <!-- Header
    ============================================= -->
    <header id="header" class="header-size-sm" data-sticky-shrink="false">
      <div class="container">
        <div class="header-row">

          <!-- Logo
          ============================================= -->
          <div id="logo" class="ms-auto ms-lg-0 me-lg-auto">
            <a href="demo-construction.html">
              <img class="logo-default" srcset="images/logo.png, images/logo@2x.png 2x" src="images/logo@2x.png" alt="Canvas Logo">
            </a>
          </div><!-- #logo end -->

          <div class="header-misc d-none d-lg-flex">

            <ul class="header-extras">
              <li>
                <i class="i-plain bi-telephone m-0"></i>
                <div class="he-text">
                  Call Us
                  <span>+234 818 670 1509</span>
                </div>
              </li>
              <li>
                <i class="i-plain bi-envelope m-0"></i>
                <div class="he-text">
                  Email Us
                  <span>hello@supligo.com</span>
                </div>
              </li>
              <li>
                <i class="i-plain bi-clock m-0"></i>
                <div class="he-text">
                  We'are Open
                  <span>Mon - Sat, 10AM to 6PM</span>
                </div>
              </li>
            </ul>

          </div>

        </div>
      </div>

      <div id="header-wrap">
        <div class="container">
          <div class="header-row justify-content-between flex-row-reverse flex-lg-row justify-content-lg-center">

            <!-- Primary Navigation
            ============================================= -->
            <nav class="primary-menu with-arrows">

              <ul class="menu-container">
                <li class="menu-item current"><a class="menu-link" href="home"><div>Home</div></a></li>
                <li class="menu-item"><a class="menu-link" href="about"><div>About Us</div></a></li>
                <li class="menu-item"><a class="menu-link" href="projects"><div>Projects</div></a></li>
                <li class="menu-item"><a class="menu-link" href="contact"><div>Contact</div></a></li>
              </ul>

            </nav><!-- #primary-menu end -->

            <form class="top-search-form" action="search.html" method="get">
              <input type="text" name="q" class="form-control" value="" placeholder="Type &amp; Hit Enter.." autocomplete="off">
            </form>

          </div>
        </div>
      </div>
      <div class="header-wrap-clone"></div>
    </header><!-- #header end -->
</template>