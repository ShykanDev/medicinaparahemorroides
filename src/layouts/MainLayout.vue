<template>
    <div class="selection:bg-white selection:text-emerald-700 overflow-hidden">
        <header class="fixed left-0 right-0 z-50 flex flex-col text-white shadow-lg bg-emerald-700">
            <img src="../assets/ssl-certificate.png"  class="absolute w-10 right-0 md:hidden -bottom-6" alt="">
            <!-- Navegación principal -->
            <nav class="flex items-center justify-between px-4 lg:px-8">
                <!-- Logo -->
                 
                <img src="https://medicinaparaansiedad.com/img/logo.png" alt="Logo" class="w-11 md:w-12   lg:w-14" />
                <p class="hidden text-xl font-semibold font-poppins animate-fade-down md:block">medicinaparahemorroides.com</p>
                <!-- Links de navegación -->
                <div class="flex gap-4 text-sm font-medium lg:text-lg lg:gap-6 font-sour-gummy">
                    <RouterLink :class="{ 'italic animate-jump-in': route.name === 'home' }" :to="{ name: 'home' }">
                        Inicio
                    </RouterLink>
                    <RouterLink :class="{ 'italic animate-jump-in': route.name === 'beneficts' }"
                        :to="{ name: 'beneficts' }">
                        Beneficios
                    </RouterLink>
                    <RouterLink :class="{ 'italic animate-jump-in': route.name === 'ingredients' }"
                        :to="{ name: 'ingredients' }">
                        Ingredientes
                    </RouterLink>
                    <RouterLink :class="{ 'italic animate-jump-in': route.name === 'faqs' }" :to="{ name: 'faqs' }">
                        Preguntas
                    </RouterLink>
                    <a href="https://www.prasadam.mx/" target="_blank" class="hidden hover:text-orange-300 md:block">
                        Prasadam
                    </a>
                </div>
            </nav>

            <!-- Información de contacto -->
            <div
                class="flex-col relative hidden gap-4 px-4 py-3 text-xs lg:flex lg:flex-row lg:items-center lg:justify-evenly lg:text-base bg-emerald-800">
                <img src="../assets/ssl-certificate.png"  class="absolute w-11 right-0" alt="">
                <!-- Dirección -->
                <div class="flex items-center gap-2">
                    <v-icon name="md-locationon" class="text-emerald-300" scale="1.5" />
                    <a href="https://www.google.com.mx/maps/place/Gutenberg+128,+Anzures,+Miguel+Hidalgo,+11590+Ciudad+de+M%C3%A9xico,+CDMX/@19.4322888,-99.1760704,17z/data=!3m1!4b1!4m6!3m5!1s0x85d1f8b32758939b:0xf34fbd07bc47d6dd!8m2!3d19.4322888!4d-99.1760704!16s%2Fg%2F11c4n3lm2g?entry=ttu&g_ep=EgoyMDI0MTEwNS4wIKXMDSoASAFQAw%3D%3D"
                        target="_blank" class="hover:text-emerald-400">
                        Gutenberg #128 Anzures, Miguel Hidalgo, 11590 Ciudad de México
                    </a>
                </div>

                <!-- Teléfonos -->
                <div class="flex items-center gap-2">
                    <v-icon name="bi-telephone-fill" class="text-emerald-300" scale="1.5" />
                    <a href="tel:+525563950178" class="font-bold hover:text-emerald-400">
                        +52 55 6395 0178
                    </a>
                    <v-icon name="bi-telephone-fill" class="text-emerald-300" scale="1.5" />
                    <a href="tel:+525563950179" class="font-bold hover:text-emerald-400">
                        +52 55 6395 0179
                    </a>
                </div>

                <!-- WhatsApp -->
                <div class="flex items-center gap-2">
                    <v-icon name="co-whatsapp" class="text-emerald-300" scale="1.5" />
                    <a href="https://wa.me/525562516687" target="_blank" rel="noopener noreferrer"
                        class="font-bold hover:text-emerald-400">
                        +52 5562516687
                    </a>
                </div>
            </div>
        </header>

        <main class="lg:pt-[107px] pt-9">
            <slot name="main" />
        </main>
        <footer class="relative flex flex-col items-center gap-6 p-6 text-white bg-emerald-700 font-sour-gummy lg:p-10">
            <!-- Contact Title -->
            <h2 class="text-2xl font-bold lg:text-4xl">Contacto</h2>

            <!-- SSL Logo -->
            <img class="absolute w-10 top-2 right-4"
                src="https://shykandev.github.io/medicinaparadiabetes/assets/ssl-Cjd7i8VT.png" alt="SSL Logo">

            <!-- Location Section -->
            <div class="flex flex-col items-center gap-4">
                <div class="flex items-center gap-2">
                    <v-icon name="md-locationon" class="text-3xl" scale="1.5"></v-icon>
                    <a class="text-sm font-bold text-center lg:text-lg hover:text-orange-300"
                        href="https://www.google.com.mx/maps/place/Gutenberg+128,+Anzures,+Miguel+Hidalgo,+11590+Ciudad+de+M%C3%A9xico,+CDMX/@19.4322888,-99.1760704,17z/data=!3m1!4b1!4m6!3m5!1s0x85d1f8b32758939b:0xf34fbd07bc47d6dd!8m2!3d19.4322888!4d-99.1760704!16s%2Fg%2F11c4n3lm2g?entry=ttu&g_ep=EgoyMDI0MTEwNS4wIKXMDSoASAFQAw%3D%3D">
                        Gutenberg #128 Anzures, Miguel Hidalgo, 11590 Ciudad de México
                    </a>
                </div>

                <!-- Google Maps Embed -->
                <iframe class="w-full rounded-md shadow-md lg:w-4/4"
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3762.5395970522604!2d-99.1760704!3d19.4322888!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85d1f8b32758939b%3A0xf34fbd07bc47d6dd!2sGutenberg%20128%2C%20Anzures%2C%20Miguel%20Hidalgo%2C%2011590%20Ciudad%20de%20M%C3%A9xico%2C%20CDMX!5e0!3m2!1sen!2smx!4v1730328617197!5m2!1sen!2smx"
                    allowfullscreen="false" loading="lazy" referrerpolicy="no-referrer-when-downgrade" height="250"
                    style="border: 0;"></iframe>
            </div>

            <!-- Contact Info Section -->
            <div class="flex flex-wrap justify-center gap-6">
                <!-- Phone Numbers -->
                <div class="flex items-center gap-2">
                    <v-icon name="bi-telephone-fill" class="text-2xl"></v-icon>
                    <a href="tel:+525563950178" class="text-sm font-bold lg:text-lg hover:text-orange-300">
                        +52 55 6395 0178
                    </a>
                </div>
                <div class="flex items-center gap-2">
                    <v-icon name="bi-telephone-fill" class="text-2xl"></v-icon>
                    <a href="tel:+525563950179" class="text-sm font-bold lg:text-lg hover:text-orange-300">
                        +52 55 6395 0179
                    </a>
                </div>

                <!-- Email -->
                <div class="flex items-center gap-2">
                    <v-icon name="md-email" class="text-2xl"></v-icon>
                    <a href="mailto:informes@prasadam.mx" class="text-sm font-bold lg:text-2xl hover:text-orange-300">
                        informes@prasadam.mx
                    </a>
                </div>

                <!-- WhatsApp -->
                <div class="flex items-center gap-2">
                    <v-icon name="co-whatsapp" class="text-xl"></v-icon>
                    <a href="https://wa.me/525562516687" class="text-sm font-bold lg:text-2xl hover:text-orange-300"
                        target="_blank" rel="noopener noreferrer">
                        +52 5562516687
                    </a>
                </div>
            </div>

            <!-- Footer Bottom -->
            <div class="text-center">
                <p class="text-sm font-bold lg:text-lg">
                    Todos los derechos reservados &copy; {{ new Date().getFullYear() }}
                </p>
                <p class="text-sm lg:text-lg">
                    Design: <strong class="font-normal">PACA</strong>
                </p>
            </div>
        </footer>

    </div>
</template>

<script lang="ts" setup>
import { useRoute } from 'vue-router';

const route = useRoute();
</script>

<style scoped></style>