<template>
    <div class="">
        <MainLayout>
            <template #main>
                    <!-- <h1 class="text-3xl font-extrabold text-center text-white md:py-7 bg-cyan-600 font-poppins">Conozca los BENEFICIOS que CIDNI le ofrece para la GASTRITIS</h1> -->
                    <h1 class="py-8 text-4xl font-bold text-center rounded-lg shadow-lg text-cyan-900 bg-gradient-to-r from-cyan-100 via-white to-cyan-100 font-poppins">
  Conozca los <span class="text-cyan-600">BENEFICIOS</span> que <span class="underline decoration-cyan-600">CIDNI</span> le ofrece para la <span class="text-cyan-600">GASTRITIS</span>
</h1>

                <section class="flex flex-wrap justify-around w-full gap-4 p-3">
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/izZVsrv5vpbPHF2VBvpoAGHYDIyniTAGSGsyWTXd7abLsR8E.jpg"
                     :title="benefit1.title" :small-description="benefit1.smallIntro" :description="benefit1.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/ZutGUJeAt5RaGKlWKuWAJK45vE5fpYIe0iuICHT3QB1QjNinA.jpg"
                     :title="benefit2.title" :small-description="benefit2.smallIntro" :description="benefit2.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/cZ7HueVz54T7FaXXZgeeznmR9ISVSv4N1WiOeyodt8YDLbEPB.jpg"
                     :title="benefit3.title" :small-description="benefit3.smallIntro" :description="benefit3.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/ofqqHmJCe8nZz0RUEtZAmFJNHguF6n4Q13xP4z2n2DxL1GxTA.jpg"
                     :title="benefit4.title" :small-description="benefit4.smallIntro" :description="benefit4.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/k7nWVmluLlpFHt7D6F2BoE51dpSO6CfeDJEZCn9CF4qerNinA.jpg"
                     :title="benefit5.title" :small-description="benefit5.smallIntro" :description="benefit5.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/S4fVwnh2TA2MUqUjkRhzvgeW1fQ1hvfzXaKltVipNfqDB3IeE.jpg"
                     :title="benefit6.title" :small-description="benefit6.smallIntro" :description="benefit6.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/eHIz9ciUjExWJCglvwarezuJcFr2fsubuQl6lI8Ladk1xNinA.jpg"
                     :title="benefit7.title" :small-description="benefit7.smallIntro" :description="benefit7.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/0Gb287aJuZIiOpiqFpRZADPHNCiMrRAS9CazrxkuEah4uR8E.jpg"
                     :title="benefit8.title" :small-description="benefit8.smallIntro" :description="benefit8.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/r9zxYPHLOUKUFpcfmf59573TiyMVwAfOYLdNZUATT11X5NinA.jpg"
                     :title="benefit9.title" :small-description="benefit9.smallIntro" :description="benefit9.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/ZGHkRkJ9wB5eYSLKDsJU814r0tqrht2c1eMPkWMNf1UY6NinA.jpg"
                     :title="benefit10.title" :small-description="benefit10.smallIntro" :description="benefit10.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/DxttxgcPeiXySaiVyR5GbdJvPAsfuuigPI9eg95TQivRfbEPB.jpg"
                     :title="benefit11.title" :small-description="benefit11.smallIntro" :description="benefit11.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/wZ5i8eeNC6l4bUcUvVfRhffef6Fnf8e0dGU2MDyF7P0ZnAOinA.jpg"
                     :title="benefit12.title" :small-description="benefit12.smallIntro" :description="benefit12.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/0hXG86lmLEp4JNlUomKx9i2CswJw4ufEJ1fGuzghK7TtAHxTA.jpg"
                     :title="benefit13.title" :small-description="benefit13.smallIntro" :description="benefit13.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/F69Dqql7sipuHNBHWRPcFqvu2FjjI2nd3EfddomkOyMvgj4JA.jpg"
                     :title="benefit14.title" :small-description="benefit14.smallIntro" :description="benefit14.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/xQ44DiHaHdp3H9DbvWhjfK1oCJZzShGd6l0z7L6EeEEcCHxTA.jpg"
                     :title="benefit16.title" :small-description="benefit16.smallIntro" :description="benefit16.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/xKeHPmrxGb1MPq1fgfLh7Q1A3ktthx1NCF3isMGmVTfbNcEPB.jpg"
                     :title="benefit17.title" :small-description="benefit17.smallIntro" :description="benefit17.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/KB5IceGWsfpSZkIWqe0y2IUr0e6eT6gDkDhMqpsb2b1Vi4IeE.jpg"
                     :title="benefit18.title" :small-description="benefit18.smallIntro" :description="benefit18.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/8f0VefzljWHr4JPpXQjscRSfz1rN8c3TM2kR8RESV9jxvcEPB.jpg"
                     :title="benefit19.title" :small-description="benefit19.smallIntro" :description="benefit19.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/IIFLWY5jXBJRJx0jduZwVFpSiwteYeFlMEKXNjWMRFONMHxTA.jpg"
                     :title="benefit20.title" :small-description="benefit20.smallIntro" :description="benefit20.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/mt3qYefE1eMN4J2Fnzoq1r48hxqtjvljyX0EoxqfAsSSycEPB.jpg"
                     :title="benefit21.title" :small-description="benefit21.smallIntro" :description="benefit21.description"/>
                    <BenefictCard data-aos="flip-right" 
                    img-src="https://storage.googleapis.com/a1aa/image/6l7FfF3KyzzoUSnMEakAjoMG0RENV8acZgDkKVATBEctmj4JA.jpg"
                     :title="benefit22.title" :small-description="benefit22.smallIntro" :description="benefit22.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/dLWCaZWYCyLrIVGqFE0rumdEXL0HamBJKzYZHxIYeAqMnj4JA.jpg"
                     :title="benefit23.title" :small-description="benefit23.smallIntro" :description="benefit23.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/kFwlfvpaF22mMq2J8oLa0qdkoPHC0LhV7N66AuPgSyTdnj4JA.jpg"
                     :title="benefit24.title" :small-description="benefit24.smallIntro" :description="benefit24.description"/>
                    <BenefictCard data-aos="flip-left" 
                    img-src="https://storage.googleapis.com/a1aa/image/Mq8EBqMLfYTlACWeVugeJzNQNMHSBadPlqTXf7GIyVb6e5IeE.jpg"
                     :title="benefit25.title" :small-description="benefit25.smallIntro" :description="benefit25.description"/>
                    

                </section>
            </template>
        </MainLayout>
    </div>
</template>

<script lang="ts" setup>
import BenefictCard from '@/components/BenefictCard.vue';
import MainLayout from '@/layouts/MainLayout.vue';

const benefit1 = {
  title: "Alivio de la Inflamación de las Hemorroides",
  smallIntro: "PILOGUARD ayuda a reducir la inflamación en la zona afectada por las hemorroides.",
  description: "Uno de los principales beneficios de PILOGUARD es su capacidad para reducir la inflamación y el dolor asociado con las hemorroides. Su fórmula natural actúa suavemente sobre los tejidos inflamados, proporcionando alivio inmediato y ayudando a prevenir la inflamación recurrente. Los ingredientes como el Neem y la Cúrcuma trabajan sinérgicamente para calmar la irritación y mejorar la circulación sanguínea.",
  tags: ["salud", "hemorroides", "antiinflamatorio"]
};

const benefit2 = {
  title: "Alivio del Dolor y la Irritación",
  smallIntro: "PILOGUARD ayuda a calmar el dolor y la irritación causados por las hemorroides.",
  description: "La formulación de PILOGUARD está diseñada para proporcionar un alivio eficaz del dolor y la irritación de las hemorroides. Gracias a sus ingredientes naturales, como el Aloe vera y la Acacia catechu, este suplemento reduce el ardor, la picazón y la incomodidad, permitiendo que las personas puedan continuar con su vida diaria sin las molestias constantes.",
  tags: ["salud", "hemorroides", "alivio del dolor"]
};

const benefit3 = {
  title: "Mejora de la Circulación Sanguínea",
  smallIntro: "PILOGUARD favorece la circulación sanguínea en la región anal, esencial para prevenir las hemorroides.",
  description: "Los ingredientes naturales de PILOGUARD contribuyen a mejorar la circulación sanguínea en la zona afectada por las hemorroides. Esto no solo alivia los síntomas actuales, sino que también ayuda a prevenir futuros episodios al fortalecer los vasos sanguíneos y mejorar la elasticidad de los tejidos. Así, se reduce el riesgo de desarrollar hemorroides recurrentes.",
  tags: ["salud", "circulación", "prevención"]
};

const benefit4 = {
  title: "Prevención de Futuras Crisis de Hemorroides",
  smallIntro: "PILOGUARD ayuda a prevenir futuros episodios de hemorroides al mantener la salud digestiva y vascular.",
  description: "Con su enfoque integral, PILOGUARD no solo alivia los síntomas de las hemorroides, sino que también ayuda a prevenir futuros brotes. Gracias a sus propiedades digestivas y circulatorias, este suplemento mejora la salud intestinal y vascular, evitando factores como el estreñimiento y la mala circulación que pueden desencadenar hemorroides.",
  tags: ["prevención", "salud", "digestión"]
};

const benefit5 = {
  title: "Fortalecimiento del Sistema Digestivo",
  smallIntro: "PILOGUARD promueve un sistema digestivo saludable, lo cual es clave para evitar las hemorroides.",
  description: "Uno de los beneficios principales de PILOGUARD es su capacidad para fortalecer el sistema digestivo. Al mejorar la digestión y prevenir el estreñimiento, ayuda a evitar la presión excesiva sobre los vasos sanguíneos en la zona anal. Esto reduce las probabilidades de que se desarrollen hemorroides, promoviendo una digestión más eficiente y un tránsito intestinal regular.",
  tags: ["salud", "digestión", "prevención"]
};

const benefit6 = {
  title: "Cuidado Natural para las Hemorroides",
  smallIntro: "PILOGUARD está compuesto por ingredientes naturales que brindan un cuidado efectivo para las hemorroides.",
  description: "PILOGUARD es una alternativa natural y segura para el tratamiento de las hemorroides. Utiliza extractos de plantas ayurvédicas como el Neem y la Cúrcuma, conocidos por sus propiedades antiinflamatorias y antioxidantes. Estos ingredientes ayudan a reducir la inflamación, fortalecer las paredes de los vasos sanguíneos y promover la regeneración de los tejidos afectados.",
  tags: ["natural", "salud", "antiinflamatorio"]
};

const benefit7 = {
  title: "Mejora la Salud del Colon",
  smallIntro: "PILOGUARD apoya la salud del colon, lo cual es crucial para evitar las hemorroides.",
  description: "Los ingredientes de PILOGUARD favorecen el funcionamiento saludable del colon, aliviando el estreñimiento y reduciendo la presión sobre las venas rectales. Esto es crucial para prevenir la aparición de hemorroides y mantener un sistema digestivo óptimo. Un colon saludable facilita el proceso digestivo y reduce la inflamación en la zona anal.",
  tags: ["salud", "colon", "prevención"]
};

const benefit8 = {
  title: "Reducción del Estreñimiento",
  smallIntro: "PILOGUARD ayuda a reducir el estreñimiento, un factor clave en el desarrollo de las hemorroides.",
  description: "PILOGUARD facilita el tránsito intestinal, reduciendo el estreñimiento y el esfuerzo durante las evacuaciones. Esto disminuye la presión en la región anal y previene la aparición de hemorroides. Su fórmula natural actúa sobre el sistema digestivo para promover una digestión regular y cómoda.",
  tags: ["digestión", "estreñimiento", "salud"]
};

const benefit9 = {
  title: "Soporte para la Regeneración de Tejidos",
  smallIntro: "PILOGUARD favorece la regeneración de los tejidos dañados por las hemorroides.",
  description: "PILOGUARD contribuye a la reparación de los tejidos dañados por las hemorroides. Su combinación de ingredientes ayurvédicos acelera la cicatrización de las zonas inflamadas, reduciendo las molestias y promoviendo una recuperación más rápida. Esto es especialmente beneficioso para quienes sufren de hemorroides crónicas o recurrentes.",
  tags: ["salud", "cicatrización", "recuperación"]
};

const benefit10 = {
  title: "Mejora del Bienestar General",
  smallIntro: "PILOGUARD mejora el bienestar general al tratar las hemorroides y promover una digestión saludable.",
  description: "Además de aliviar los síntomas de las hemorroides, PILOGUARD contribuye a mejorar el bienestar general. Su acción sobre el sistema digestivo y circulatorio ayuda a reducir el malestar general y fomenta una sensación de alivio duradero. Esto mejora la calidad de vida de quienes padecen de hemorroides, permitiéndoles disfrutar de un día a día más cómodo y sin dolor.",
  tags: ["bienestar", "salud", "digestión"]
};

const benefit11 = {
  title: "Reducción de la Sensación de Ardor",
  smallIntro: "PILOGUARD ayuda a aliviar la sensación de ardor comúnmente experimentada por quienes sufren de hemorroides.",
  description: "La sensación de ardor es uno de los síntomas más molestos de las hemorroides. PILOGUARD actúa sobre la piel irritada y los tejidos afectados, calmando el ardor y la incomodidad. Sus ingredientes como la Manzanilla y el Aloe vera tienen propiedades calmantes que proporcionan un alivio inmediato, ayudando a las personas a sentirse más cómodas en su día a día.",
  tags: ["salud", "ardor", "alivio"]
};

const benefit12 = {
  title: "Fortalece las Paredes Venosas",
  smallIntro: "PILOGUARD fortalece las paredes venosas de la zona anal para prevenir complicaciones de las hemorroides.",
  description: "Las hemorroides a menudo se desarrollan debido a la debilidad de las paredes venosas en el área anal. PILOGUARD, gracias a sus componentes como el Castaño de Indias, ayuda a fortalecer estas venas, mejorando la circulación y reduciendo la probabilidad de inflamaciones futuras. Esto permite una mejor salud vascular y la prevención de complicaciones asociadas a las hemorroides.",
  tags: ["salud", "circulación", "vascular"]
};

const benefit13 = {
  title: "Alivio de la Pesadez y Fatiga",
  smallIntro: "PILOGUARD alivia la pesadez y la fatiga derivada de las hemorroides.",
  description: "Las hemorroides pueden causar una sensación de pesadez y cansancio debido a la inflamación y la irritación en la zona anal. PILOGUARD combate estos síntomas al mejorar la circulación sanguínea, reducir la inflamación y promover una digestión regular. Esto alivia la sensación de fatiga, ayudando a las personas a sentirse más ligeras y energizadas.",
  tags: ["salud", "bienestar", "fatiga"]
};

const benefit14 = {
  title: "Acción Antioxidante para la Zona Anal",
  smallIntro: "PILOGUARD actúa como un antioxidante que ayuda a proteger la zona anal de posibles daños.",
  description: "Los antioxidantes en PILOGUARD, como la Vitamina C y la Curcumina, ayudan a reducir el daño celular y a proteger la piel en la zona anal. Esto es esencial para prevenir infecciones o complicaciones que pueden surgir debido a la irritación constante de las hemorroides. Con un enfoque natural, PILOGUARD protege y regenera los tejidos afectados.",
  tags: ["salud", "antioxidantes", "protección"]
};

const benefit15 = {
  title: "Reducción de la Sensibilidad en la Zona Anal",
  smallIntro: "PILOGUARD ayuda a reducir la sensibilidad en la zona anal, lo que alivia el malestar causado por las hemorroides.",
  description: "Las hemorroides pueden hacer que la zona anal se vuelva extremadamente sensible. PILOGUARD, con ingredientes como el Aloe vera y el Aceite de Oliva, ayuda a reducir esta sensibilidad, proporcionando un alivio duradero. Su acción calmante permite que las personas puedan sentarse y moverse con mayor comodidad.",
  tags: ["salud", "sensibilidad", "alivio"]
};

const benefit16 = {
  title: "Facilita la Eliminación de Toxinas",
  smallIntro: "PILOGUARD favorece la eliminación de toxinas del cuerpo, ayudando a prevenir las hemorroides.",
  description: "El cuerpo acumula toxinas que pueden afectar la circulación y la salud intestinal, favoreciendo la aparición de hemorroides. PILOGUARD, a través de su acción depurativa, promueve la eliminación de toxinas, lo que mejora el funcionamiento general del sistema digestivo y circulatorio. Esto contribuye a prevenir futuros episodios de hemorroides al mantener el cuerpo más saludable y equilibrado.",
  tags: ["detox", "salud", "prevención"]
};

const benefit17 = {
  title: "Mejora la Elasticidad de los Tejidos",
  smallIntro: "PILOGUARD mejora la elasticidad de los tejidos de la zona anal, previniendo desgarros o daños.",
  description: "La elasticidad de los tejidos en la zona anal es fundamental para prevenir complicaciones derivadas de las hemorroides. PILOGUARD mejora esta elasticidad, permitiendo que los vasos sanguíneos se adapten mejor a los cambios de presión y reduciendo el riesgo de desgarros. Esto también contribuye a una cicatrización más rápida y eficiente en los casos de hemorroides agudas.",
  tags: ["salud", "elasticidad", "recuperación"]
};

const benefit18 = {
  title: "Ayuda en la Recuperación Postquirúrgica",
  smallIntro: "PILOGUARD apoya la recuperación después de una cirugía de hemorroides.",
  description: "Las personas que se han sometido a una cirugía para tratar las hemorroides pueden experimentar dolor e incomodidad en el proceso de recuperación. PILOGUARD ayuda a acelerar la cicatrización de los tejidos, reduce la inflamación postquirúrgica y alivia el dolor, favoreciendo una recuperación más rápida y menos dolorosa. Esto permite que los pacientes se sientan más cómodos durante su proceso de sanación.",
  tags: ["recuperación", "salud", "postquirúrgico"]
};

const benefit19 = {
  title: "Regula la Frecuencia de las Evacuaciones",
  smallIntro: "PILOGUARD ayuda a regular las evacuaciones intestinales, evitando la constipación que puede desencadenar hemorroides.",
  description: "Uno de los factores principales en el desarrollo de las hemorroides es el estreñimiento, que genera presión excesiva durante las evacuaciones. PILOGUARD mejora la regularidad del tránsito intestinal, ayudando a evitar episodios de constipación y a promover evacuaciones más suaves. Esto reduce la presión en la zona anal y previene la aparición de hemorroides.",
  tags: ["digestión", "salud", "regulación"]
};

const benefit20 = {
  title: "Promueve un Estilo de Vida Saludable",
  smallIntro: "PILOGUARD fomenta un estilo de vida saludable, aliviando y previniendo las hemorroides de manera natural.",
  description: "Más allá de aliviar los síntomas de las hemorroides, PILOGUARD contribuye a un estilo de vida saludable al mejorar la circulación, la digestión y la salud intestinal. Al incorporar PILOGUARD en tu rutina diaria, puedes reducir el riesgo de sufrir de hemorroides y mejorar tu bienestar general, promoviendo un cuerpo más equilibrado y saludable.",
  tags: ["salud", "bienestar", "prevención"]
};


const benefit21 = {
  title: "Alivio de la Inflamación",
  smallIntro: "PILOGUARD reduce la inflamación en la zona anal, proporcionando un alivio efectivo.",
  description: "La inflamación es uno de los principales síntomas de las hemorroides. PILOGUARD contiene ingredientes antiinflamatorios como la Cúrcuma, que actúan directamente sobre la zona afectada para disminuir la hinchazón y la irritación. Esto alivia el malestar y ayuda a restaurar el bienestar general de la persona.",
  tags: ["salud", "antiinflamatorio", "hemorroides"]
};

const benefit22 = {
  title: "Facilita la Cicatrización",
  smallIntro: "PILOGUARD ayuda en la cicatrización rápida de los tejidos afectados por las hemorroides.",
  description: "Gracias a su composición rica en Aloe Vera y Aceite de Coco, PILOGUARD favorece la regeneración celular y acelera la cicatrización de los tejidos dañados por las hemorroides. Esto no solo reduce el tiempo de recuperación, sino que también mejora la salud de la piel y previene nuevas lesiones.",
  tags: ["salud", "cicatrización", "recuperación"]
};

const benefit23 = {
  title: "Control del Dolor",
  smallIntro: "PILOGUARD proporciona un control efectivo del dolor causado por las hemorroides.",
  description: "El dolor es un síntoma común de las hemorroides, especialmente cuando se inflaman o se irritan. PILOGUARD actúa como un analgésico natural gracias a su contenido de ingredientes como la Manzanilla y el Aceite de Eucalipto, proporcionando alivio inmediato y reduciendo la incomodidad durante las actividades cotidianas.",
  tags: ["salud", "analgésico", "dolor"]
};

const benefit24 = {
  title: "Prevención de Recaídas",
  smallIntro: "PILOGUARD ayuda a prevenir la aparición de hemorroides recurrentes.",
  description: "Las hemorroides pueden volver a aparecer si no se toman medidas preventivas. PILOGUARD promueve la salud vascular y la circulación, evitando la congestión venosa que puede desencadenar una recaída. Su uso continuo mantiene las venas anales saludables y ayuda a prevenir futuros episodios.",
  tags: ["prevención", "salud", "circulación"]
};

const benefit25 = {
  title: "Mejora la Digestión",
  smallIntro: "PILOGUARD contribuye a una mejor digestión, lo que ayuda a reducir la presión sobre el área anal.",
  description: "Un sistema digestivo eficiente es fundamental para prevenir problemas como las hemorroides. PILOGUARD mejora la digestión gracias a ingredientes como el Jengibre y la Menta, que facilitan el tránsito intestinal y reducen el riesgo de estreñimiento. Al mejorar la digestión, PILOGUARD ayuda a aliviar la presión en la zona anal y a reducir la aparición de hemorroides.",
  tags: ["salud", "digestión", "bienestar"]
};



</script>

<style scoped>

</style>