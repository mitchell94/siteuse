<script setup>
let preventClick = (e) => {
    e.preventDefault()
}
</script>

<template>
    <section class="parent-container header-section">
        <div class="container">
            <div class="row">
                <div class="col-auto ms-auto">
                    <img src="../assets/img/unsm.webp" alt="" class="logo" />
                </div>
                <div class="col col-md">
                    <div class="mb-3 unsm-name">UNIVERSIDAD NACIONAL DE SAN MARTÍN</div>
                    <div class="mb-3 fcs-name">FACULTAD DE CIENCIAS DE LA SALUD</div>
                </div>
                <div class="col-auto me-auto">
                    <img src="../assets/img/fcs.webp" alt="" class="logo" />
                </div>
            </div>
        </div>
    </section>

    <section class="img-fondo">
        <video autoplay loop muted playsinline width="100%" @contextmenu="preventClick">
            <source src="../assets/img/bg_animation_50.webm" type="video/webm" />
        </video>
        <div class="use-name">UNIDAD DE SEGUNDA ESPECIALIDAD</div>
    </section>

    <section class="parent-container admision-section">
        <div class="container">
            <div class="row">
                <div class="col d-flex align-items-center justify-content-center">
                    <div class="text-center">
                        <div class="admision-title">ADMISIÓN 2024-I</div>
                        <div class="admision-subtitle">Segunda Especialidad en Obstetricia</div>
                        <div class="admision-registration">
                            <RouterLink to="/admision">VER ADMISIÓN</RouterLink>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="parent-container programas-section">
        <div class="container">
            <div class="row">
                <div class="col section-title">
                    <span>PROGRAMAS DE ESTUDIO</span>
                </div>
            </div>
            <div class="row align-items-stretch section-body">
                <div class="col-md-4">
                    <div class="card h-100 program-card aro-card">
                        <img
                            src="../assets/img/programas/aro.webp"
                            class="card-img-top"
                            alt="..."
                        />
                        <div class="card-body">
                            <p class="card-text text-center">
                                SEGUNDA ESPECIALIDAD EN OBSTETRICIA DE ALTO RIESGO CON MENCIÓN EN
                                CUIDADOS INTENSIVOS MATERNOS
                            </p>
                            <div>
                                <RouterLink to="/cacu" class="btn btn-aro">VER PROGRAMA</RouterLink>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-4 mt-3 mt-md-0">
                    <div class="card h-100 program-card eco-card">
                        <img
                            src="../assets/img/programas/eco.webp"
                            class="card-img-top"
                            alt="..."
                        />
                        <div class="card-body">
                            <p class="card-text text-center">
                                SEGUNDA ESPECIALIDAD EN ECOGRAFÍA OBSTÉTRICA CON MENCIÓN EN
                                MONITOREO FETAL ELECTRÓNICO
                            </p>
                            <div>
                                <RouterLink to="/cacu" class="btn btn-eco">VER PROGRAMA</RouterLink>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-4 mt-3 mt-md-0">
                    <div class="card h-100 program-card cacu-card">
                        <img
                            src="../assets/img/programas/cacu.webp"
                            class="card-img-top"
                            alt="..."
                        />
                        <div class="card-body">
                            <p class="card-text text-center">
                                SEGUNDA ESPECIALIDAD EN SALUD REPRODUCTIVA CON MENCIÓN EN PREVENCIÓN
                                DE CÁNCER DE CUELLO UTERINO Y MAMA
                            </p>
                            <div>
                                <RouterLink to="/cacu" class="btn btn-cacu"
                                    >VER PROGRAMA</RouterLink
                                >
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
@media only screen and (min-width: 1200px) {
    .header-section {
        background-image: linear-gradient(to bottom, #81163390, #81163389) !important;
        position: absolute !important;
        width: 100% !important;
        z-index: 2 !important;
    }
}
</style>
