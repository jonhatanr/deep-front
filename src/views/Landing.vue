<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-2 shape-default shape-skew bg-gradient-warning">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col order-md-2 overflow-hidden">
                        <div class="overflow-hidden transform-perspective-right">
                            <img src="img/brand/menu_show.jpeg" class="img-fluid">
                        </div>
                    </div>
                    <div class="col order-md-1">
                        <div class="row">
                            <div class="col-lg-10">
                                <h1 class="display-3 text-white">
                                    Llevamos la visibilidad de tu restaurante, bar, cafetería a otra dimensión
                                    <!-- <span>completed with examples</span> -->
                                </h1>
                                <p class="lead text-white">No es solo otra aplicación para restaurantes, es la que faltaba ...
                                </p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                                 href="#/about"
                                                 class="mb-2"
                                                 type="neutral"
                                                 icon="ni ni-air-baloon">
                                        Conoce más
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <div class="rounded shadow-lg overflow-hidden transform-perspective-right">
                            <b-carousel id="carousel1"
                                        controls
                                        indicators>
                                <!-- Text slides with image -->
                                <b-carousel-slide img-src="img/brand/automated_order_process.jpeg"></b-carousel-slide>
                                <b-carousel-slide img-src="img/brand/pleople_ordering_food.jpeg"></b-carousel-slide>
                                <b-carousel-slide img-src="img/brand/orders.jpeg"></b-carousel-slide>
                                
                            </b-carousel>
                        </div>
                    </div>

                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <icon name="ni ni-settings-gear-65" class="mb-5" size="lg" type="success" shadow
                                  rounded></icon>
                            <h3>Funcionalidades impresionantes</h3>
                            <p>
                                Ofrecemos una serie de funcionalidades que van más allá de un simple punto de venta.
                            </p>
                            <ul class="list-unstyled mt-4">
                                <li class="py-3">
                                    <div class="align-items-center d-flex">
                                        <badge type="success" class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-1">Agregar tú menú y compartirlo con todo mundo mediante un código QA</h6>
                                    </div>
                                </li>
                                <li class="py-3 ">
                                    <div class="align-items-center d-flex">
                                        <badge type="success"  class="mr-3" icon="ni ni-world"></badge>
                                        <h6 class="mb-1">Punto de venta para cualquier dispositivo, podrás acceder a el desde cualquier parte donde estés</h6>
                                    </div>
                                </li>
                                <li class="py-3">
                                    <div class="align-items-center d-flex">
                                        <badge type="success" class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-1">Aplicación movil para tus clientes. Podrán ordenar, pagar y más!</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="section section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-1 bg-gradient-warning shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container py-0">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div>
                                <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow
                                      rounded></icon>
                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">Interfaz y tecnologías modernas</h4>
                                <span class="text-white">
                                    Te ofrecemos un panel de control intuitivo, agradable a la vista y muy fácil de usar 
                                    con la intención de manejar tus ventas, productos, inventarios y más.
                                </span>
                            </div>
                        </div>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-chart-bar-32" gradient="success" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">Ve como tu negocio crece</h5>
                                    <p>
                                        Mediante un Dashboard moderno, serás capaz de visualizar información de mucha utilidad
                                        la cual te servirá para tomar deciciones en tu negocio.
                                    </p>
                                </div>
                            </div>
                        </card>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="warning" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">Satisface a tus clientes</h5>
                                    <p>
                                        Ofrecemos una applicación móvil para cualquier usuario, mediante la cual podrán observar tus productos,
                                        promociones, horarios...
                                        ordenar y hasta pagar.
                                    </p>
                                    <a href="#" class="text-warning">Conoce más</a>
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section section-lg my-1 section-contact-us">
            <div class="container justify-content-center col-lg-8 text-center">
                <h3 class="display-3 mb-5">Contáctanos</h3>

                <div class="container pl-4">
                    <div class="row justify-content-center">
                        <div class="col-lg-8">
                            <card gradient="secondary" shadow body-classes="p-lg-5">
                                <p class="mt-0">Tu opinión es muy importante para nosotros</p>
                                <base-input class="mt-5"
                                            alternative
                                            placeholder="Nombre"
                                            addon-left-icon="ni ni-user-run">
                                </base-input>
                                <base-input alternative
                                            placeholder="Correo Electrónico"
                                            addon-left-icon="ni ni-email-83">
                                </base-input>
                                <base-input class="mb-4">
                                        <textarea class="form-control form-control-alternative" name="name" rows="4"
                                                cols="80" placeholder="Dinos tu opinión..."></textarea>
                                </base-input>
                                <base-button type="warning" round block size="lg">
                                    Enviar Mensaje
                                </base-button>
                            </card>
                        </div>
                    </div>
                </div>
            </div>

        </section>

    </div>
</template>

<script>
    import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
    import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

    export default {
    name: "home",
    components: {
        BCarousel,
        BCarouselSlide
    }
    };
</script>
