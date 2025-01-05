<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Aplicación de la aritmética en la vida diaria: proporciones y reglas de tres, simples'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-3(data-aos="flip-up") Las proporciones y reglas de tres, son herramientas matemáticas que permitirán resolver problemas de escalamiento y relaciones entre cantidades, en diversos entornos profesionales. Estas técnicas son fundamentales para realizar estimaciones, proyecciones y cálculos comparativos, siendo especialmente útiles cuando se necesita determinar valores desconocidos a partir de relaciones conocidas.
    .bg-5.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center
        .col-lg
          .p-4
            p.mb-0 Parra y Saiz (2007) enfatizan la aplicación de las proporciones en la resolución de problemas empresariales. Andonegui Zabala (2007) destaca su importancia en el análisis de datos comerciales, mientras que Ortiz Ceredo (2018), señala su utilidad en la planificación y gestión de recursos.
        .col-lg-auto.d-none.d-lg-block
            img(src='@/assets/curso/t3/1.png', alt='')
            

    #t_3_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.1] Proporciones
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-12
        .bg-1.p-4
          p.mb-4 Una proporción es una igualdad entre dos razones, donde una razón es el cociente de dos cantidades comparables.

          h4.mb-3 Una proporción se expresa como:
          p.mb-3.ml-1 a/b = c/d
          
          h4.mb-3 Donde:
          ul.mb-3
            li • a y c son antecedentes
            li • b y d son consecuentes
            li • Se lee: "a es a b, como c es a d"

      
          h4.mb-3 Ejemplo:
          p.mb-2.ml-1 2/3 = 8/12
          p.ml-1 "2 es a 3, como 8 es a 12"
    h3.mb-5(data-aos="flip-up") Propiedades de las proporciones
    .bg-full-width.bg-fondo-2.mb-5(data-aos="flip-up")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Propiedad fundamental
              p En toda proporción, el producto de medios, es igual al producto de extremos.
              p Si a/b = c/d, entonces a×d = b×c
              p #[b Ejemplo:] 2/3 = 8/12
            .col-lg-5.d-none.d-lg-block
              img(src='@/assets/curso/t3/2.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Propiedades derivadas
              p Si a/b = c/d, entonces a/c = b/d
              p #[b Ejemplo:] 3/4 = 9/12
              p #[b Por tanto:] 3/9 = 4/12
            .col-lg-5.d-none.d-lg-block
              img(src='@/assets/curso/t3/3.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Propiedad inversa
              p Si a/b = c/d, entonces b/a = d/c
              p #[b Ejemplo:] 2/5 = 4/10
              p #[b Por tanto:] 5/2 = 10/4
            .col-lg-5.d-none.d-lg-block
              img(src='@/assets/curso/t3/4.png', alt='')


    h3.mb-5(data-aos="flip-up") Tipos de proporcionalidad
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-5.d-none.d-lg-block
        img(src="@/assets/curso/t3/5.png")
      .col-sm-12.col-lg-7
        AcordionA(tipo="b")
          .div(titulo="Directa")
            p.mb-4 Cuando una magnitud aumenta/disminuye en la misma proporción que otra.
            p.mb-0.fw-bold Características:
            ul.mb-3
              li - y = kx (k es constante).
              li - La razón y/x es constante.
              li - Sus gráficas son líneas rectas.
            p.mb-0.fw-bold Ejemplo:
            p.mb-0.fw-bold Velocidad constante:
            p.mb-0 Tiempo (h) | Distancia (km)
            p.mb-1 1 | 60
            p.mb-1 2 | 120
            p.mb-1 3 | 180
            p k = 60 km/h (constante)

          .div(titulo="Inversa")
            p.mb-4 Cuando una magnitud aumenta en la misma proporción que otra disminuye.
            p.mb-0.fw-bold Características:
            ul.mb-3
              li - x×y = k (k es constante).
              li - El producto x×y es constante.
              li - Sus gráficas son hipérbolas.
            p.mb-0.fw-bold Ejemplo:
            p.mb-0.fw-bold Trabajo constante:
            p.mb-0 Operarios | Tiempo (h)
            p.mb-0 2 | 12
            p.mb-0 3 | 8
            p.mb-0 4 | 6
            p.mb-0 k = 24 horas-operario (constante)

          .div(titulo="Series proporcionales")
            p.mb-0.fw-bold Serie de razones iguales:
            p.mb-3 a₁/b₁ = a₂/b₂ = a₃/b₃ = ... = k
            p.mb-0.fw-bold Ejemplo:
            p.mb-0 2/6 = 3/9 = 4/12 = 1/3

          .div(titulo="Proporcionalidad compuesta")
            p.mb-0 Combina proporcionalidad directa e inversa:
            p.mb-3 y = k × (x₁×x₂)/(x₃×x₄)
            p.mb-0.fw-bold Ejemplo:
            p.mb-0.fw-bold Productividad:
            p.mb-0 (operarios × horas)/(área × dificultad)

    h3.mb-5(data-aos="flip-up") Aplicaciones de las proporciones
    .row.justify-content-center.align-items-start.mb-0(data-aos="flip-up")
      .col-sm-12.col-lg-6
        .bg-color-white.shadow-soft.py-4.px-lg-5.h-card-1
          .row.justify-content-around.align-items-start
            .col-md-auto.d-none.d-lg-block
              img(src="@/assets/curso/t3/6.svg")
            .col
              p.fw-bold En producción
              p.mb-0.fw-bold Rendimiento:
              p.mb-0 8 operarios → 400 unidades
              p.mb-4 12 operarios → 600 unidades

              p.mb-0.fw-bold Productividad:
              p.mb-0 3 máquinas → 150 piezas/hora
              p.mb-0 5 máquinas → 250 piezas/hora
      .col-sm-12.col-lg-6
        .bg-color-white.shadow-soft.py-4.px-lg-5.h-card-1
          .row.justify-content-around.align-items-start
            .col-md-auto.d-none.d-lg-block
              img(src="@/assets/curso/t3/7.svg")
            .col
              p.fw-bold En finanzas
              p.mb-0.fw-bold Rentabilidad:
              p.mb-0 $1000 → $120 beneficio
              p.mb-4 $2500 → $300 beneficio

              p.mb-0.fw-bold Distribución:
              p.mb-0 Inversión: beneficio
              p.mb-0 5000: 750
              p.mb-0 8000: 1200
    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Importancia de las proporciones matemáticas
            p.mb-4 Las proporciones matemáticas son herramientas fundamentales que permiten establecer relaciones entre magnitudes, facilitando la resolución de problemas en múltiples ámbitos. El PDF #[b Importancia de las proporciones matemáticas], analiza su importancia en áreas como tecnología, finanzas, logística, salud y educación, mostrando cómo su aplicación optimiza procesos, mejora la toma de decisiones y garantiza precisión en cálculos complejos. A través de ejemplos prácticos, se demuestra su relevancia tanto en la vida cotidiana como en contextos profesionales.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Importancia_proporciones_matematicas.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Importancia de las proporciones matemáticas

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t3/8.png', alt='') 

    #t_3_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.2] Reglas de tres
    .bg-8.p-4.mb-5(data-aos="flip-up")
      .row.justify-content-center.mb-0
        .col-sm-12.col-lg-7
            p.mb-4 La regla de tres es un método para resolver problemas de proporcionalidad, encontrando un valor desconocido, a partir de tres valores conocidos.

            p.mb-0.fw-bold Estructura básica:
            p.mb-0 A → B
            p.mb-4 C → x

            p.mb-0.fw-bold Donde:
            p.mb-0 - A y B son valores relacionados conocidos.
            p.mb-0 - C es un nuevo valor de A.
            p.mb-0 - x es el valor desconocido de B.

        .col-lg-5.d-none.d-lg-block
          img(src="@/assets/curso/t3/9.png")
    h3.mb-3(data-aos="flip-up") Propiedades de la regla de tres
    p.fw-bold(data-aos="flip-up") Tipos de proporción, según su relación
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-5
        .bg-6.p-4.h-card-2
          p.fw-bold Directa
          p.mb-0 Si A → B
          p.mb-0 C → x
          p.mb-4 Entonces: x = (B×C) / A

          p.mb-0.fw-bold Ejemplo:
          p.mb-0 3 kg → $15
          p.mb-0 8 kg → x
          p.mb-0 x = ($15×8) / 3 = $40
      .col-sm-12.col-lg-5
        .bg-7.p-4.h-card-2
          p.fw-bold Inversa
          p.mb-0 Si A → B
          p.mb-0 C → x
          p.mb-4 Entonces: x = (A×B) / C

          p.mb-0.fw-bold Ejemplo:
          p.mb-0 2 días → 6 operarios
          p.mb-0 3 días → x operarios
          p.mb-0 x = (2×6) / 3 = 4 operarios

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-10
        .row.align-items-start.bg-8.p-4
          .col-lg-auto.d-none.d-lg-block
            img(src="@/assets/curso/t3/10.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.fw-bold Regla de Tres Compuesta
            p Con variables directas e inversas

            p.mb-0.fw-bold Fórmula general:
            p.mb-4 x = (B × variables directas) / (A × variables inversas)

            p.mb-0.fw-bold Ejemplo:
            p.mb-0 6 operarios en 8 horas producen 480 unidades
            p.mb-0 ¿Cuántas unidades producirán 9 operarios en 6 horas?
            p.mb-0 Operarios: directa (×9/6)
            p.mb-0 Horas: directa (×6/8)
            p.mb-0 x = 480 × (9/6) × (6/8) = 540 unidades

    h3.mb-5(data-aos="flip-up") Método de proporciones
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src="@/assets/curso/t3/11.png")
      .col-sm-12.col-lg-6
        p.mb-0.fw-bold Para cada variable:
        p.mb-0 - Si es directa: a/b = c/d
        p.mb-4 - Si es inversa: a/b = d/c

        p.mb-0.fw-bold Ejemplo:
        p.mb-0 4 máquinas en 6 días producen 720 unidades.
        p.mb-0 ¿Cuántos días necesitan 3 máquinas para 900 unidades?
        p.mb-0 Máquinas (inversa): 4/3 = x/6
        p.mb-0 Unidades (directa): 720/900 = 6/x
        p.mb-0 x = (4×6×900) / (3×720) = 10 días

    h3.mb-5(data-aos="flip-up") Casos especiales de proporciones
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-5
        .bg-6.p-4.h-card-2
          p.fw-bold Con porcentajes
          p.mb-0.fw-bold Regla de tres para calcular porcentajes:
          p.mb-0 100 % → Total
          p.mb-4 X %     → Parte

          p.mb-0.fw-bold Ejemplo:
          p.mb-0 100 % → 250 unidades
          p.mb-0 40 %   → x unidades
          p.mb-0 x = (250×40) / 100 = 100 unidades
      .col-sm-12.col-lg-5
        .bg-7.p-4.h-card-2
          p.fw-bold Con escalas
          p.mb-0 Escala 1:100
          p.mb-0 Real → Plano
          p.mb-0 1 m  → 1 cm
          p.mb-0 x m  → 25 cm
          p.mb-0 x = 25×1/1 = 25 metros

    h3.mb-5(data-aos="flip-up") Aplicaciones de la regla de tres
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-8
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/t3/12.svg')
          .tarjeta.color-adicional-2.p-3(x="15.5%" y="71.7%" numero="")
            p.fw-bold.mb-0 Rendimiento:
            p.mb-0 5 máquinas → 200 unidades/hora
            p.mb-0 8 máquinas → x unidades/hora
            p.mb-4 x = (200×8)/5 = 320 unidades/hora

            p.mb-0.fw-bold Planificación:
            p.mb-0 3 operarios → 24 horas
            p.mb-0 6 operarios → x horas
            p.mb-0 x = (3×24)/6 = 12 horas

          .tarjeta.color-adicional-2.p-3(x="50%" y="71.7%" numero="")
            p.fw-bold.mb-0 Precios y descuentos:
            p.mb-0 Precio normal: $100 → 0 % descuento
            p.mb-0 Precio final: x → 20 % descuento
            p.mb-4 x = $100 - ($100×20)/100 = $80

            p.mb-0.fw-bold Conversiones:
            p.mb-0 1 dólar → 20 pesos
            p.mb-0 50 dólares → x pesos
            p.mb-0 x = 50×20 = 1000 pesos
          .tarjeta.color-adicional-2.p-3(x="84.5%" y="71.7%" numero="")
            p.fw-bold.mb-0 Material necesario:
            p.mb-0 100 m² → 300 ladrillos
            p.mb-0 150 m² → x ladrillos
            p.mb-4 x = (300×150)/100 = 450 ladrillos

            p.mb-0.fw-bold Tiempo de obra:
            p.mb-0 10 obreros → 45 días
            p.mb-0 15 obreros → x días
            p.mb-4 x = (10×45)/15 = 30 días

    .bg-5.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center
        .col-lg
          .p-4
            p.mb-0 En el sector social, estas herramientas son cruciales para la planificación y distribución de recursos. Por ejemplo, en la gestión de programas sociales, necesitará calcular la distribución de ayudas, según la población beneficiaria, estimar recursos necesarios, según la cobertura deseada, y proyectar impactos basados en datos piloto. En el sector industrial, estas técnicas son esenciales para el escalamiento de procesos, la planificación de producción y la optimización de recursos.
        .col-lg-auto.d-none.d-lg-block
            img(src='@/assets/curso/t3/13.png', alt='')

    p.mb-4 Resolvamos tres ejercicios prácticos de cada tipo: 
    .bg-full-width.bg-fondo-2.mb-5(data-aos="flip-up")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Regla de tres directa, en producción: 
              p.mb-0 #[b 1.] Si 15 máquinas producen 300 unidades, ¿cuántas para 2000 unidades? Solución: 15 → 300, x → 2000; x = (15 × 2000) ÷ 300 = 100 máquinas. 
              p.mb-0 #[b 2.] Si 20 operarios procesan 5000 pedidos, ¿cuántos para 15000? Solución: x = (20 × 15000) ÷ 5000 = 60 operarios. 
              p.mb-0 #[b 3.] Si 8 líneas producen 400 unidades/hora, ¿cuántas para 1000? Solución: x = (8 × 1000) ÷ 400 = 20 líneas. 
            .col-lg-5.d-none.d-lg-block
                img(src="@/assets/curso/t3/14.png")
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Regla de tres, inversa en tiempo: 
              p.mb-0 #[b 1.] Si 8 técnicos tardan 6 horas, ¿cuánto tardarán 6 técnicos? Solución: 8 × 6 = 48 horas-técnico; 48 ÷ 6 = 8 horas. 
              p.mb-0 #[b 2.] Si 12 equipos tardan 4 horas, ¿cuánto tardarán 6? Solución: 12 × 4 = 48; 48 ÷ 6 = 8 horas. 
              p.mb-0 #[b 3.] Si 15 operarios tardan 3 horas, ¿cuánto tardarán 5? Solución: 15 × 3 = 45; 45 ÷ 5 = 9 horas. 
            .col-lg-5.d-none.d-lg-block
                img(src="@/assets/curso/t3/15.png")
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Regla de tres compuesta, en producción:
              p.mb-0 #[b 1.] Si 6 máquinas en 8 horas producen 480 unidades, ¿cuánto producirán 9 máquinas en 6 horas? Solución: (9 × 6 × 480) ÷ (6 × 8) = 540 unidades. 
              p.mb-0 #[b 2.] Si 4 equipos en 5 horas procesan 200 pedidos, ¿cuánto procesarán 6 equipos en 8 horas? Solución: (6 × 8 × 200) ÷ (4 × 5) = 480 pedidos. 
              p.mb-0 #[b 3.] Si 3 líneas en 4 días producen 360 lotes, ¿cuántos producirán 5 líneas en 6 días? Solución: (5 × 6 × 360) ÷ (3 × 4) = 900 lotes. 
            .col-lg-5.d-none.d-lg-block
                img(src="@/assets/curso/t3/16.png")


    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t3/17.png', alt='') 
          .col-lg-7
            h2.mb-4 Importancia de la regla de tres
            p.mb-4 La regla de tres es una herramienta matemática indispensable que simplifica la resolución de problemas de proporcionalidad, encontrando aplicaciones prácticas en diversas áreas. El PDF #[b Importancia de la regla de tres], explora cómo su uso optimiza procesos en sectores como sistemas informáticos, finanzas, logística, gestión humana y educación. Su versatilidad y facilidad de aplicación la convierten en una técnica clave, para tomar decisiones informadas y resolver situaciones cotidianas y profesionales con eficiencia y precisión.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Importancia_regla_tres.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Importancia de la regla de tres

    h3.mb-3(data-aos="flip-up") Ventajas de la regla de tres:
    ul.lista-ul--color.mb-5(data-aos="flip-up")
      li
        i.fas.fa-circle.icon-list
        |  Simplicidad: no requiere conocimientos avanzados, lo que la hace accesible para cualquier persona.
      li
        i.fas.fa-circle.icon-list
        | Aplicabilidad: funciona en cualquier contexto que involucre relaciones proporcionales.
      li
        i.fas.fa-circle.icon-list
        | Eficiencia: reduce el tiempo necesario para resolver problemas cotidianos y profesionales.

    .row.align-items-center.bg-1.p-4.mb-5(data-aos="flip-up")
        .col-lg-auto.d-none.d-lg-block
          img(src="@/assets/curso/t3/19.svg", style="max-width: 90px").mx-auto
        .col-lg
          p.mb-0 La regla de tres sigue siendo una herramienta esencial en el mundo moderno. Su capacidad para simplificar cálculos y adaptarse a diversos contextos, la convierte en un recurso valioso tanto en la vida cotidiana como en sectores profesionales claves.

    .bg-full-width.border-top.color-primario.mb-0
      .p-4.p-md-5
        h2 MATERIAL COMPLEMENTARIO
        .row.material-complem
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
            //- Referencia con enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/book.svg' :style='{"max-width":"16px"}')
              a(href='https://elibro.net/en/ereader/tecnologicodeloriente/40539?page=6' target='_blank' rel='noopener noreferrer') Ortiz Ceredo, F. J. (2018). Matemáticas 3 (2 ed.). Grupo Editorial Patria.
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style='{"max-width":"16px"}')
              a(href='https://matematix.org/ ' target='_blank' rel='noopener noreferrer') https://matematix.org/ 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style='{"max-width":"16px"}')
              a(href='https://es.khanacademy.org/math' target='_blank' rel='noopener noreferrer') Cursos matemáticos por área.
            
            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style='{"max-width":"16px"}')
              a(href='https://youtu.be/ro-fpmydR4s?si=iA9ZiEinq1Nlxp6h' target='_blank' rel='noopener noreferrer') Épsilon Akdemy. (2019). Aritmética: FRACCIONES y OPERACIONES
          
          .col-12.col-md-6.col-lg-3.offset-lg-1.d-none.d-lg-block
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

    .bg-full-width.border-top.actividad.ctn-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    


</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema3',
  components: {
    BannerInterno,
  },
  data: () => ({
    cuestionario: {
      tema: 'Sistemas numéricos y álgebra de Boole',
      titulo: 'Ponte a prueba',
      introduccion:
        'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
      barajarPreguntas: true,
      preguntas: [
        {
          id: 1,
          texto: 'La aritmética básica se define principalmente como:',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Un conjunto de números',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El fundamento del pensamiento matemático y cuantitativo',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Una serie de símbolos',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Un método de conteo simple',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente! La aritmética básica es el fundamento esencial de todo pensamiento matemático y cuantitativo.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto: 'La propiedad conmutativa de la suma establece que:',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El resultado siempre es positivo',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El orden de los sumandos no altera el resultado',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'La suma con cero da el mismo número',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Los números se pueden agrupar de cualquier forma',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! La propiedad conmutativa permite cambiar el orden de los sumandos sin afectar el resultado.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: 'Para sumar fracciones con diferente denominador, se debe:',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Sumar numeradores y denominadores',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Encontrar un denominador común',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Multiplicar las fracciones',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Dividir los numeradores',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Perfecto! El denominador común es necesario para sumar fracciones correctamente.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto: 'Al multiplicar 234 por 56, el proceso correcto es:',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Sumar 234 cincuenta y seis veces',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Multiplicar por 6 y luego por 50, sumando resultados',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Multiplicar solo los dígitos iguales',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Dividir 234 entre 56',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente! Este método descompone la multiplicación en pasos más sencillos.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: 'Una fracción propia es aquella donde:',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El numerador es mayor que el denominador',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El numerador es menor que el denominador',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Numerador y denominador son iguales',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'El denominador es cero',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Las fracciones propias representan partes de una unidad.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Felicidades! Has superado la prueba con éxito.',
      mensaje_final_reprobado:
        'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
    },
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.material-complementario
  padding-top: 3rem
  border-top: 9px solid $color-sistema-e
</style>
