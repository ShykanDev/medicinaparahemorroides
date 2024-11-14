<template>
    <div class="">
        <MainLayout>
            <template #main>
                <article class="w-full overflow-hidden lg:flex lg:items-center ">
            <div
              class="flex flex-col items-center pt-2 lg:items-center lg:flex lg:justify-around lg:w-1/3 lg:w lg:h-screen rounded-bl-md rounded-br-md lg:py-11 ">
              <h2 class="hidden text-3xl font-extrabold text-center text-cyan-600 font-poppins animate-fade-down lg:block">
                Alivio natural con CIDNI para la gastritis </h2>
              <h1 class="text-xl font-extrabold text-center text-gray-800 lg:text-3xl font-poppins animate-fade-down">
                <span class="text-cyan-600 ">Su escudo natural contra el reflujo</span>
              </h1>
              <h1 class="text-xl font-extrabold text-center text-gray-800 lg:text-3xl font-poppins animate-fade-down">
                <span class="text-emerald-500 ">Medicina ayurvédica con origen en la India</span>
              </h1>
              <a href="#cidni"
                class="p-1 my-3 font-bold rounded-md bg-cyantext-cyan-600 lg:rounded-lg lg:text-xl lg:p-2 text-cyan-600 font-poppins animate-bounce">Conozca
                más</a>
            </div>
            <img src="../assets/mainImg.jpg" class="lg:w-2/3 animate-fade-up lg:h-screen" alt="">
          </article>
                <section  id="cidni" class="space-y-20 overflow-hidden">
                    <CardInfoSm class="" img-center="https://plus.unsplash.com/premium_photo-1693266635481-37de41003239?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8aGVyYnN8ZW58MHx8MHx8fDA%3D" :title="info1.title" :description="info1.content" :description2="info1.content2"/>
                    <CardInfoSm data-aos="fade-right" class="" img-center="https://plus.unsplash.com/premium_photo-1722658473477-0c8ab1b79acf?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8ZXN0b21hZ298ZW58MHx8MHx8fDA%3D" :title="info2.title" :description="info2.content" :description2="info2.content2"/>
                    <CardInfoSm data-aos="fade-left" class="" img-center="https://plus.unsplash.com/premium_photo-1723108858066-66b1bd834675?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NDV8fGRpZ2VzdGlvbnxlbnwwfHwwfHx8MA%3D%3D" :title="info3.title" :description="info3.content" :description2="info3.content2"/>
                    <CardInfoSm data-aos="fade-right" class="" img-center="https://images.unsplash.com/photo-1687273195751-14befe467d43?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjZ8fGhlcmJzfGVufDB8fDB8fHww" :title="info4.title" :description="info4.content" :description2="info4.content2"/>
                    <CardInfoSm data-aos="fade-left" class="" img-center="https://images.unsplash.com/photo-1513097847644-f00cfe868607?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NTR8fHBlbnNhbmRvfGVufDB8fDB8fHww" :title="info5.title" :description="info5.content" :description2="info5.content2"/>
                    <CardInfoSm data-aos="fade-right" class="" img-center="https://images.unsplash.com/photo-1591343395902-1adcb454c4e2?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mjh8fHBlcnNvbmElMjBtZWRpdGFuZG98ZW58MHx8MHx8fDA%3D" :title="info6.title" :description="info6.content" :description2="info6.content2"/>
                    <CardInfoSm data-aos="fade-left" class="" img-center="https://storage.googleapis.com/a1aa/image/FgyTilXtIZqzAR5EhFODgfBT5SgjXJu0t8DuGahyrhVc0O4JA.jpg" :title="info7.title" :description="info7.content" :description2="info7.content2"/>
                </section>
                <div class="w-full h-[1px] my-4 bg-cyan-800" />
                <section>
                    <h2 class="my-4 text-3xl font-semibold text-center text-cyan-800">Mira este video sobre como la ayurveda puede ayudarte en los problemas de digestión incluyendo gastritis</h2>
                    <iframe class="w-full h-52 lg:h-96" src="https://www.youtube.com/embed/ihJ2nLGGXms?si=g-nTfsrQcoi29V7u" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </section>
                <div class="w-full h-[1px] my-4 bg-cyan-800" />

                <h2 class="my-4 text-3xl font-semibold text-center text-cyan-800">Noticias</h2>
                <section class="flex flex-col flex-wrap w-full px-3 space-y-5 font-poppins mt-11 md:flex-row md:justify-around">
                  <NewsCard title="La mayoría de casos de gastritis es consecuencia de infección por la bacteria Helicobacter pylori" description="También puede deberse al consumo de medicamentos o alimentos con picante, condimentos o irritantes." href-link="https://www.gob.mx/salud/prensa/204-la-mayoria-de-casos-de-gastritis-es-consecuencia-de-infeccion-por-la-bacteria-helicobacter-pylori" img-src="https://www.gob.mx/cms/uploads/press/main_image/274099/post_IMAGEN2022-02.jpg"/>
                  <NewsCard title="Gastritis, una enfermedad de la vida moderna" description="Si hay una enfermedad asociada a los afanes de la modernidad, esa es la gastritis. Todos en algún momento hemos experimentado ese dolor en la boca del estómago que nos quema. A continuación despejamos los principales interrogantes entorno al tema." href-link="https://www.mysanitas.com/es/blog/gastritis-una-enfermedad-de-la-vida-moderna" img-src="https://www.mysanitas.com/sites/default/files/articles/gastritis_image.jpg" />
                  <NewsCard title="9 de cada 10 mexicanos sufren de gastritis crónica" description="Esta enfermedad, causada en gran parte por la bacteria Helicobacter pylori (H. pylori), puede llevar a complicaciones graves si no se trata adecuadamente." href-link="https://codigof.mx/9-de-cada-10-mexicanos-sufren-de-gastritis-cronica/" img-src="https://codigof.mx/wp-content/uploads/2024/07/9decada10mexicanossufrengastritis.jpg" />
                  <NewsCard title="¿Gastritis? Estas plantas evitan que se desarrolle, según UNAM" description="De manera común se le denomina gastritis a la enfermedad que tiene como característica la inflamación del revestimiento del estómago, la cual puede presentar síntomas que aparezcan de manera repentina o lenta que aumentan con el paso del tiempo." href-link="https://www.infobae.com/mexico/2024/05/08/gastritis-estas-plantas-evitan-que-se-desarrolle-segun-unam/" img-src="https://www.infobae.com/resizer/v2/GW24ZIZS3VBO3AXZSALAE3JGP4.jpg?auth=d8161aea1ad6041f39bd8673b0bc4eb89e60c098323e53c0333be973ee83c929&smart=true&width=992&height=558&quality=85" />
                  <NewsCard title="Combate la gastritis con 3 opciones a través de la Ayurveda" description="La gastritis es una inflamación del estómago que produce dolor y que puede venir acompañado de náuseas, vómito y diarrea ocasional." href-link="https://www.maspormas.com/opinion/combate-la-gastritis/  " img-src="https://img.maspormas.com/2023/08/Gastritis-Salud-Tips.jpg" />
                </section>
                <div class="w-full h-[1px] my-4 bg-cyan-800" />

                        <!-- Ads Section -->
        <h3 class="mt-6 text-2xl font-bold text-center text-rose-900 font-poppins">Le puede interesar</h3>
        <section  class="flex justify-center w-full my-6 space-x-4"> <!-- ads section -->
              <div
                class="relative flex items-center justify-center w-1/2 p-4 border-2 rounded-lg shadow-md border-slate-400 bg-slate-100">
                <span
                  class="absolute px-2 py-1 text-sm font-semibold text-white rounded -top-4 left-4 bg-slate-500">Anuncio</span>
                <a href="https://shykandev.github.io/medicinaparadiabetes/" class="relative w-full h-full" target="_blank"
                  rel="noopener noreferrer">
                  <div
                    class="absolute flex flex-col items-center w-full h-full transition-opacity duration-300 ease-out bg-black opacity-0 hover:opacity-70 justify-evenly">
                    <p class="text-xs font-bold text-center text-white font-poppins md:text-3xl">Jarabe o Cápsulas tu decides</p>
                    <p class="text-sm font-bold text-center text-white font-poppins md:text-3xl">100% Natural</p>
                  </div>
                  <img class="w-full h-full bg-contain rounded-md" src="https://shykandev.github.io/medicinaparahigado/assets/mainHome-BjxRmTRc.jpg" alt="">
                  <p class="absolute text-xs font-bold text-center text-white bg-red-600 top-1 font-poppins md:text-3xl">
                    ¿Problemas en el Hígado?</p>
                  <p class="absolute text-xs font-bold text-center text-white bottom-1 font-poppins md:text-3xl">
                    Conozca Livad</p>
                </a>
              </div>

              <div
                class="relative flex items-center justify-center w-1/2 p-4 border-2 rounded-lg shadow-md border-slate-400 bg-slate-100">
                <span
                  class="absolute px-2 py-1 text-sm font-semibold text-white rounded -top-4 left-4 bg-slate-500">Anuncio</span>
                <a href="https://www.prasadam.mx/typography.html" class="relative w-full h-full" target="_blank"
                  rel="noopener noreferrer">
                  <div
                    class="absolute flex flex-col items-center w-full h-full transition-opacity duration-300 ease-out bg-black opacity-0 hover:opacity-70 justify-evenly">
                    <p class="text-sm font-bold text-center text-white font-poppins md:text-3xl">100% Natural</p>
                    <!-- <p class="text-sm font-bold text-center text-white font-poppins md:text-3xl">Tu </p> -->
                    <p class="hidden text-sm font-bold text-center text-white font-poppins md:text-3xl md:block">Esta es su solución</p>
                  </div>
                  <img class="w-full h-full bg-contain rounded-md" src="https://shykandev.github.io/medicinaparadiabetes/assets/mainHome-EGZr2Qar.jpg" alt="">
                  <p class="absolute top-0 text-xs font-bold text-center text-white bg-yellow-600 font-poppins md:text-3xl">¿Tienes Diabetes?</p>
                  <p
                    class="absolute px-3 text-xs font-bold text-center text-white md:px-0 bottom-3 font-poppins md:text-3xl">
                    Le recomendamos GLUFAC</p>
                </a>
              </div>
            </section>

            <div class="flex items-center justify-center min-h-screen font-poppins">
   <div class="p-8 text-center bg-white rounded-lg shadow-lg">
    <div class="mb-4 text-green-500">
      
    </div>
    <h1 class="mb-2 text-2xl font-bold">
      Esta página es segura
    </h1>
    <v-icon name="bi-shield-lock-fill" class="text-green-500" scale="4.5"/>
    <p class="mb-4 text-gray-700">
     Esta página cuenta con HTTPS y un certificado SSL válido.
    </p>
    <h2 class="mb-2 text-xl font-semibold">
     ¿Qué es HTTPS?
    </h2>
    <p class="mb-4 text-gray-700">
     HTTPS (Hypertext Transfer Protocol Secure) es una versión segura de HTTP, el protocolo a través del cual se envían datos entre su navegador y el sitio web al que está conectado. La 'S' al final de HTTPS significa 'Seguro'. Utiliza cifrado SSL/TLS para proteger la integridad y la confidencialidad de los datos durante la transferencia.
    </p>
    <h2 class="mb-2 text-xl font-semibold">
     ¿Qué es un certificado SSL?
    </h2>
    <p class="mb-4 text-gray-700">
     SSL (Secure Sockets Layer) es una tecnología estándar de seguridad global que permite la comunicación cifrada entre un navegador web y un servidor web. Un certificado SSL es un archivo de datos que vincula una clave criptográfica a los detalles de una organización. Cuando se instala en un servidor web, activa el candado y el protocolo HTTPS, permitiendo conexiones seguras desde un servidor web a un navegador.
    </p>
    <div class="flex justify-center">
      <img class="w-36" src="https://logowik.com/content/uploads/images/ssl-secured7869.jpg" alt="">
    </div>
   </div>
  </div>
            </template>
        </MainLayout>
    </div>
</template>

<script lang="ts" setup>
import CardInfoSm from '@/components/CardInfoSm.vue';
import NewsCard from '@/components/NewsCard.vue';
import MainLayout from '@/layouts/MainLayout.vue';
import AOS from 'aos';
AOS.init();


const info1 = {  
  title: "¿Qué es CIDNI?",  
  content: "CIDNI es un suplemento 100% natural basado en la milenaria medicina ayurvédica. Su fórmula combina extractos de hierbas cuidadosamente seleccionadas, conocidas por sus propiedades digestivas y antiinflamatorias. Este suplemento está diseñado específicamente para mejorar la salud del sistema digestivo, proporcionando un alivio eficaz y duradero a quienes padecen gastritis y otros trastornos estomacales. Al integrar ingredientes naturales, CIDNI ofrece una solución segura y libre de químicos dañinos, lo que lo convierte en una opción ideal para quienes buscan tratamientos más naturales.",  
  content2: "Además de aliviar los síntomas de la gastritis, como la acidez y el dolor estomacal, CIDNI promueve un equilibrio saludable en el sistema digestivo. Esto se logra a través de la regeneración de la mucosa gástrica y el fortalecimiento del tracto digestivo. Es un producto versátil que no solo ayuda con problemas estomacales, sino que también contribuye a un bienestar integral al mejorar la absorción de nutrientes esenciales y fortalecer el sistema inmunológico."  
};

const info2 = {  
  title: "¿Cómo ayuda CIDNI a combatir la gastritis?",  
  content: "La gastritis es una inflamación de la mucosa gástrica que puede ser causada por diversos factores, como el estrés, una dieta inadecuada o la infección por Helicobacter pylori. CIDNI combate esta condición al reducir la inflamación y al regular la producción de ácido estomacal. Sus ingredientes naturales, como el Amalaki y el Yasthimadhu, tienen propiedades antiinflamatorias y protectoras que ayudan a calmar el estómago y a reparar el daño en la mucosa gástrica.",  
  content2: "Además, CIDNI actúa como un escudo protector contra irritantes comunes, ayudando a prevenir futuros episodios de gastritis. Su fórmula equilibra el pH estomacal y fomenta la regeneración de tejidos, lo que alivia el dolor y mejora la digestión en general. Con el uso regular, este suplemento no solo alivia los síntomas existentes, sino que también fortalece el sistema digestivo para resistir futuros desequilibrios."  
};

const info3 = {  
  title: "El impacto de CIDNI en tu sistema digestivo",  
  content: "El sistema digestivo es fundamental para la salud general, ya que es responsable de la absorción de nutrientes esenciales. CIDNI optimiza este proceso al mejorar la función del estómago y del intestino. Al promover una digestión más eficiente, este suplemento ayuda a descomponer los alimentos de manera más efectiva, facilitando la absorción de vitaminas y minerales. Esto es particularmente beneficioso para personas que sufren de deficiencias nutricionales debido a problemas digestivos.",  
  content2: "Además, CIDNI contribuye a mantener una flora intestinal equilibrada, un factor crucial para prevenir problemas como el estreñimiento y la diarrea. Los probióticos incluidos en su fórmula no solo mejoran la salud intestinal, sino que también fortalecen el sistema inmunológico, ayudando al cuerpo a defenderse mejor contra infecciones y enfermedades. En conjunto, CIDNI es una herramienta poderosa para mantener un sistema digestivo saludable y eficiente."  
};

const info4 = {  
  title: "El proceso ayurvédico detrás de CIDNI",  
  content: "La medicina ayurvédica es una de las prácticas curativas más antiguas del mundo, y CIDNI aprovecha sus principios para ofrecer una solución natural a los problemas digestivos. Cada ingrediente en CIDNI ha sido seleccionado por sus beneficios específicos, siguiendo un enfoque holístico que busca equilibrar los doshas (energías) del cuerpo. Esto no solo trata los síntomas de la gastritis, sino que también aborda sus causas subyacentes, como el desequilibrio en la dieta y el estrés.",  
  content2: "El proceso de formulación de CIDNI se basa en años de investigación y experiencia en la medicina ayurvédica. Las hierbas como el Chandan y el Bhringraj no solo alivian la inflamación, sino que también tienen un efecto calmante en el sistema nervioso, reduciendo el estrés y promoviendo un equilibrio general. Este enfoque integral asegura que CIDNI no solo trate los problemas digestivos inmediatos, sino que también mejore el bienestar general del usuario."  
};

const info5 = {  
  title: "¿Por qué elegir CIDNI como tu suplemento digestivo?",  
  content: "CIDNI destaca en el mercado de suplementos por su combinación única de ingredientes naturales y su enfoque integral en la salud digestiva. Mientras que otros suplementos se centran solo en aliviar síntomas temporales, CIDNI aborda tanto las causas como los efectos de los problemas digestivos, proporcionando un alivio duradero y mejorando la salud general del sistema digestivo. Su fórmula libre de químicos lo hace adecuado para personas de todas las edades.",  
  content2: "Al elegir CIDNI, también estás optando por un producto respaldado por la tradición ayurvédica y la ciencia moderna. Los ingredientes como el Guduchi y el Katuki han sido estudiados por sus beneficios en la salud gástrica, asegurando un tratamiento eficaz y seguro. Además, su enfoque natural minimiza el riesgo de efectos secundarios, lo que lo convierte en una opción confiable para el cuidado digestivo diario."  
};

const info6 = {  
  title: "La visión de CIDNI hacia la salud integral",  
  content: "CIDNI no es solo un suplemento; es un compromiso con un estilo de vida más saludable. Su formulación busca no solo aliviar los problemas digestivos, sino también mejorar el bienestar general. Esto se logra a través de un enfoque holístico que combina la curación física con el equilibrio emocional y mental. Los ingredientes ayurvédicos de CIDNI trabajan juntos para reducir la inflamación, mejorar la digestión y fortalecer el sistema inmunológico, todo mientras promueven una sensación general de bienestar.",  
  content2: "La salud integral que promueve CIDNI va más allá del estómago. Al mejorar la digestión y la absorción de nutrientes, este suplemento ayuda a aumentar los niveles de energía y a mejorar la concentración. Su acción sobre el sistema nervioso también puede reducir el estrés y mejorar la calidad del sueño, contribuyendo a una vida más equilibrada y saludable."  
};

const info7 = {  
  title: "El recorrido de CIDNI en el cuidado digestivo",  
  content: "Desde su desarrollo, CIDNI ha sido diseñado para ser una solución efectiva y natural para los problemas digestivos. Su formulación combina la sabiduría de la medicina ayurvédica con la investigación científica moderna, garantizando un producto seguro y eficaz. Cada lote de CIDNI es fabricado con los más altos estándares de calidad, asegurando que cada cápsula contenga la dosis óptima de ingredientes activos para obtener los mejores resultados.",  
  content2: "A lo largo de los años, CIDNI ha ganado la confianza de miles de usuarios que han encontrado alivio en sus propiedades curativas. Su eficacia ha sido respaldada por testimonios de personas que han experimentado mejoras significativas en su salud digestiva y bienestar general. Este suplemento sigue evolucionando, comprometido con su misión de brindar soluciones naturales y efectivas para el cuidado digestivo."  
};

</script>

<style scoped>

</style>