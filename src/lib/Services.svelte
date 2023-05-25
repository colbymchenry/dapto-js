<script>
    import FacebookIcon from "./FacebookIcon.svelte";
    import FilmIcon from "./FilmIcon.svelte";
    import MailIcon from "./MailIcon.svelte";
    import TrendingUpIcon from "./TrendingUpIcon.svelte";
    import WebDesignIcon from "./WebDesignIcon.svelte";
</script>

<!-- section start -->
<section class="layout-pt-xl layout-pb-lg">
    <!-- container start -->
    <div class="container">
        <!-- row start -->
        <div class="row">
            <div class="col-xl-9 col-md-12">
                <div class="sectionHeading -sm">
                    <p class="sectionHeading__subtitle -light">services</p>
                    <h2 class="sectionHeading__title fw-600 text-white">
                        We're <span style="text-decoration: line-through">good</span> best at:
                    </h2>
                </div>
            </div>
        </div>
        <!-- row end -->

        <!-- row start -->
        <div data-anim-wrap class="row x-gap-48 y-gap-60 layout-pt-md">
            <div class="col-lg-4 col-sm-6">
                <div data-anim-child="slide-up delay-4" class="serviceCard -type-2">
                    <div class="serviceCard__content text-center">
                        <div class="d-flex align-items-center justify-content-center">
                            <div class="px-20 py-20 bg-dark-1 border-light rounded-full">
                                <div class="header__logo__dark js-lazy size-sm str-width-md text-accent">
                                    <FacebookIcon />
                                </div>
                            </div>
                        </div>

                        <h3 class="serviceCard__title text-accent text-2xl fw-500 mt-40 md:mt-24">Facebook Ads</h3>
                    </div>
                </div>
            </div>

            <div class="col-lg-4 col-sm-6">
                <div data-anim-child="slide-up delay-5" class="serviceCard -type-2">
                    <div class="serviceCard__content text-center">
                        <div class="d-flex align-items-center justify-content-center">
                            <div class="px-20 py-20 bg-dark-1 border-light rounded-full">
                                <img class="header__logo__dark js-lazy size-sm str-width-md text-accent" data-src="/img/icons/snapchat.svg" alt="Logo" />
                            </div>
                        </div>

                        <h3 class="serviceCard__title text-accent text-2xl fw-500 mt-40 md:mt-24">Snapchat Ads</h3>
                    </div>
                </div>
            </div>

            <div class="col-lg-4 col-sm-6">
                <div data-anim-child="slide-up delay-6" class="serviceCard -type-2">
                    <div class="serviceCard__content text-center">
                        <div class="d-flex align-items-center justify-content-center">
                            <div class="px-20 py-20 bg-dark-1 border-light rounded-full">
                                <div class="header__logo__dark js-lazy size-sm str-width-md text-accent">
                                    <TrendingUpIcon />
                                </div>
                            </div>
                        </div>

                        <h3 class="serviceCard__title text-accent text-2xl fw-500 mt-40 md:mt-24">Conversion Rate</h3>
                    </div>
                </div>
            </div>
        </div>
        <!-- row end -->

        <!-- row start -->
        <div data-anim-wrap class="row x-gap-48 y-gap-60 layout-pt-md">
            <div class="col-lg-4 col-sm-6">
                <div data-anim-child="slide-up delay-4" class="serviceCard -type-2">
                    <div class="serviceCard__content text-center">
                        <div class="d-flex align-items-center justify-content-center">
                            <div class="px-20 py-20 bg-dark-1 border-light rounded-full">
                                <div class="header__logo__dark js-lazy size-sm str-width-md text-accent">
                                    <MailIcon />
                                </div>
                            </div>
                        </div>

                        <h3 class="serviceCard__title text-accent text-2xl fw-500 mt-40 md:mt-24">Email & SMS</h3>
                    </div>
                </div>
            </div>

            <div class="col-lg-4 col-sm-6">
                <div data-anim-child="slide-up delay-5" class="serviceCard -type-2">
                    <div class="serviceCard__content text-center">
                        <div class="d-flex align-items-center justify-content-center">
                            <div class="px-20 py-20 bg-dark-1 border-light rounded-full">
                                <div class="header__logo__dark js-lazy size-sm str-width-md text-accent">
                                    <WebDesignIcon />
                                </div>
                            </div>
                        </div>

                        <h3 class="serviceCard__title text-accent text-2xl fw-500 mt-40 md:mt-24">Web Design</h3>
                    </div>
                </div>
            </div>

            <div class="col-lg-4 col-sm-6">
                <div data-anim-child="slide-up delay-6" class="serviceCard -type-2">
                    <div class="serviceCard__content text-center">
                        <div class="d-flex align-items-center justify-content-center">
                            <div class="px-20 py-20 bg-dark-1 border-light rounded-full">
                                <div class="header__logo__dark js-lazy size-sm str-width-md text-accent">
                                    <FilmIcon />
                                </div>
                            </div>
                        </div>

                        <h3 class="serviceCard__title text-accent text-2xl fw-500 mt-40 md:mt-24">Video</h3>
                    </div>
                </div>
            </div>
        </div>
        <!-- row end -->

        <!-- row start -->
        <div data-anim-wrap class="row x-gap-48 y-gap-60 layout-pt-md text-center justify-content-center">
            <div class="masthead__button mt-40 sm:mt-32 js-button">
                <a
                    href="https://form.typeform.com/to/AyVsICIS?typeform-medium=embed-snippet"
                    data-size="100"
                    data-mode="popup"
                    target="_blank"
                    class="typeform-share button -md -outline-white text-white"
                >
                    Let's Work
                </a>
            </div>
        </div>
    </div>
    <!-- container end -->
</section>
<!-- section end -->
