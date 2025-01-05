<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Fracciones, decimales y porcentajes'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-7
        p.mb-3 Las fracciones, decimales y porcentajes, son representaciones numéricas que le permitirán expresar proporciones, partes de un todo y relaciones entre cantidades en diversos contextos profesionales. Estas tres formas de expresión están interrelacionadas y le ofrecerán la flexibilidad necesaria para presentar y analizar datos, según los requerimientos específicos de cada sector o situación.
        .bg-1.p-4
          p.mb-0 Parra y Saiz (2007), resaltan la importancia de comprender estas diferentes representaciones numéricas como herramientas complementarias en el análisis cuantitativo. Andonegui Zabala (2007), destaca su aplicación en el análisis de datos empresariales, mientras que Ortiz Ceredo (2018), enfatiza su uso en la toma de decisiones comerciales y financieras.
      .col-sm-12.col-lg-5.d-none.d-lg-block
        img(src='@/assets/curso/t2/1.png', alt='')

    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t2/2.png', alt='') 
          .col-lg-7
            h2.mb-4 Fracciones
            p.mb-4 Las fracciones son un concepto fundamental en matemáticas, utilizadas para representar partes de un todo y realizar operaciones esenciales en diversas aplicaciones prácticas. El PDF #[b Fracciones], explora su estructura, propiedades, operaciones y aplicaciones, destacando ejemplos concretos en áreas como mediciones y finanzas. Comprender las fracciones permite simplificar cálculos, comparar cantidades y resolver problemas cotidianos, consolidando su importancia en contextos académicos y profesionales.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/fracciones.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Fracciones

          

    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Decimales
            p.mb-4 Los números decimales son una herramienta esencial en el mundo moderno, proporcionando precisión y claridad en cálculos que abarcan desde mediciones hasta transacciones financieras. El PDF #[b Decimales], aborda su estructura, propiedades, operaciones y aplicaciones prácticas en áreas como ciencia, logística y programación. Comprender y manejar los números decimales permite resolver problemas con exactitud, destacando su relevancia en la toma de decisiones informadas en diversos contextos cotidianos y profesionales.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/decimales.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Decimales

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t2/3.png', alt='') 


    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t2/4.png', alt='') 
          .col-lg-7
            h2.mb-4 Porcentajes
            p.mb-4 Los números decimales son una herramienta esencial en el mundo moderno, proporcionando precisión y claridad en cálculos que abarcan desde mediciones hasta transacciones financieras. El PDF #[b Porcentajes], aborda su estructura, propiedades, operaciones y aplicaciones prácticas en áreas como ciencia, logística y programación. Comprender y manejar los números decimales, permite resolver problemas con exactitud, destacando su relevancia en la toma de decisiones informadas en diversos contextos cotidianos y profesionales.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/porcentajes.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Porcentajes


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2 MATERIAL COMPLEMENTARIO
        .row.material-complem
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
            //- Referencia con enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/book.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/en/ereader/tecnologicadeloriente/94592?page=29" target="_blank" rel="noopener noreferrer") Andonegui Zabala, M. (2007). El sistema numérico decima. Corporación Andina de Fomento.
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.lifeder.com/ " target="_blank" rel="noopener noreferrer") https://www.lifeder.com/ 
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://es.symbolab.com/solver/basic-operations-calculator" target="_blank" rel="noopener noreferrer") Solucionador matemático de IA > Calculadora de operaciones básicas.
            
            
            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/playlist?list=PLWyONXRtuelT7e2waz4vGaYlc_Hi3YpYG" target="_blank" rel="noopener noreferrer") Ayala, M. (s.f.). Curso de fundamentos matemáticos (playlist)
            
            
          .col-12.col-md-6.col-lg-3.offset-lg-1.d-none.d-lg-block
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')












</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema2',
  components: {
    BannerInterno,
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
