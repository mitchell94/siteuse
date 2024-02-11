<script setup>
import { onMounted, ref } from 'vue'
import { RouterLink, RouterView } from 'vue-router'

onMounted(() => {
    window.addEventListener('resize', onResize)

    return () => {
        window.removeEventListener('resize', onResize)
    }
})

let showMenu = ref(false)
const onResize = () => {
    let windowWidth =
        window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth

    if (windowWidth >= 992) {
        showMenu.value = true
    } else {
        showMenu.value = false
    }
}
onResize()
</script>

<template>
    <nav>
        <div class="container">
            <div class="row align-items-stretch">
                <div class="col-auto social-article">
                    <a
                        href="https://www.facebook.com/UnidaddeSegundaEspecialidad?locale=es_LA"
                        target="_blank"
                        title="social-facebook"
                    >
                        <img src="../assets/img/facebook.svg" alt="" width="28" height="28"
                    /></a>
                </div>
                <div class="col p-0">
                    <div id="menu" v-show="showMenu">
                        <ul class="menu-lista" @click="onResize">
                            <li>
                                <RouterLink to="/" class="exact-active">INICIO</RouterLink>
                            </li>
                            <li><RouterLink to="/nosotros">NOSOTROS</RouterLink></li>
                            <li><RouterLink to="/admision">ADMISIÓN</RouterLink></li>
                            <li><RouterLink to="/aro">PROGRAMA ARO</RouterLink></li>
                            <li><RouterLink to="/eco">PROGRAMA ECO</RouterLink></li>
                            <li><RouterLink to="/cacu">PROGRAMA CACU</RouterLink></li>
                        </ul>
                    </div>
                </div>
                <div class="col-auto d-flex justify-content-end align-items-center">
                    <a
                        href="https://usefcs.unsm.edu.pe/admin/"
                        target="_blank"
                        class="me-2 btn-admin"
                        >ADMIN</a
                    >
                    <a
                        href="https://usefcs.unsm.edu.pe/intranet/"
                        target="_blank"
                        class="btn-intranet"
                        >INTRANET</a
                    >
                </div>
            </div>
        </div>
    </nav>
    <main>
        <RouterView />
    </main>

    <footer>
        <section class="parent-container">
            <div class="container">
                <div class="row">
                    <div class="col footer-title"><span>Contacto</span></div>
                </div>
                <div class="row">
                    <div class="col">
                        <div class="row">
                            <div class="col contacto">
                                <span>Teléfono</span><br />
                                <span>987 721 182</span><br />
                                <span>952 591 696</span>
                            </div>
                            <div class="col contacto">
                                <span>Ubicación</span><br />
                                <span>FCS - Campus UNSM</span>
                            </div>
                        </div>
                        <div class="row align-items-stretch">
                            <div class="col contacto">
                                <span>Correo</span><br />
                                <span>usefcs@unsm.edu.pe</span>
                            </div>
                            <div class="col d-flex align-items-end">
                                <a
                                    href="https://www.facebook.com/UnidaddeSegundaEspecialidad?locale=es_LA"
                                    target="_blank"
                                    title="social-facebook"
                                >
                                    <img
                                        src="../assets/img/facebook.svg"
                                        alt=""
                                        width="32"
                                        height="32"
                                /></a>
                                <a href="https://unsm.edu.pe/" target="_blank" title="social-unsm">
                                    <img src="../assets/img/unsm.webp" alt="" width="32" height="32"
                                /></a>
                            </div>
                        </div>
                    </div>
                    <div
                        class="col-sm-12 col-md d-flex justify-content-center justify-content-md-end align-items-end mt-5 mt-md-0"
                    >
                        <img src="../assets/img/sunedu.webp" alt="" height="64" />
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="container">
                <div class="row">
                    <div class="col d-flex justify-content-center">
                        UNIDAD DE SEGUNDA ESPECIALIDAD - FCS/UNSM 2024
                    </div>
                </div>
            </div>
        </section>
    </footer>

    <button class="menu-button" title="show-menu" @click="showMenu = !showMenu">
        <span class="fa-solid fa-bars"></span>
    </button>
    
</template>

<style lang="css">
@import url('../assets/movil.css');
@import url('../assets/screens.css');
</style>
