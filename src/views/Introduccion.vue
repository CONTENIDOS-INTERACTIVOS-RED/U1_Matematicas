<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    p.mb-5(data-aos="flip-up") La aritmética básica, es un pilar fundamental de las matemáticas y una herramienta esencial en muchos aspectos de la vida diaria y profesional. Desde realizar cálculos simples, hasta enfrentar problemas más complejos, operaciones como la suma, resta, multiplicación y división, así como sus extensiones a fracciones, decimales, porcentajes, proporciones y la regla de tres, son habilidades indispensables. Esta unidad tiene como objetivo principal, ayudar a los estudiantes a dominar estos conceptos y aplicarlos en situaciones prácticas, lo que refuerza su importancia en un mundo interconectado y orientado a la resolución de problemas.
    .row.justify-content-center(data-aos="flip-up")
      .col-sm-12.col-lg-5.d-none.d-lg-block
        img(src="@/assets/curso/intro/1.png")
      .col-sm-12.col-lg-7
          p.mb-3 La unidad #[b Aritmética básica], presenta a los estudiantes conceptos claves y técnicas prácticas que son útiles en diversas áreas como contabilidad, tecnología, gestión empresarial y logística. A medida que las sociedades dependen cada vez más de datos, cálculos y modelos matemáticos, se espera que se logre interiorizar que la aritmética básica se convierte en un recurso invaluable, para cualquier disciplina. Desde calcular presupuestos y estimar tiempos, hasta resolver problemas de proporción y escala, las habilidades aritméticas proporcionan una base sólida para enfrentar desafíos del mundo real.
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-12
              .p-4.bg-1
                .row.align-items-center
                  .col-lg-auto.d-none.d-lg-block
                    img(src="@/assets/curso/intro/2.svg", style="max-width: 90px").mx-auto
                  .col-lg
                    p.mb-0 Las matemáticas no solo son importantes para aprobar un curso, sino también para enfrentarse con confianza, a las exigencias de un mundo moderno. 
    p.mb-3(data-aos="flip-up") Por ejemplo, un analista financiero utiliza porcentajes para evaluar tasas de interés y retornos de inversión; un ingeniero de sistemas aplica proporciones para modelar sistemas escalables y, un gerente de logística usa la regla de tres para optimizar rutas de transporte. Cada uno de estos escenarios demuestra que las habilidades matemáticas básicas, son esenciales para el éxito tanto profesional como personal.
    p.mb-3(data-aos="flip-up") Esta unidad está diseñada de forma progresiva, para facilitar el aprendizaje:
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-7
        AcordionA(tipo="b")
          .div(titulo="Operaciones básicas")
            p.mb-0 Comienza con un repaso detallado de las #[b operaciones básicas] (suma, resta, multiplicación y división) y sus propiedades. 
          .div(titulo="Fracciones, decimales y porcentajes")
            p.mb-0 Luego, se introducen conceptos más avanzados como #[b fracciones, decimales y porcentajes], subrayando su aplicabilidad práctica. 
          .div(titulo="Proporciones y la regla de tres")
            p.mb-0 A continuación, se exploran las #[b proporciones y la regla de tres], demostrando cómo estas herramientas matemáticas se utilizan en la vida cotidiana. 
          .div(titulo="Ejercicios propuestos y aplicaciones")
            p.mb-0 Seguidamente, se incluyen #[b ejercicios propuestos y aplicaciones], para consolidar el aprendizaje en un contexto práctico.
      .col-sm-12.col-lg-5.d-none.d-lg-block
        img(src="@/assets/curso/intro/3.png")
    p.mb-0(data-aos="flip-up") Al finalizar esta unidad, los estudiantes serán capaces de aplicar operaciones aritméticas básicas (suma, resta, multiplicación, división) en la resolución de problemas cotidianos y académicos simples; se espera que el estudiante participe activamente en las actividades propuestas, resuelva los ejercicios planteados y se involucre en discusiones virtuales, para reforzar sus conocimientos. Es recomendable tener nociones básicas de matemáticas y un enfoque proactivo hacia el aprendizaje. ¡Bienvenidos!



</template>

<script>
import BannerInterno from '../components/plantilla/BannerInterno'
import Muestras from '../components/muestras/Muestras.vue'

export default {
  name: 'Introduccion',
  components: {
    BannerInterno,
    Muestras,
  },
  data: () => ({
    globalData: global,
  }),
}
</script>

<style lang="sass"></style>
