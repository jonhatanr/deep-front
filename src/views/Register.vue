<template>
    <section class="section section-shaped section-lg my-0">
        <div class="shape shape-style-1 bg-gradient-warning">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container pt-lg-md">
            <div class="row justify-content-center">
                <div class="col-lg-5">
                    <card type="secondary" shadow
                          header-classes="bg-white pb-5"
                          body-classes="px-lg-5 py-lg-5"
                          class="border-0">
                        <template>
                            <div class="text-muted text-center mb-3">
                                <p>Crear cuenta con</p>
                            </div>
                            <div class="btn-wrapper text-center d-flex">
                                <base-button type="neutral">
                                    <img slot="icon" src="img/icons/common/facebook.svg">
                                    Facebook
                                </base-button>

                                <base-button type="neutral">
                                    <img slot="icon" src="img/icons/common/google.svg">
                                    Google
                                </base-button>
                            </div>
                        </template>
                        <template>
                            <div class="text-center text-muted mb-4 my-2">
                                <small>O mediante correo electronico</small>
                            </div>
                            <form role="form">
                                <base-input alternative
                                            class="mb-3"
                                            placeholder="Nombre(s)"
                                            addon-left-icon="ni ni-hat-3">
                                </base-input>
                                <base-input alternative
                                            class="mb-3"
                                            placeholder="Correo Electrónico"
                                            addon-left-icon="ni ni-email-83">
                                </base-input>
                                <base-input alternative
                                            type="password"
                                            placeholder="Contraseña"
                                            addon-left-icon="ni ni-lock-circle-open">
                                </base-input>
                                <div class="text-muted font-italic my-2">
                                    <small>Seguridad de la contraseña:
                                        <span class="text-success font-weight-700">fuerte</span>
                                    </small>
                                </div>
                                <base-checkbox>
                                    <span>Estoy de acuerdo y he leído la
                                        <a href="#">Politica de privacidad</a>
                                    </span>
                                </base-checkbox>
                                <div class="text-center">
                                    <base-button type="warning" class="my-4">Crear cuenta</base-button>
                                </div>
                            </form>
                        </template>
                    </card>
                    <div class="mt-3 text-center">
                        <a href="#/login" class="text-white">
                            <small>¿Ya tienes cuenta?</small>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {};
</script>

<style>
</style>
