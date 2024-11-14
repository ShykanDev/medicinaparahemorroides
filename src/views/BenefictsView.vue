<template>
    <div class="">
        <MainLayout>
            <template #main>
                    <h1 class="text-3xl font-extrabold text-center text-white md:py-7 bg-cyan-600 font-poppins">Conozca los BENEFICIOS que CIDNI le ofrece para la GASTRITIS</h1>
                <section class="flex flex-wrap justify-around w-full gap-4 p-3">
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/NTSNav0hSlq4NFRo5XUjKlMPUVLCG1ehDBF3eFkDkFR3hpwTA.jpg" :title="benefit1.title" :small-description="benefit1.smallIntro" :description="benefit1.description"/>
                    <BenefictCard img-src="https://images.pexels.com/photos/2035066/pexels-photo-2035066.jpeg?auto=compress&cs=tinysrgb&w=600" :title="benefit2.title" :small-description="benefit2.smallIntro" :description="benefit2.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/QPhqPnGmpc6zKFofmykWlEY4Tm9a2Oq7HOw89lWlbtF4xU4JA.jpg" :title="benefit3.title" :small-description="benefit3.smallIntro" :description="benefit3.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/LMkikWzCnBapM5q0gCzjjBB2gEM56cHGspuKJ6RjaysAZK8E.jpg" :title="benefit4.title" :small-description="benefit4.smallIntro" :description="benefit4.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/qwS36ByPz9YWEpA8vIs4IGqXSFgz84VYdJjXhZGnQxIKZK8E.jpg" :title="benefit5.title" :small-description="benefit5.smallIntro" :description="benefit5.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/lXcgIvAFqObLL1bLveqXT1fzPb2koBjCap7ved4R4dJfYmCPB.jpg" :title="benefit6.title" :small-description="benefit6.smallIntro" :description="benefit6.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/Pb86kFqsuMoyDplFBBiK7qFq7j44n86fXeFtRXazf2NOPThnA.jpg" :title="benefit7.title" :small-description="benefit7.smallIntro" :description="benefit7.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/ATZw5xOMlRKXARVbTzgVhgaQiJFmuZUl6bJ5e89eCoKxmpwTA.jpg" :title="benefit8.title" :small-description="benefit8.smallIntro" :description="benefit8.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/gZKLy7xF454hPd9rGCuIiwAZBBqEdymE8d3fSU5BQe0ZppwTA.jpg" :title="benefit9.title" :small-description="benefit9.smallIntro" :description="benefit9.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/gK8Wg3qxahZlKF1x8VmzlpiMkxGNGn86mmx58h6fQCJ40U4JA.jpg" :title="benefit10.title" :small-description="benefit10.smallIntro" :description="benefit10.description"/>
                    <BenefictCard img-src="https://images.unsplash.com/photo-1611566620327-5e879d9b0955?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8cmVsYXh8ZW58MHx8MHx8fDI%3D" :title="benefit11.title" :small-description="benefit11.smallIntro" :description="benefit11.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/IWK2f7nSXfhkDEThkmZCZewE2BHEMdAJ7DQWbHAGb6TrWThnA.jpg" :title="benefit12.title" :small-description="benefit12.smallIntro" :description="benefit12.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/PvYRoxemofo7sEr1FfqTBf0cfMKDEpNxOXbrOQ1gf0aqBbK8E.jpg" :title="benefit13.title" :small-description="benefit13.smallIntro" :description="benefit13.description"/>
                    <BenefictCard img-src="https://images.pexels.com/photos/3958569/pexels-photo-3958569.jpeg?auto=compress&cs=tinysrgb&w=600" :title="benefit14.title" :small-description="benefit14.smallIntro" :description="benefit14.description"/>
                    <BenefictCard img-src="https://images.pexels.com/photos/5712686/pexels-photo-5712686.jpeg?auto=compress&cs=tinysrgb&w=600" :title="benefit16.title" :small-description="benefit16.smallIntro" :description="benefit16.description"/>
                    <BenefictCard img-src="https://images.unsplash.com/photo-1543250903-0eaa21ef14b3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NDV8fGVhdGluZ3xlbnwwfHwwfHx8Mg%3D%3D" :title="benefit17.title" :small-description="benefit17.smallIntro" :description="benefit17.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/nJlpvPELco6gB5Tju4uXJ3lcvIEJLY2hZt7rNik8EEuybK8E.jpg" :title="benefit18.title" :small-description="benefit18.smallIntro" :description="benefit18.description"/>
                    <BenefictCard img-src="https://images.pexels.com/photos/8471875/pexels-photo-8471875.jpeg?auto=compress&cs=tinysrgb&w=600" :title="benefit19.title" :small-description="benefit19.smallIntro" :description="benefit19.description"/>
                    <BenefictCard img-src="https://images.pexels.com/photos/5973352/pexels-photo-5973352.jpeg?auto=compress&cs=tinysrgb&w=600" :title="benefit20.title" :small-description="benefit20.smallIntro" :description="benefit20.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/LuAMSE9jgh7AHBkutuFGPRUvAMz5C5yUxWMQxqvB8TjjcK8E.jpg" :title="benefit21.title" :small-description="benefit21.smallIntro" :description="benefit21.description"/>
                    <BenefictCard img-src="https://storage.googleapis.com/a1aa/image/t1OjSefr37qbzkZJa1Il9nvH1eByRi4gw6QRnoekxFSQKnCPB.jpg" :title="benefit22.title" :small-description="benefit22.smallIntro" :description="benefit22.description"/>
                    <BenefictCard img-src="https://images.unsplash.com/photo-1585909085111-2c2f311643af?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NjB8fGVhdGluZ3xlbnwwfHwwfHx8Mg%3D%3D" :title="benefit23.title" :small-description="benefit23.smallIntro" :description="benefit23.description"/>
                    <BenefictCard img-src="https://images.pexels.com/photos/347135/pexels-photo-347135.jpeg?auto=compress&cs=tinysrgb&w=600" :title="benefit24.title" :small-description="benefit24.smallIntro" :description="benefit24.description"/>
                    <BenefictCard img-src="https://images.pexels.com/photos/3807760/pexels-photo-3807760.jpeg?auto=compress&cs=tinysrgb&w=600" :title="benefit25.title" :small-description="benefit25.smallIntro" :description="benefit25.description"/>
                    

                </section>
            </template>
        </MainLayout>
    </div>
</template>

<script lang="ts" setup>
import BenefictCard from '@/components/BenefictCard.vue';
import MainLayout from '@/layouts/MainLayout.vue';

const benefit1 = {
  title: "Reducción del Reflujo Ácido",
  smallIntro: "CIDNI ayuda a controlar y reducir los síntomas del reflujo ácido, una de las principales molestias de la gastritis.",
  description: "Uno de los efectos más notables de CIDNI es su capacidad para reducir la acidez estomacal y el reflujo ácido. Gracias a sus ingredientes naturales, actúa suavemente sobre el sistema digestivo, proporcionando alivio a las personas que sufren de ardor estomacal y regurgitación ácida. Su fórmula herbal está diseñada para calmar la mucosa gástrica, ayudando a prevenir la irritación que desencadena el reflujo, promoviendo una digestión más saludable y menos dolorosa.",
  tags: ["salud", "digestión", "reflujo"]
};

const benefit2 = {
  title: "Mejora en la Calidad de Vida",
  smallIntro: "CIDNI contribuye a una mejor calidad de vida al reducir los malestares constantes causados por la gastritis.",
  description: "Los ingredientes naturales de CIDNI trabajan para aliviar la inflamación del estómago y la irritación gástrica. Esto permite que quienes padecen de gastritis puedan disfrutar de una vida diaria sin los síntomas dolorosos o molestos, como los gases, la acidez y la sensación de llenura. Al equilibrar el sistema digestivo, CIDNI facilita una mejor absorción de nutrientes y mejora la energía general.",
  tags: ["salud", "bienestar", "energía"]
};

const benefit3 = {
  title: "Alivio de la Irritación Gástrica",
  smallIntro: "CIDNI ayuda a calmar la irritación estomacal, promoviendo una digestión más tranquila y sin molestias.",
  description: "La fórmula única de CIDNI actúa directamente sobre la mucosa gástrica, protegiéndola y calmando la inflamación provocada por la gastritis. Al reducir la irritación, se previenen dolores y molestias, proporcionando un alivio inmediato y mejorando la función digestiva a largo plazo. Esto es crucial para aquellos que sufren de inflamación crónica del estómago.",
  tags: ["salud", "gastritis", "alivio"]
};

const benefit4 = {
  title: "Mejora la Digestión",
  smallIntro: "CIDNI promueve una digestión más eficiente y saludable, reduciendo la pesadez estomacal.",
  description: "Una de las principales ventajas de CIDNI es su capacidad para mejorar el proceso digestivo. Al aliviar la inflamación y reducir la acidez, CIDNI facilita una digestión más fluida, ayudando a prevenir la indigestión, la sensación de pesadez y la distensión abdominal. Además, sus propiedades antiinflamatorias contribuyen a un tránsito intestinal más regular.",
  tags: ["salud", "digestión", "bienestar"]
};

const benefit5 = {
  title: "Reducción de la Acidez Estomacal",
  smallIntro: "CIDNI ayuda a reducir la acidez estomacal, previniendo el dolor y la incomodidad.",
  description: "Los ingredientes naturales de CIDNI actúan regulando los niveles de acidez en el estómago. Al equilibrar el pH gástrico, ayuda a reducir el ardor y el malestar causado por el exceso de ácido, lo cual es común en personas con gastritis. Este beneficio también es ideal para quienes sufren de úlceras gástricas o reflujo ácido.",
  tags: ["digestión", "alivio", "salud"]
};

const benefit6 = {
  title: "Refuerza el Sistema Inmunológico",
  smallIntro: "CIDNI ayuda a fortalecer el sistema inmunológico, lo cual es importante para la salud digestiva general.",
  description: "Los componentes herbales de CIDNI no solo actúan sobre el sistema digestivo, sino que también tienen propiedades que fortalecen el sistema inmunológico. Esto es fundamental para prevenir infecciones o desequilibrios en el tracto digestivo, especialmente en personas propensas a la gastritis y otros trastornos digestivos.",
  tags: ["salud", "inmunidad", "digestión"]
};

const benefit7 = {
  title: "Prevención de Úlceras Gástricas",
  smallIntro: "CIDNI actúa como preventivo de úlceras gástricas, reduciendo el riesgo de complicaciones por gastritis.",
  description: "Gracias a su capacidad para calmar y proteger la mucosa gástrica, CIDNI es una excelente opción para quienes buscan prevenir las úlceras gástricas. Al reducir la inflamación y crear una barrera protectora, CIDNI ayuda a evitar el daño en el revestimiento del estómago, que es una de las principales causas de las úlceras.",
  tags: ["prevención", "gastritis", "salud"]
};

const benefit8 = {
  title: "Control del Estrés Relacionado con la Digestión",
  smallIntro: "CIDNI ayuda a controlar el estrés que afecta la salud digestiva, reduciendo sus efectos negativos.",
  description: "El estrés es uno de los principales factores que contribuye a la gastritis y otros trastornos digestivos. CIDNI ayuda a equilibrar el sistema nervioso y a reducir la ansiedad, lo que a su vez mejora la salud digestiva. Al disminuir el estrés, también se reduce la producción de ácido estomacal en exceso, aliviando el malestar.",
  tags: ["estrés", "salud", "digestión"]
};

const benefit9 = {
  title: "Alivio de la Pesadez Estomacal",
  smallIntro: "CIDNI alivia la sensación de pesadez estomacal tras las comidas, facilitando la digestión.",
  description: "Después de las comidas copiosas o ricas en grasas, muchas personas sufren de pesadez estomacal. CIDNI ayuda a reducir esta incomodidad al facilitar el proceso digestivo y aliviando la inflamación gástrica. Esto permite que la digestión se realice de forma más eficiente, evitando la sensación de hinchazón y malestar.",
  tags: ["digestión", "salud", "alivio"]
};

const benefit10 = {
  title: "Mejora la Absorción de Nutrientes",
  smallIntro: "CIDNI optimiza la absorción de nutrientes esenciales al mejorar la salud digestiva.",
  description: "Una digestión eficiente no solo reduce molestias, sino que también mejora la absorción de nutrientes esenciales. CIDNI favorece un ambiente digestivo saludable, lo que permite que el cuerpo asimile mejor las vitaminas, minerales y otros nutrientes de los alimentos. Esto contribuye a un bienestar general y a una mayor energía.",
  tags: ["nutrición", "digestión", "salud"]
};

const benefit11 = {
  title: "Propiedades Antiinflamatorias Naturales",
  smallIntro: "CIDNI cuenta con propiedades antiinflamatorias que ayudan a reducir la inflamación en el tracto digestivo.",
  description: "Los ingredientes de CIDNI tienen propiedades antiinflamatorias que son claves para aliviar los síntomas de la gastritis. Estas propiedades no solo ayudan a reducir la inflamación estomacal, sino que también contribuyen a calmar otros trastornos digestivos inflamatorios, ofreciendo un alivio duradero.",
  tags: ["antiinflamatorio", "gastritis", "salud"]
};

const benefit12 = {
  title: "Balance de los Jugos Gástricos",
  smallIntro: "CIDNI ayuda a equilibrar la producción de jugos gástricos, promoviendo un ambiente saludable en el estómago.",
  description: "Un desequilibrio en la producción de jugos gástricos puede ser la causa de la acidez y la gastritis. CIDNI ayuda a regular estos jugos gástricos, asegurando que el estómago funcione correctamente. Esta regulación favorece una digestión más eficiente y previene el exceso de ácido que causa irritación y malestar.",
  tags: ["digestión", "equilibrio", "gastritis"]
};

const benefit13 = {
  title: "Alivio de la Distensión Abdominal",
  smallIntro: "CIDNI ayuda a reducir la distensión abdominal, una molestia común en quienes sufren de gastritis.",
  description: "La distensión abdominal es una molestia frecuente entre quienes padecen de gastritis, debido a la inflamación en el estómago. CIDNI contribuye a reducir la inflamación y la acumulación de gases, proporcionando alivio a quienes experimentan esta sensación de hinchazón abdominal, promoviendo una digestión más cómoda y sin dolor.",
  tags: ["digestión", "gastritis", "alivio"]
};

const benefit14 = {
  title: "Atenúa los Cólicos Abdominales",
  smallIntro: "CIDNI alivia los cólicos abdominales causados por la irritación gástrica.",
  description: "Los cólicos abdominales son un síntoma común de la gastritis y otros trastornos digestivos. CIDNI posee propiedades que ayudan a calmar los cólicos abdominales, reduciendo el dolor y la incomodidad. Al actuar sobre la mucosa gástrica, ayuda a aliviar la tensión en el abdomen, promoviendo una sensación de bienestar.",
  tags: ["alivio", "digestión", "gastritis]"]
};
const benefit16 = {
  title: "Alivio de la Inflamación Estomacal",
  smallIntro: "CIDNI reduce la inflamación en el tracto digestivo, ofreciendo alivio para las molestias gástricas.",
  description: "El exceso de inflamación en el estómago puede causar dolor y malestar. CIDNI, gracias a sus propiedades antiinflamatorias naturales, ayuda a reducir la inflamación en el tracto digestivo. Esto contribuye a un estómago más relajado, disminuyendo la sensación de pesadez y malestar que muchas personas experimentan debido a problemas digestivos o gastritis.",
  tags: ["inflamación", "digestión", "salud"]
};

const benefit17 = {
  title: "Optimiza la Absorción de Nutrientes",
  smallIntro: "Mejora la capacidad del cuerpo para absorber nutrientes de los alimentos que consumes.",
  description: "Una digestión eficiente es clave para una absorción adecuada de los nutrientes. CIDNI apoya el proceso digestivo, optimizando la capacidad del cuerpo para absorber vitaminas, minerales y otros nutrientes esenciales de los alimentos. Esto no solo mejora la digestión, sino que también favorece una mejor nutrición y salud general.",
  tags: ["nutrición", "salud digestiva", "rendimiento"]
};

const benefit18 = {
  title: "Apoyo para el Sistema Inmunológico",
  smallIntro: "Fortalece las defensas naturales del cuerpo, ayudando a mantener el bienestar general.",
  description: "El sistema inmunológico juega un papel fundamental en la protección contra enfermedades. CIDNI contiene ingredientes naturales que fortalecen las defensas del cuerpo. Al mejorar la salud digestiva y reducir la inflamación, también se contribuye a un sistema inmunológico más fuerte, lo que te permite mantenerte saludable y protegido.",
  tags: ["inmunidad", "salud", "bienestar"]
};

const benefit19 = {
  title: "Favorece el Equilibrio del pH Estomacal",
  smallIntro: "Regula el pH del estómago, ayudando a reducir la acidez gástrica.",
  description: "El equilibrio del pH estomacal es crucial para prevenir problemas como la acidez y la indigestión. CIDNI ayuda a regular este pH, lo que reduce la acidez excesiva en el estómago. Esto proporciona un alivio efectivo para quienes sufren de reflujo ácido o ardor estomacal, mejorando la comodidad y la digestión.",
  tags: ["pH", "acidez", "salud digestiva"]
};

const benefit20 = {
  title: "Promueve la Salud Hepática",
  smallIntro: "Apoya el funcionamiento adecuado del hígado, fundamental para la detoxificación del cuerpo.",
  description: "El hígado juega un papel esencial en la eliminación de toxinas del cuerpo. CIDNI, con sus propiedades desintoxicantes naturales, apoya la función hepática, ayudando al hígado a eliminar toxinas y mejorar la salud general del sistema digestivo. Esto contribuye a un bienestar general y una mejor capacidad del cuerpo para procesar y eliminar impurezas.",
  tags: ["hígado", "detoxificación", "bienestar"]
};

const benefit21 = {
  title: "Reducción de la Fatiga Digestiva",
  smallIntro: "Reduce la sensación de cansancio que puede acompañar a problemas digestivos crónicos.",
  description: "Los trastornos digestivos a menudo se asocian con fatiga y agotamiento debido al esfuerzo que el cuerpo realiza para digerir los alimentos. CIDNI apoya una digestión más eficiente, ayudando a reducir la fatiga digestiva. Al mejorar la función digestiva y equilibrar el sistema, las personas pueden experimentar más energía y menos sensación de cansancio después de las comidas.",
  tags: ["energía", "digestión", "bienestar"]
};

const benefit22 = {
  title: "Favorece la Salud de la Microbiota Intestinal",
  smallIntro: "Promueve el crecimiento de bacterias beneficiosas en el intestino.",
  description: "La salud intestinal depende del equilibrio entre las bacterias buenas y malas en el sistema digestivo. CIDNI apoya la salud de la microbiota intestinal, favoreciendo el crecimiento de bacterias beneficiosas que promueven una digestión eficiente. Esto no solo mejora la digestión, sino que también contribuye a un sistema inmunológico más fuerte y un mejor estado de ánimo.",
  tags: ["microbiota", "digestión", "salud intestinal"]
};

const benefit23 = {
  title: "Disminuye los Dolores de Estómago Relacionados con la Gastritis",
  smallIntro: "Ayuda a aliviar el dolor y la incomodidad asociados con la gastritis.",
  description: "La gastritis puede causar dolor abdominal intenso, hinchazón y malestar general. CIDNI, con sus propiedades antiinflamatorias, reduce la inflamación en el estómago, proporcionando alivio a quienes padecen gastritis. Esto contribuye a una mayor comodidad digestiva y una reducción de los dolores asociados con esta condición.",
  tags: ["gastritis", "dolor", "bienestar"]
};

const benefit24 = {
  title: "Ayuda a Reducir los Episodios de Reflujo Ácido",
  smallIntro: "Alivia y previene el reflujo ácido, una condición común que afecta el bienestar digestivo.",
  description: "El reflujo ácido puede ser incómodo y doloroso. CIDNI ayuda a equilibrar los niveles de ácido en el estómago, previniendo el reflujo ácido y sus síntomas asociados, como la acidez estomacal y la irritación del esófago. Esto proporciona un alivio efectivo y ayuda a evitar los episodios recurrentes de reflujo.",
  tags: ["reflujo ácido", "acidez", "digestión"]
};

const benefit25 = {
  title: "Mejora la Calidad del Sueño Relacionado con la Digestión",
  smallIntro: "Mejora el sueño al aliviar los problemas digestivos que interfieren con el descanso.",
  description: "Los problemas digestivos, como la acidez o la indigestión, pueden dificultar un buen descanso nocturno. CIDNI contribuye a aliviar estos trastornos digestivos, lo que favorece un sueño más profundo y reparador. Al mejorar la función digestiva, las personas pueden disfrutar de una mejor calidad de sueño, sin interrupciones causadas por problemas estomacales.",
  tags: ["sueño", "digestión", "bienestar"]
};


</script>

<style scoped>

</style>