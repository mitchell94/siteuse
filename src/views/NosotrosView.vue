<script setup>
import { useSeoMeta } from '@unhead/vue'

useSeoMeta({
    title: 'Nosotros | Segunda Especialidad - FCS',
    description:
        '¿Quieres conocer la Unidad de Segunda Especialidad?, conocer nuestra presentación, nuestra misión y visión, así como nuestras autoridades y demás.',
    ogTitle: 'Nosotros | Segunda Especialidad - FCS',
    ogDescription:
        '¿Quieres conocer la Unidad de Segunda Especialidad?, conoce quienes somos y danos tu confianza.'
})
</script>

<template>
    <section class="parent-container header-section">
        <div class="container">
            <div class="row">
                <div class="col-auto ms-auto">
                    <img
                        src="../assets/img/unsm.webp"
                        alt="Logo de la Universidad Nacional de San Martín"
                        class="logo"
                    />
                </div>
                <div class="col col-md">
                    <div class="mb-3 unsm-name">UNIVERSIDAD NACIONAL DE SAN MARTÍN</div>
                    <div class="mb-3 fcs-name">FACULTAD DE CIENCIAS DE LA SALUD</div>
                </div>
                <div class="col-auto me-auto">
                    <img
                        src="../assets/img/fcs.webp"
                        alt="Logo de la Facultad de Ciencias de la Salud"
                        class="logo"
                    />
                </div>
            </div>
        </div>
    </section>

    <section class="parent-container presentacion-section">
        <div class="container">
            <div class="row">
                <div class="col section-title">
                    <span>PRESENTACIÓN</span>
                </div>
            </div>
            <div class="row">
                <div class="col" style="text-align: justify">
                    La Unidad de Segunda Especialidad de la Facultad de Ciencias de la Salud de la
                    Universidad Nacional de San Martín - Tarapoto, prosiguiendo con su labor
                    orientada a la formación de profesionales altamente especializados en su carrera
                    asi como en el campo de la investigación mediante el estudio multidisciplinario,
                    busca incesantemente seguir contribuyendo en dar solución a múltiples problemas
                    dentro del ámbito local, regional, nacional e internacional.
                </div>
            </div>
        </div>
    </section>

    <section class="parent-container mision-vision-section">
        <div class="container">
            <div class="row gx-md-5">
                <div class="col-md-6">
                    <div class="row">
                        <div class="col section-title"><span>MISIÓN</span></div>
                    </div>
                    <div class="row">
                        <div class="col" style="text-align: justify">
                            “Formamos profesionales de Obstetricia con enfoque integral, calidad
                            educativa y competencias sanitarias pertinentes, con énfasis en la Salud
                            Sexual y Reproductiva en los diferentes niveles resolutivos,
                            desarrollando bienestar en la mujer, familia y comunidad”.
                        </div>
                    </div>
                </div>
                <div class="col-md-6 mt-3 mt-md-0">
                    <div class="row">
                        <div class="col section-title"><span>VISIÓN</span></div>
                    </div>
                    <div class="row">
                        <div class="col" style="text-align: justify">
                            Al 2024, el Programa de Estudios de Obstetricia de la Facultad de
                            Ciencias de la Salud de la UNSM, sostiene la calidad educativa en base a
                            la mejora continua de sus procesos.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="parent-container autoridades-section">
        <div class="container">
            <div class="row">
                <div class="col section-title">
                    <span>AUTORIDADES</span>
                </div>
            </div>
            <div class="row align-items-stretch section-body">
                <div class="col-md-4">
                    <div class="card h-100 border-0">
                        <img
                            src="../assets/img/autoridades/rector.webp"
                            class="card-img-top"
                            alt="Fotografía del Rector"
                        />
                        <div class="card-body autoridad">
                            <div>Dr. Aquilino Mesías Garcia Bautista</div>
                            <div>RECTOR</div>
                        </div>
                    </div>
                </div>

                <div class="col-md-4 mt-3 mt-md-0">
                    <div class="card h-100 border-0">
                        <img
                            src="../assets/img/autoridades/decana.webp"
                            class="card-img-top"
                            alt="Fotografía del Decano"
                        />
                        <div class="card-body autoridad">
                            <div>Obsta. Dra. Evangelina Ampuero Fernandez</div>
                            <div>DECANA</div>
                        </div>
                    </div>
                </div>

                <div class="col-md-4 mt-3 mt-md-0">
                    <div class="card h-100 border-0">
                        <img
                            src="../assets/img/autoridades/coordinadora.webp"
                            class="card-img-top"
                            alt="Fotografía del Coordinador"
                        />
                        <div class="card-body autoridad">
                            <div>Obsta. Dra. Rosa Rios Lopez</div>
                            <div>COORDINADORA</div>
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
        background-image: linear-gradient(to bottom, #811633e9, #811632) !important;
        position: initial !important;
    }
}
</style>
