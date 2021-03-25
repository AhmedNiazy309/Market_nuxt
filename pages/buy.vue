<template>
    <div class="buyPage">
            <section>
        <nav class="navbar navbar-expand-lg navbar-light">
            <nuxt-link class="navbar-brand" to="">Final Cut Pro X</nuxt-link>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                        <nuxt-link class="nav-link" to="">Over View</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" to="">Metion</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" to="">Tech Speces</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link buy btn btn-primary mr-3" to="">Free Trial</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link buy btn btn-primary" to="">Buy</nuxt-link>
                    </li>
                </ul>
            </div>
        </nav>
    </section>
    <section class="header">
        <div class="container text-center">
            <h1 class="text-left">Our most stunning take on post-production.</h1>
            <nav aria-label="breadcrumb">
                <ol class="breadcrumb">
                    <li class="breadcrumb-item"><nuxt-link to="/">Try Final Cut Pro free</nuxt-link></li>
                    <li class="breadcrumb-item active" aria-current="page">Buy Now</li>
                </ol>
            </nav>
            <img class="mt-3" src="@/assets/img/Imac Mockup.svg" alt="">
        </div>
    </section>
    <section class="det">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <div class="detail mt-5">
                        <img src="@/assets/img/Rectangle 2.svg" alt="">
                        <p class="d-inline"> Editing, audio, motion graphics, and delivery.</p>
                        <br>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="detail mt-5">
                        <img src="@/assets/img/Rectangle 2.svg" alt="">
                        <p class="d-inline"> Color grading, HDR support, and ProRes RAW.</p>
                        <br>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="detail mt-5">
                        <img src="@/assets/img/Rectangle 2.svg" alt="">
                        <p class="d-inline">Metal engine coming this fall.</p>
                        <br>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="detail mt-5">
                        <img src="@/assets/img/Rectangle 2.svg" alt="">
                        <p class="d-inline">360° video editing and VR headset playback.</p>
                        <br>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="collectiom_img">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <img src="@/assets/img/8.svg" alt="">
                </div>
                <div class="col-md-4">
                    <img src="@/assets/img/3.2.svg" alt="">
                </div>
                <div class="col-md-4">
                    <img src="@/assets/img/2.svg" alt="">
                </div>
            </div>
        </div>
    </section>
    <footer>
        <div class="container text-center">
        <div class="social text-center">
                <nuxt-link to="">
                    <i class="fab fa-facebook-f"></i>
                </nuxt-link>
                <nuxt-link to="" class="ml-5">
                    <i class="fab fa-twitter"></i>
                </nuxt-link>
                <nuxt-link to="" class="ml-5">
                    <i class="fab fa-instagram"></i>
                </nuxt-link>
            </div>
            <p>All rights reserved. Copyright &copy; 2021 Apple Inc. 1 Infinite MInyat_Samanoud Aga<span style="color: yellow;font-size: 15px;">&#128515;</span></p>
            <p>This email was sent to ahmedalsolya@gmail.com <span style="color: #f00; font-size: 20px;">&#9829;</span> because you indicated that you’d like to stay up to date on the latest features, services, support info and offers for Final Cut Pro. You can unsubscribe from Final Cut Pro emails here</p>
            <p>Privacy Policy | Terms &#38; Conditions | Suppert | Account | Subscribe</p>
        </div>
    </footer>

    </div>
</template>