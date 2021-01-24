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
                                <p>Regístrate con</p>
                            </div>
                            <div class="btn-wrapper text-center">
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
                            <div class="text-center text-muted mb-4 my-4">
                                <small>O con tu correo electronico</small>
                            </div>
                            <form role="form">
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
                                <base-checkbox>
                                    Recordarme
                                </base-checkbox>
                                <div class="text-center">
                                    <base-button type="warning" class="my-4">Acceder</base-button>
                                </div>
                            </form>
                        </template>
                    </card>
                    <div class="row mt-3">
                        <div class="col-6">
                            <a href="#" class="text-white">
                                <small>¿Olvidaste la contraseña?</small>
                            </a>
                        </div>
                        <div class="col-6 text-right">
                            <a href="#/register" class="text-white">
                                <small>¡Crea tu cuenta!</small>
                            </a>
                        </div>
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
