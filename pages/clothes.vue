<template>
    <div class="clothesPage">
            <div class="container">
        <div class="structure">
            <header>
                <div class="container">
                    <div class="float-left">
                        <div class="float-left">
                            <img src="@/assets/img/Ellipse.svg" alt="">
                        </div>
                        <div class="float-right">
                            <div class="text d-inline">
                                <h2 class="name d-inline">Jane Smith</h2>
                                <br>
                                <span class="co">Co-Founder</span>
                            </div>
                        </div>
                    </div>
                    <div class="float-right">
                        <img src="@/assets/img/Logo.svg" alt="">
                    </div>
                </div>
            </header>
            <div class="clear-fix"></div>
            <div class="d-flex justifyContent-center">
                <img src="@/assets/img/sh.svg" class="text-center w-100" alt="">
            </div>
            <div class="save">
                <div class="container">
                    <h2 class="h1">Save €10 on your next order</h2>
                    <p>
                        Hello Herbert Jones. Welcome to the PRFCT FIT Store! I’m Jane Stith, Co-Founder of prfctfit.com.
                        We’re happy to have you here :) We’ve prepared a little gift for you — €10 off your next order.
                        <br>
                        <br>
                        And if that isn’t enough, we’ll be keeping you updated with the latest releases, fashion trends,
                        special offers and more.
                    </p>
                </div>
            </div>
            <div class="code mt-4 text-center">
                <h2 class="h1">Your €10 Voucher Code*:</h2>
                <div class="m-auto">
                    <label for="code">MJ2-S23-Q77</label>
                    <nuxt-link to="" class="btn btn-primary">use it</nuxt-link>
                    <p>*Full terms and conditions can be found here</p>
                </div>
            </div>
            <div class="discover">
                <div class="container">
                    <div class="float-left">
                        <h2 class="h1">You might like</h2>
                    </div>
                    <div class="float-right">
                        <nuxt-link to="">Discover more ></nuxt-link>
                    </div>
                    <div class="clear-fix"></div>
                    <div class="row text-center">
                        <div class="col-md-4">
                            <img src="@/assets/img/Rectangle 5.svg" alt="">
                            <h6>New Balance
                                <br>
                                MSX90RPB (Grey)
                            </h6>
                            <span class="price">€135.00</span>
                        </div>
                        <div class="col-md-4">
                            <img src="@/assets/img/c.svg" alt="">
                            <h6>Stussy Stripe Crew 
                                <br>
                                (White - Orange)
                            </h6>
                            <span class="price">€20.00</span>
                        </div>
                        <div class="col-md-4">
                            <img src="@/assets/img/p.svg" alt="">
                            <h6>Fjallqraven Kanken No.2
                                <br>
                                Total (Black)
                            </h6>
                            <span class="price">€175.00</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <footer class="text-center">
            <p class="d-block">
                Partnership with the famous brands:
            </p>
                <img src="@/assets/img/Partner logos.svg" class="mt-3 mb-3" alt="">
                <div class="follow mb-4">
                    <nuxt-link to="" class="d-inline mt-3 text-left mr-5">Follow @prfctfit on twitter →</nuxt-link>
                    <p class="text-right d-inline">Unsubscribe</p>
                </div>
        </footer>
    </div>

    </div>
</template>