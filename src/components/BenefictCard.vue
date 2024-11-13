<template>
    <div class="relative overflow-hidden transition-all duration-500 transform rounded-lg shadow-lg w-80 hover:min-h-[600px] min-h-96 ">
   <img alt="A placeholder image of a scenic landscape with mountains and a lake" class="absolute inset-0 object-cover w-full h-full" height="400" :src="imgSrc" width="320"/>
   <div class="absolute inset-0 flex flex-col justify-start p-4 bg-black bg-opacity-50">
    <h2 class="mb-2 text-2xl font-bold text-white">
     {{ title }}
    </h2>
    <h4 class="mb-2 text-lg text-white">
     {{ smallDescription }}
    </h4>
    <div class="relative group">
     <button class="px-4 py-2 text-white transition-opacity duration-500 bg-blue-500 rounded group-hover:opacity-0">
      Más Información
     </button>
     <p class="absolute top-0 left-0 mt-12 text-white transition-opacity duration-500 opacity-0 group-hover:opacity-100">{{ description }}</p>
    </div>
   </div>
  </div>

</template>

<script lang="ts" setup>
const props = defineProps({
        title: {
            type: String,
            default: 'Título de la Tarjeta',
        },
        smallDescription: {
            type: String,
            default: 'Pequeño resumen',
        },
        description: {
            type: String,
            default: 'lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt debitis labore iusto aspernatur asperiores incidunt exercitationem nemo earum. Atque, minima!',
        },
        imgSrc: {
            type: String,
        //   required: true
        default: 'https://images.pexels.com/photos/12327637/pexels-photo-12327637.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load',
        }
})
</script>
<style scoped>
.group:hover .group-hover\:opacity-0 {
         opacity: 0;
     }
     .group:hover .group-hover\:opacity-100 {
         opacity: 1;
     }
</style>