<template>
  <div class="main">
        <section class="SectionNavber text-center">
        <div class="container">
            <img src="@/assets/img/apple-watch.svg" alt="" />
        <nav class="navbar navbar-expand-lg navbar-light">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item active">
                        <nuxt-link class="nav-link" to="">Design</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" to="">Health</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" to="">Workouts</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" to="">Activity</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" to="">Connect</nuxt-link>
                    </li>
                </ul>
            </div>
        </nav>
        </div>
    </section>
    <section class="change">
        <div class="container">
            <div class="row">
                <div class="col-md-8">
                    <h2>Change
                        <br>
                        starts within.
                    </h2>
                    <p>Apple Watch Series 4. Fundamentally redesigned and re‑engineered to help you be even more active,
                        healthy, and connected.</p>
                    <nuxt-link to="" class="visit">Visit website ></nuxt-link>
                    <nuxt-link to="" class="buy btn btn-primary">Buy</nuxt-link>
                </div>
                <div class="col-md-4 img_watch">
                    <img src="@/assets/img/watch.svg" class="float-right" alt="">
                </div>
            </div>
        </div>
    </section>
    <section class="check">
        <div class="container">
            <h2 class="float-left">Check Also
            </h2>
            <nuxt-link to="" class="float-right">See All ></nuxt-link>
            <div class="clear-fix"></div>
            <div class="row text-center">
                <div class="col-md-6">
                    <img src="@/assets/img/Airpods.svg" class="sell" alt="">
                    <p>AirPods</p>
                    <span>$799.00</span>
                    <nuxt-link to="" class="buy btn btn-primary">Buy</nuxt-link>
                </div>
                <div class="col-md-6">
                    <img src="@/assets/img/Iphone.svg" class="sell" alt="">
                    <p>Iphone XR</p>
                    <span>$199.00</span>
                    <nuxt-link to="" class="buy btn btn-primary">Buy</nuxt-link>
                </div>
                <div class="col-md-6">
                    <img src="@/assets/img/Apple tv.svg" class="sell" alt="">
                    <p>Apple Tv</p>
                    <span>$179.00</span>
                    <nuxt-link to="" class="buy btn btn-primary">Buy</nuxt-link>
                </div>
                <div class="col-md-6">
                    <img src="@/assets/img/Apple card.svg" class="sell" alt="">
                    <p>Apple Card</p>
                    <span>Free</span>
                    <nuxt-link to="" class="buy btn btn-primary mb-3">Apply</nuxt-link>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-md-6 mt-6">
                    <h2>Follow Us.</h2>
                    <p>We are always looking for new projects and collaborations. Feel free to contact us.</p>
                    <nuxt-link to="" class="m">
                        <i class="fab fa-facebook-f"></i>
                    </nuxt-link>
                    <nuxt-link to="" class="m">
                        <i class="fab fa-twitter"></i>
                    </nuxt-link>
                    <nuxt-link to="">
                        <i class="fab fa-instagram"></i>
                    </nuxt-link>
                </div>
                <div class="col-md-6 text-center mt-6">
                    <h2>Contact Us.</h2>
                    <p>Minyat Samanoud Aga</p>
                    <p>+201096710328</p>
                    <nuxt-link to="">ahmedalsolya@gmail.com</nuxt-link>
                </div>
            </div>
        </div>
    </footer>

  </div>
</template>