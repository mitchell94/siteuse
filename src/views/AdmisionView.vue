<script setup>
import { useSeoMeta } from '@unhead/vue'

useSeoMeta({
    title: 'Admisión | Segunda Especialidad - FCS',
    description:
        '¿Quieres empezar tus estudios de Segunda Especialidad en Obstetricia?, conoce los costos, requisitos y horario de estudios.',
    ogTitle: 'Admisión | Segunda Especialidad - FCS',
    ogDescription:
        '¿Quieres empezar tus estudios de Segunda Especialidad en Obstetricia?, aquí te mostramos los requisitos.'
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

    <section class="parent-container bg-white admision-section">
        <div class="container">
            <div class="row">
                <div class="col d-flex align-items-center justify-content-center">
                    <div class="text-center">
                        <div class="admision-title">ADMISIÓN 2024-I</div>
                        <div class="admision-subtitle">Segunda Especialidad en Obstetricia</div>
                    </div>
                </div>
            </div>
            <div class="row gx-md-5">
                <div class="col-md-6 mt-3 mt-md-5">
                    <div class="row">
                        <div class="col-12 admision-horario">
                            <div class="article-title">HORARIO DE CLASES (Semipresencial)</div>
                            <table class="table table-sm table-bordered">
                                <thead>
                                    <tr>
                                        <th>DÍA</th>
                                        <th>HORARIO</th>
                                        <th>HORAS</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>SÁBADO</td>
                                        <td>3:00 p.m. a 8:00 p.m.</td>
                                        <td>5</td>
                                    </tr>
                                    <tr>
                                        <td>DOMINGO</td>
                                        <td>8:00 a.m. a 1:00 p.m.</td>
                                        <td>5</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                        <div class="col-12 mt-3 mt-md-4 admision-horario">
                            <div class="article-title">CRONOGRAMA DE ADMISIÓN</div>
                            <table class="table table-sm table-bordered">
                                <tbody>
                                    <tr>
                                        <td>Inscripción y presentación de documentos</td>
                                        <td>Hasta el 20 de marzo 2024 (Hora límite 2:45 pm)</td>
                                    </tr>
                                    <tr>
                                        <td>Evaluación de expedientes</td>
                                        <td>21 y 22 de marzo 2024</td>
                                    </tr>
                                    <tr>
                                        <td>Examen de admisión</td>
                                        <td>23 de marzo 2024 (9 a 11 am)</td>
                                    </tr>
                                    <tr>
                                        <td>Entrevista personal</td>
                                        <td>23 de marzo 2024 (2 a 5 pm)</td>
                                    </tr>
                                    <tr>
                                        <td>Publicación de resultados</td>
                                        <td>24 de marzo 2024 (4 pm)</td>
                                    </tr>
                                    <tr>
                                        <td>Acreditación de ingresantes (virtual)</td>
                                        <td>25 y 26 de marzo 2024</td>
                                    </tr>
                                    <tr>
                                        <td>Inicio de clases, semestre I</td>
                                        <td>20 de abril 2024</td>
                                    </tr>
                                    <tr>
                                        <td>Fin de clases, semestre I</td>
                                        <td>27 de octubre 2024</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                        <div class="col-12 mt-3 mt-md-4 admision-horario">
                            <div class="article-title">COSTOS DE ENSEÑANZA</div>
                            <div class="fw-bold">
                                1. OBSTETRICIA DE ALTO RIESGO <br />
                                2. SALUD REPRODUCTIVA
                            </div>
                            <table class="table table-sm table-bordered">
                                <thead>
                                    <tr>
                                        <th>CONCEPTO</th>
                                        <th>CANT</th>
                                        <th>COSTO</th>
                                        <th>TOTAL</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>Inscripción</td>
                                        <td>1</td>
                                        <td>S/ 100.00</td>
                                        <td>S/ 100.00</td>
                                    </tr>
                                    <tr>
                                        <td>Derecho de carpeta</td>
                                        <td>1</td>
                                        <td>S/ 250.00</td>
                                        <td>S/ 250.00</td>
                                    </tr>
                                    <tr>
                                        <td>Matrícula por ciclo</td>
                                        <td>3</td>
                                        <td>S/ 300.00</td>
                                        <td>S/ 900.00</td>
                                    </tr>
                                    <tr>
                                        <td>Pensión de estudios</td>
                                        <td>18</td>
                                        <td>S/ 400.00</td>
                                        <td>S/ 7200.00</td>
                                    </tr>
                                </tbody>
                            </table>
                            <div class="mt-3 fw-bold">3. ECOGRAFÍA OBSTÉTRICA</div>
                            <table class="table table-sm table-bordered">
                                <thead>
                                    <tr>
                                        <th>CONCEPTO</th>
                                        <th>CANT</th>
                                        <th>COSTO</th>
                                        <th>TOTAL</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>Inscripción</td>
                                        <td>1</td>
                                        <td>S/ 100.00</td>
                                        <td>S/ 100.00</td>
                                    </tr>
                                    <tr>
                                        <td>Derecho de carpeta</td>
                                        <td>1</td>
                                        <td>S/ 250.00</td>
                                        <td>S/ 250.00</td>
                                    </tr>
                                    <tr>
                                        <td>Matrícula por ciclo</td>
                                        <td>3</td>
                                        <td>S/ 400.00</td>
                                        <td>S/ 1200.00</td>
                                    </tr>
                                    <tr>
                                        <td>Pensión de estudios</td>
                                        <td>18</td>
                                        <td>S/ 450.00</td>
                                        <td>S/ 8100.00</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>

                        <div class="col-12 mt-3 mt-md-4 admision-horario">
                            <div class="article-title">BANCO DE LA NACIÓN</div>
                            <span class="numbers">Cta. Cte: 00541-043101</span>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 mt-3 mt-md-5">
                    <div class="mb-1 fw-bold">DIRIGIDO A</div>
                    <div class="mb-1" style="text-align: justify">
                        Profesionales Obstetras que deseen ser especialistas laborando en
                        instituciones.
                    </div>
                    <div class="mb-1 fw-bold">REQUISITOS DE ADMISIÓN</div>
                    <div class="mb-1">
                        <ul class="requirements-list">
                            <li>Solicitud de Admisión, debidamente llenada.</li>
                            <li>
                                Título Profesional de Obstetra registrado en SUNEDU (copia
                                autenticada por la Universidad de origen para Universidades
                                Nacionales, o revalidadas por SUNEDU en el caso de Universidades
                                Extranjeras).
                            </li>
                            <li>Currículo Vitae con documentos de los 3 últimos años.</li>
                            <li>
                                Copia del DNI legalizada por Notario, o del Carné de Extranjería o
                                Pasaporte si es extranjero.
                            </li>
                            <li>
                                Recibo de pago por Derecho de Inscripción y Derecho de Admisión.
                            </li>
                            <li>
                                Cuatro (04) fotografías recientes; con terno, tamaño carné a
                                colores.
                            </li>
                            <li>Compromiso de pago de estudios de Segunda Especialidad.</li>
                            <li>Compromiso de entrega de documentos faltantes.</li>
                            <li>Declaración Jurada de Autenticidad.</li>
                        </ul>
                    </div>
                    <div class="article-title">DESCARGAR FORMATOS</div>
                    <ol class="downloads-list">
                        <li>
                            <a
                                href="./descargas/FORMATOS (04) ADMISION 2024-I.pdf"
                                download="formatos-admision-2024-I.pdf"
                                >FORMATOS DE INSCRIPCIÓN 2024 - I</a
                            >
                        </li>
                    </ol>
                    <div class="article-title">TE ATENDEMOS</div>
                    <span class="numbers me-3"> 987 721 182 </span>
                    <a
                        title="Abrir WhatsApp"
                        href="https://wa.me/51987721182?text=Hola%2C%20👋%20¿Podría%20brindarme%20información%20sobre%20los%20programas%20de%20Segunda%20Especialidad%20que%20ofertan%3F"
                        ><span class="fa-brands fa-square-whatsapp text-success fa-xl"></span
                    ></a>
                    <a title="Realizar llamada" href="tel:+51987721182" class="ms-2">
                        <span class="fa-solid fa-square-phone text-primary fa-xl"></span></a
                    ><br />
                    <span class="numbers me-3"> 952 591 696 </span>
                    <a
                        title="Abrir WhatsApp"
                        href="https://wa.me/51952591696?text=Hola%2C%20👋%20¿Podría%20brindarme%20información%20sobre%20los%20programas%20de%20Segunda%20Especialidad%20que%20ofertan%3F"
                        ><span class="fa-brands fa-square-whatsapp text-success fa-xl"></span
                    ></a>
                    <a title="Realizar llamada" href="tel:+51952591696" class="ms-2">
                        <span class="fa-solid fa-square-phone text-primary fa-xl"></span
                    ></a>
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
