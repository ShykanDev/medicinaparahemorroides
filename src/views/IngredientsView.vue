<template>
    <div class="">
        <MainLayout >
            <template #main>
                <h1 class="text-3xl font-extrabold text-center text-white md:py-7 bg-cyan-600 font-poppins">Conoce los ingredientes naturales de CIDNI</h1>
                <div class="grid grid-cols-3">
                <img class="animate-flip-up" src="../assets/front.png" alt="">
                <img class="animate-flip-up" src="../assets/syrup.png" alt="">
                <img class="animate-flip-up" src="../assets/frontRight.png" alt="">
              </div>
                <section class="flex flex-wrap justify-between gap-5 p-4 font-poppins">
  <div class="flex-1 sm:flex-1 md:flex-1 lg:w-1/2">
    <h3 class="mb-4 text-xl font-semibold">Características del Producto</h3>
    <ul class="p-0 list-none">
      <li><strong>Cantidad de Cápsulas:</strong> 60 cápsulas por envase / Botella 200ml</li>
      <li><strong>Tamaño de la Porción:</strong> 1 cápsula/15ml</li>
      <li><strong>Modo de Uso:</strong> Tomar 1 cápsula de 1 a 2 veces al día, preferiblemente con comida o según lo indique un profesional de la salud.</li>
      <li><strong>Almacenamiento:</strong> Mantener en un lugar fresco y seco, lejos de la luz solar directa.</li>
      <li><strong>Advertencias:</strong> Consultar a un profesional de la salud si está embarazada o en período de lactancia. Mantener fuera del alcance de los niños.</li>
      <li><strong>Categoría:</strong> Suplemento dietético</li>
    </ul>
  </div>
  <div class="flex-1 sm:flex-1 md:flex-1 lg:w-1/2">
    <h3 class="mb-4 text-xl font-semibold">Resumen de Ingredientes</h3>
    <ul class="p-0 list-none">
  <li><span class="font-bold">Amalaki 🌿</span> Rico en vitamina C, reduce la acidez estomacal y favorece la regeneración de la mucosa gástrica.</li>
  <li><span class="font-bold">Guduchi 🌱</span> Alivia la inflamación gástrica y apoya el equilibrio del sistema digestivo.</li>
  <li><span class="font-bold">Bhringraj 🍃</span> Conocido por sus propiedades protectoras del hígado, también ayuda a reducir los síntomas de indigestión.</li>
  <li><span class="font-bold">Chandan 🌳</span> Calma el sistema digestivo y reduce la sensación de ardor estomacal.</li>
  <li><span class="font-bold">Karpur Kachari 🌾</span> Mejora la digestión y alivia la hinchazón abdominal asociada con la gastritis.</li>
  <li><span class="font-bold">Katuki 🌱</span> Promueve la desintoxicación del hígado y regula la producción de ácidos estomacales.</li>
  <li><span class="font-bold">Vasa 🍃</span> Favorece la salud digestiva y ayuda a proteger el revestimiento del estómago.</li>
  <li><span class="font-bold">Yasthimadhu 🌿</span> Alivia el dolor estomacal y protege contra úlceras al fortalecer la mucosa gástrica.</li>
  <li><span class="font-bold">Probiótico 🦠</span> Restaura el equilibrio de la flora intestinal, mejorando la digestión y reduciendo la inflamación gástrica.</li>
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
    title: "Amalaki Ext. (Emblica officinalis)",
    shortResume: "Conocido por sus propiedades antioxidantes y antiinflamatorias.",
    longResume: "Amalaki, o Amla, es una fruta utilizada en la medicina ayurvédica. Es rica en vitamina C y se utiliza tradicionalmente para mejorar la digestión, fortalecer el sistema inmune y reducir la inflamación. Además, sus propiedades antioxidantes ayudan a combatir los radicales libres, contribuyendo a la salud general.",
    listTitles: [
      "Propiedades antioxidantes",
      "Mejora la digestión",
      "Fortalece el sistema inmunológico"
    ],
    listContent: [
      "Amalaki es conocido por su alta concentración de vitamina C, lo que lo convierte en un potente antioxidante.",
      "Ayuda a mejorar la digestión, aliviando el malestar estomacal y promoviendo la absorción de nutrientes.",
      "Fortalece el sistema inmunológico, ayudando a prevenir infecciones y enfermedades comunes."
    ],
    imgSrc:'https://zurcetraud.com/wp-content/uploads/2023/03/amla1-1024x678-1.jpg'
  },
  {
    title: "Guduchi Ext. (Tinospora cordifolia)",
    shortResume: "Promueve la salud digestiva y tiene efectos inmunoestimulantes.",
    longResume: "Guduchi, también conocida como 'la planta de la inmortalidad', es una hierba utilizada ampliamente en la medicina ayurvédica. Se cree que tiene propiedades antiinflamatorias, antioxidantes y es eficaz en el tratamiento de afecciones digestivas como la gastritis y la indigestión.",
    listTitles: [
      "Efectos antiinflamatorios",
      "Apoya la salud digestiva",
      "Mejora la función inmunológica"
    ],
    listContent: [
      "Guduchi tiene poderosas propiedades antiinflamatorias que ayudan a reducir la inflamación en el cuerpo.",
      "Ayuda a regular la digestión, aliviando síntomas de acidez y gastritis.",
      "Estimula y fortalece el sistema inmunológico, promoviendo una respuesta inmune eficiente."
    ],
    imgSrc:'https://mejorconsalud.as.com/wp-content/uploads/2021/09/fruto-guduchi.jpg'
  },
  {
    title: "Bhringraj Ext. (Eclipta alba)",
    shortResume: "Favorece la salud del cabello y el hígado, y tiene propiedades antiinflamatorias.",
    longResume: "Bhringraj es una planta conocida por sus efectos positivos en la salud capilar, pero también tiene beneficios en la mejora de la digestión y en la reducción de la inflamación. Se utiliza tradicionalmente para tratar afecciones del hígado, y su capacidad para reducir el estrés también contribuye a su efectividad en la gestión de problemas digestivos.",
    listTitles: [
      "Mejora la salud del cabello",
      "Propiedades antiinflamatorias",
      "Apoya la función hepática"
    ],
    listContent: [
      "Bhringraj se utiliza en tratamientos para fortalecer el cabello y prevenir su caída.",
      "Posee propiedades antiinflamatorias que ayudan a aliviar los problemas digestivos, como la gastritis.",
      "Apoya la función hepática, ayudando al hígado a desintoxicarse y mejorar su eficiencia."
    ],
    imgSrc:'https://vermiorganics.co/cdn/shop/files/204.jpg?v=1704369242'
  },
  {
    title: "Chandan Ext. (Santalum album)",
    shortResume: "Conocido por sus propiedades calmantes y antiinflamatorias.",
    longResume: "El sándalo es una planta que se utiliza en la medicina tradicional india, conocida por sus efectos calmantes sobre el sistema nervioso y su capacidad para aliviar la inflamación. Ayuda a reducir el malestar digestivo y puede tener un efecto positivo en el tratamiento de la gastritis.",
    listTitles: [
      "Propiedades calmantes",
      "Efectos antiinflamatorios",
      "Mejora el bienestar digestivo"
    ],
    listContent: [
      "Chandan es conocido por su efecto calmante sobre el sistema nervioso, lo que ayuda a reducir el estrés, un factor que agrava la gastritis.",
      "Posee propiedades antiinflamatorias que ayudan a reducir la inflamación en el tracto digestivo.",
      "Contribuye a mejorar el bienestar digestivo y reduce los síntomas de la acidez estomacal y malestar general."
    ],
    imgSrc:'https://sheffields.com/html/scale/800//data/Santalum_album_1713.jpg.webp'
  },
  {
    title: "Karpur Kachari Ext. (Hedychium spicatum)",
    shortResume: "Ayuda a aliviar la inflamación y promueve la salud digestiva.",
    longResume: "Karpur Kachari es una planta utilizada en la medicina tradicional para tratar diversas afecciones, especialmente aquellas relacionadas con la inflamación. Su uso en la medicina ayurvédica incluye el tratamiento de problemas digestivos, como la gastritis y la acidez.",
    listTitles: [
      "Propiedades antiinflamatorias",
      "Alivio de problemas digestivos",
      "Reduce la acidez estomacal"
    ],
    listContent: [
      "Karpur Kachari posee propiedades antiinflamatorias que ayudan a reducir la inflamación interna, aliviando la gastritis.",
      "Es eficaz en el tratamiento de trastornos digestivos, reduciendo síntomas como la acidez y la indigestión.",
      "Ayuda a equilibrar los niveles de acidez estomacal, proporcionando alivio a quienes sufren de reflujo ácido."
    ],
    imgSrc:'https://www.mantra-aromatherapy.co.uk/cdn/shop/files/spikedgingerlily1_1200x1200.jpg?v=1712248247'
  },
  {
    title: "Katuki Ext. (Picrorhiza kurroa)",
    shortResume: "Utilizada para mejorar la digestión y apoyar la salud hepática.",
    longResume: "Katuki es una hierba tradicionalmente utilizada para mejorar la digestión y tratar afecciones hepáticas. Es conocida por sus propiedades desintoxicantes y su capacidad para aliviar problemas estomacales y digestivos, como la gastritis y el síndrome del intestino irritable.",
    listTitles: [
      "Mejora la digestión",
      "Apoya la salud hepática",
      "Propiedades desintoxicantes"
    ],
    listContent: [
      "Katuki promueve la digestión eficiente y ayuda a aliviar la hinchazón y el malestar estomacal.",
      "Contribuye a la desintoxicación del hígado, ayudando a mejorar su función y reducir la inflamación.",
      "Tiene propiedades desintoxicantes que favorecen la eliminación de toxinas del cuerpo, lo que mejora la salud general."
    ],
    imgSrc:'https://www.liveayurved.com/images/medicinal-plants/Katuki.jpg'
  },
  {
    title: "Vasa Ext. (Adhatoda vasika)",
    shortResume: "Ayuda a aliviar los problemas respiratorios y mejora la salud digestiva.",
    longResume: "Vasa es una planta tradicionalmente utilizada para tratar problemas respiratorios, pero también tiene propiedades antiinflamatorias que pueden ser útiles para aliviar los síntomas de la gastritis. Sus efectos beneficiosos sobre el sistema digestivo y respiratorio hacen de esta planta un remedio versátil en la medicina ayurvédica.",
    listTitles: [
      "Propiedades antiinflamatorias",
      "Alivio de problemas respiratorios",
      "Mejora la salud digestiva"
    ],
    listContent: [
      "Vasa tiene propiedades antiinflamatorias que ayudan a reducir la inflamación en el tracto digestivo.",
      "Se utiliza para aliviar problemas respiratorios, como el asma, y puede ayudar a reducir el estrés relacionado con los problemas digestivos.",
      "Mejora la digestión y puede aliviar el malestar estomacal, reduciendo los síntomas de la gastritis."
    ],
    imgSrc:'https://i0.wp.com/www.ayurtimes.com/wp-content/uploads/2017/07/Adhatoda-Vasica-Vasa-herb.jpg'
  },
  {
    title: "Yasthimadhu Ext. (Glycyrrhiza glabra)",
    shortResume: "Conocido por sus propiedades antiinflamatorias y protectoras del estómago.",
    longResume: "El regaliz es una planta con propiedades antiinflamatorias que ayuda a aliviar la inflamación en el estómago y el tracto digestivo. Es ampliamente utilizado en la medicina tradicional para tratar afecciones como la gastritis y el síndrome del intestino irritable. Su capacidad para proteger la mucosa gástrica lo convierte en un remedio popular.",
    listTitles: [
      "Protege la mucosa gástrica",
      "Reduce la inflamación",
      "Mejora la digestión"
    ],
    listContent: [
      "Yasthimadhu ayuda a proteger la mucosa gástrica, reduciendo el riesgo de úlceras y gastritis.",
      "Posee propiedades antiinflamatorias que alivian la inflamación y el dolor abdominal causados por la gastritis.",
      "Favorece la digestión, aliviando el malestar y ayudando a mejorar la absorción de nutrientes."
    ],
    imgSrc:'https://cdn.shopify.com/s/files/1/0579/0262/9029/files/slide_4_e2edfd2a-f175-4dcd-8936-34a7c72b41bc.png?v=1724670722'
  }
];


</script>

<style scoped>

</style>