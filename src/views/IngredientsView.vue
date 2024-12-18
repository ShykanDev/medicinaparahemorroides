<template>
    <div class="">
        <MainLayout >
            <template #main>
              <h1 class="py-8 text-4xl font-bold text-center rounded-lg shadow-lg text-cyan-900 bg-gradient-to-r from-emerald-100 via-white to-emerald-100 font-poppins">
  Conozca los ingredientes <span class="text-cyan-600">NATURALES</span> que <span class="underline decoration-cyan-600">PILOGUARD</span> le ofrece para las <span class="text-cyan-600">HEMORROIDES</span>
</h1>
                <div class="grid grid-cols-3">
                <img class="animate-flip-up" src="https://i.ibb.co/j53jSP7/right-Bottle.png" alt="">
                <img class="animate-flip-up" src="https://i.ibb.co/p369gXp/image-1-removebg-preview.png" alt="">
                <img class="animate-flip-up" src="https://i.ibb.co/GF34xB8/image-2-removebg-preview.png" alt="">
              </div>
                <section class="flex flex-wrap justify-between gap-5 p-4 font-poppins">
  <div class="flex-1 sm:flex-1 md:flex-1 lg:w-1/2">
    <h3 class="mb-4 text-xl font-semibold">Características del Producto</h3>
    <ul class="p-0 list-none">
      <li><strong>Cantidad de Cápsulas:</strong> 60 cápsulas por envase</li>
      <li><strong>Tamaño de la Porción:</strong> 1 cápsula</li>
      <li><strong>Modo de Uso:</strong> Tomar 1 cápsula de 1 a 2 veces al día, preferiblemente con comida o según lo indique un profesional de la salud.</li>
      <li><strong>Almacenamiento:</strong> Mantener en un lugar fresco y seco, lejos de la luz solar directa.</li>
      <li><strong>Advertencias:</strong> Consultar a un profesional de la salud si está embarazada o en período de lactancia. Mantener fuera del alcance de los niños.</li>
      <li><strong>Categoría:</strong> Suplemento dietético</li>
    </ul>
  </div>
  <div class="flex-1 sm:flex-1 md:flex-1 lg:w-1/2">
    <h3 class="mb-4 text-xl font-semibold">Resumen de Ingredientes</h3>
    <ul class="p-0 list-none">
  <li><span class="font-bold">Khacir Ext. (Acacia catechu) 🌿</span> Alivia la inflamación y promueve la cicatrización de los tejidos dañados en la zona anal, proporcionando alivio en las hemorroides.</li>
  <li><span class="font-bold">Apamarg Ext. (Achyranthes aspera) 🌱</span> Mejora la circulación sanguínea, reduce la hinchazón y alivia la congestión venosa, ayudando a disminuir la presión en las venas hemorroidales.</li>
  <li><span class="font-bold">Kumari Ext. (Aloe vera) 🍃</span> Calma, hidrata y reduce la inflamación en la zona afectada, proporcionando alivio del dolor y la irritación de las hemorroides.</li>
  <li><span class="font-bold">Kovida Ext. (Bauhinia variegata) 🌳</span> Ayuda a tonificar los vasos sanguíneos, reduciendo el sangrado y fortaleciendo las venas afectadas por las hemorroides.</li>
  <li><span class="font-bold">Chitrak Ext. (Plumbago zeylanica) 🌾</span> Mejora la digestión y reduce la inflamación en la zona afectada, aliviando la presión y el dolor asociado con las hemorroides.</li>
  <li><span class="font-bold">Daruharidra Ext. (Berberis aristata) 🌱</span> Propiedades antiinflamatorias que ayudan a reducir la inflamación y el dolor, aliviando los síntomas de las hemorroides.</li>
  <li><span class="font-bold">Neem Ext. (Azadirachta indica) 🍃</span> Antiinflamatorio natural que ayuda a reducir la irritación y previene infecciones en la zona anal afectada por hemorroides.</li>
  <li><span class="font-bold">Castor Ext. (Ricinus communis) 🌿</span> Alivia el dolor y la inflamación, promoviendo la curación de los tejidos dañados y reduciendo el malestar asociado con las hemorroides.</li>
  <li><span class="font-bold">Dhataki Ext. (Woodfordia fruticosa) 🌱</span> Propiedades calmantes y antiinflamatorias que ayudan a aliviar el dolor y la irritación en la zona afectada por las hemorroides.</li>
  <li><span class="font-bold">Haridra Ext. (Curcuma longa) 🍃</span> Potente antiinflamatorio que reduce la inflamación, el dolor y la irritación, favoreciendo la recuperación de las hemorroides.</li>
  <li><span class="font-bold">Probiótico 🦠</span> Restaura el equilibrio de la flora intestinal, mejorando la digestión y reduciendo la inflamación en la zona afectada por las hemorroides.</li>
</ul>

  </div>
</section>
            <section class="flex flex-wrap justify-around gap-4 p-4 animate-fade-up">
                <IngredientCard v-for="ingredient in ingredients" :key="ingredient.title" :title="ingredient.title" :smallIntro="ingredient.shortResume" :description="ingredient.longResume" :tags="ingredient.listTitles" :listTitles="ingredient.listTitles" :listContent="ingredient.listContent" :imgSrc="ingredient.imgSrc" />
            </section>
            </template>
        </MainLayout>
    </div>
</template>

<script lang="ts" setup>
import IngredientCard from '@/components/IngredientCard.vue';
import MainLayout from '@/layouts/MainLayout.vue';
const ingredients = [
  {
    title: "Khacir Ext. (Acacia catechu)",
    shortResume: "Alivia la inflamación y promueve la cicatrización de los tejidos.",
    longResume: "Khacir, o Acacia catechu, es conocida por sus propiedades antiinflamatorias y cicatrizantes, lo que la hace útil en el tratamiento de las hemorroides. Ayuda a reducir la inflamación y promover la cicatrización de los tejidos dañados en la zona afectada, aliviando los síntomas dolorosos asociados con las hemorroides.",
    listTitles: [
      "Propiedades antiinflamatorias",
      "Cicatrización de tejidos",
      "Alivio de dolor y molestias"
    ],
    listContent: [
      "Reducción de la inflamación en las hemorroides, ayudando a disminuir el dolor y la incomodidad.",
      "Favorece la cicatrización de los tejidos dañados, promoviendo una recuperación más rápida.",
      "Alivio del dolor en la zona afectada, ayudando a calmar las molestias durante el proceso de curación."
    ],
    imgSrc: 'https://indiabiodiversity.org/files-api/api/get/raw/img//Acacia%20catechu/Acacia_catechu_leaf.jpg'
  },
  {
    title: "Apamarg Ext. (Achyranthes aspera)",
    shortResume: "Mejora la circulación sanguínea y reduce la hinchazón.",
    longResume: "Apamarg, o Achyranthes aspera, es una planta con efectos antiinflamatorios que también favorece la circulación sanguínea, lo que es fundamental para tratar las hemorroides. Ayuda a reducir la hinchazón y mejora el flujo sanguíneo en la zona afectada, disminuyendo el riesgo de complicaciones y aliviando los síntomas.",
    listTitles: [
      "Mejora la circulación sanguínea",
      "Reduce la hinchazón",
      "Alivio de la congestión venosa"
    ],
    listContent: [
      "Apoya la circulación sanguínea en la zona afectada, ayudando a reducir la presión en las venas hemorroidales.",
      "Disminuye la hinchazón, aliviando la sensación de incomodidad y presión en la zona anal.",
      "Alivia la congestión venosa, ayudando a prevenir que las hemorroides empeoren."
    ],
    imgSrc: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6T9rmClPmDaBKou76gxBS_JbSurZghta55Q&s'
  },
  {
    title: "Kumari Ext. (Aloe vera)",
    shortResume: "Calma, hidrata y reduce la inflamación en la zona afectada.",
    longResume: "El Aloe vera es ampliamente reconocido por sus propiedades calmantes y antiinflamatorias, siendo un remedio natural eficaz para las hemorroides. Su capacidad para calmar la piel y reducir la inflamación en la zona anal ayuda a aliviar el dolor y la irritación, mientras que su acción hidratante promueve la curación de los tejidos dañados.",
    listTitles: [
      "Propiedades antiinflamatorias",
      "Calma y alivia la irritación",
      "Hidrata y promueve la cicatrización"
    ],
    listContent: [
      "Reduce la inflamación en las hemorroides, proporcionando alivio del dolor y la irritación.",
      "Calma la zona anal afectada, aliviando la picazón y el ardor.",
      "Hidrata y promueve la cicatrización de los tejidos, favoreciendo una recuperación más rápida."
    ],
    imgSrc: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwsx0Z1Nxu2BEXRX-ZT4DRHLonuqcOiA56EQ&s'
  },
  {
    title: "Kovida Ext. (Bauhinia variegata)",
    shortResume: "Ayuda a tonificar los vasos sanguíneos y a reducir el sangrado.",
    longResume: "Kovida, o Bauhinia variegata, tiene propiedades astringentes que ayudan a tonificar los vasos sanguíneos y reducir el sangrado asociado con las hemorroides. Al fortalecer los vasos sanguíneos debilitados, contribuye a la prevención de nuevas hemorroides y ayuda a disminuir el flujo sanguíneo excesivo.",
    listTitles: [
      "Astringente natural",
      "Tonifica los vasos sanguíneos",
      "Reduce el sangrado"
    ],
    listContent: [
      "Actúa como astringente, ayudando a reducir el sangrado de las hemorroides.",
      "Tonifica los vasos sanguíneos, mejorando la circulación y reduciendo la inflamación.",
      "Disminuye el riesgo de nuevos brotes de hemorroides al fortalecer los vasos sanguíneos debilitados."
    ],
    imgSrc: 'https://www.plantasyhongos.es/herbarium/b/Bauhinia_variegata_03.jpg'
  },
  {
    title: "Chitrak Ext. (Plumbago zeylanica)",
    shortResume: "Mejora la digestión y reduce la inflamación en la zona afectada.",
    longResume: "Chitrak, o Plumbago zeylanica, es conocido por sus propiedades digestivas y antiinflamatorias, lo que lo convierte en un buen complemento en el tratamiento de las hemorroides. Ayuda a mejorar la digestión, lo que puede reducir la presión en las venas rectales, y al mismo tiempo, disminuye la inflamación en la zona afectada.",
    listTitles: [
      "Mejora la digestión",
      "Reduce la inflamación",
      "Alivio de la presión interna"
    ],
    listContent: [
      "Mejora la digestión, reduciendo la presión interna que puede contribuir al agravamiento de las hemorroides.",
      "Disminuye la inflamación en la zona anal, proporcionando alivio de los síntomas.",
      "Alivia la presión en las venas rectales, ayudando a reducir el dolor y la incomodidad."
    ],
    imgSrc: 'https://rukminim2.flixcart.com/image/850/1000/k01b8280/plant-seed/b/p/e/50-hs183-shop-360-garden-original-imafjwmdmbgfgmby.jpeg?q=90&crop=false'
  },
  {
    title: "Gokshura Ext. (Tribulus terrestris)",
    shortResume: "Reduce la inflamación y favorece la salud venosa.",
    longResume: "Gokshura, o Tribulus terrestris, es una planta que posee propiedades antiinflamatorias que la hacen útil para tratar hemorroides. Ayuda a reducir la inflamación en la zona afectada y favorece la salud de las venas, mejorando la circulación sanguínea en la región anal.",
    listTitles: [
      "Propiedades antiinflamatorias",
      "Mejora la salud venosa",
      "Reducción de la inflamación"
    ],
    listContent: [
      "Reduce la inflamación, aliviando el dolor y la incomodidad asociados con las hemorroides.",
      "Mejora la circulación sanguínea, ayudando a aliviar la presión en las venas hemorroidales.",
      "Favorece la salud venosa, reduciendo el riesgo de complicaciones en las hemorroides."
    ],
    imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Tribulus_terrestris_%28Family_Zygophyllaceae%29.jpg/800px-Tribulus_terrestris_%28Family_Zygophyllaceae%29.jpg'
  },
  {
    title: "Haritaki Ext. (Terminalia chebula)",
    shortResume: "Mejora la digestión y ayuda a reducir la presión interna.",
    longResume: "Haritaki, o Terminalia chebula, es conocida por sus propiedades digestivas y purificadoras, que son útiles para tratar las hemorroides. Ayuda a mejorar la digestión, reduciendo la presión en las venas rectales, y favorece la eliminación de toxinas, lo que contribuye a una mejor circulación en la zona anal.",
    listTitles: [
      "Mejora la digestión",
      "Reduce la presión interna",
      "Favorece la eliminación de toxinas"
    ],
    listContent: [
      "Facilita la digestión, reduciendo la presión que puede agravar las hemorroides.",
      "Alivia la presión interna, ayudando a reducir el dolor y la inflamación.",
      "Contribuye a la eliminación de toxinas, mejorando la circulación y reduciendo la inflamación."
    ],
    imgSrc: 'https://m.media-amazon.com/images/I/61XwH4rxm5L._AC_UF1000,1000_QL80_.jpg'
  },
  {
    title: "Brahmi Ext. (Bacopa monnieri)",
    shortResume: "Alivia el estrés y mejora la circulación sanguínea.",
    longResume: "Brahmi, o Bacopa monnieri, es conocida por sus propiedades calmantes y su capacidad para mejorar la circulación sanguínea. Aunque es más conocida por sus efectos en la mente, también es útil en el tratamiento de las hemorroides, ya que ayuda a reducir el estrés y mejora la circulación en la zona afectada, contribuyendo a la recuperación.",
    listTitles: [
      "Reducción del estrés",
      "Mejora la circulación sanguínea",
      "Favorece la recuperación"
    ],
    listContent: [
      "Ayuda a reducir el estrés, lo que puede agravar los síntomas de las hemorroides.",
      "Mejora la circulación sanguínea, favoreciendo la recuperación de las venas afectadas.",
      "Contribuye a la regeneración de los tejidos y a la recuperación de la zona anal."
    ],
    imgSrc: 'https://s3.amazonaws.com/eit-planttoolbox-prod/media/images/Bacopa_monnieri_form_nk2V4Tw1M3EM.jpg'
  },
  {
    title: "Manjistha Ext. (Rubia cordifolia)",
    shortResume: "Purifica la sangre y reduce la inflamación.",
    longResume: "Manjistha, o Rubia cordifolia, es una planta conocida por sus propiedades purificadoras y antiinflamatorias. Ayuda a purificar la sangre, lo que puede ser útil para tratar las hemorroides, ya que mejora la circulación y reduce la inflamación en la zona afectada.",
    listTitles: [
      "Purifica la sangre",
      "Reduce la inflamación",
      "Mejora la circulación"
    ],
    listContent: [
      "Purifica la sangre, lo que puede contribuir a la mejora general de la circulación.",
      "Reduce la inflamación en las hemorroides, proporcionando alivio del dolor y la incomodidad.",
      "Mejora la circulación sanguínea en la zona afectada, ayudando a aliviar la presión en las venas hemorroidales."
    ],
    imgSrc: 'https://www.equisalud.com/wp-content/uploads/2023/01/Manjistha.webp'
  }
];




</script>

<style scoped>

</style>