<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Aritmética básica'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
    p.mb-5(data-aos="flip-up") Al comenzar su estudio de la aritmética básica, se encontrará con las herramientas esenciales que le ayudarán a desarrollarse profesionalmente, en diversos sectores productivos. La aritmética es la base sobre la que construirá su capacidad de análisis numérico y toma de decisiones, en entornos empresariales e industriales. Esta rama de las matemáticas le dotará de las habilidades necesarias para resolver problemas prácticos en diferentes contextos laborales, desde la gestión comercial, hasta la optimización de procesos industriales.
    .bg-2.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.d-none.d-lg-block
            img(src='@/assets/curso/t1/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0 La #[b aritmética básica] es el fundamento clave de todo el pensamiento matemático y cuantitativo. Su relevancia va más allá del ámbito académico, convirtiéndose en una herramienta esencial para el desarrollo profesional en cualquier sector productivo. Esta unidad explora los conceptos fundamentales de la aritmética, sus aplicaciones prácticas y su importancia en el contexto profesional actual.

    #t_1_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.1] Operaciones básicas: suma, resta, multiplicación y división    
    .bg-full-width.bg-fondo-1.mb-5(data-aos="flip-up")
      .p-4.p-md-5
        p.mb-5 Las operaciones básicas son la base de todo cálculo matemático que realizará en su vida profesional:
        .row.justify-content-center.mb-5
          .col-sm-12.col-lg-8
            SlyderF(columnas="col-12 col-lg-6")
              .row.py-4.px-3.h-100
                .col-10.offset-1.offset-md-0.col-md-12.shadow-app.p-3.py-md-5.px-md-4.bg-color-white
                  .row.justify-content-center
                    .col-6.col-md-4.mb-4
                      img(src='@/assets/curso/t1/3.svg')
                    h4.text-center Suma
                    p.mb-0.text-center La #[b suma] le ayudará a totalizar valores. 
              .row.py-4.px-3.h-100
                .col-10.offset-1.offset-md-0.col-md-12.shadow-app.p-3.py-md-5.px-md-4.bg-color-white
                  .row.justify-content-center
                    .col-6.col-md-4.mb-4
                      img(src='@/assets/curso/t1/4.svg')
                    h4.text-center Resta
                    p.mb-0.text-center La #[b resta] le ayudará a determinar diferencias y variaciones. 


              .row.py-4.px-3.h-100
                .col-10.offset-1.offset-md-0.col-md-12.shadow-app.p-3.py-md-5.px-md-4.bg-color-white
                  .row.justify-content-center
                    .col-6.col-md-4.mb-4
                      img(src='@/assets/curso/t1/5.svg')
                    h4.text-center Multiplicación
                    p.mb-0.text-center La #[b multiplicación] le ayudará a calcular productos y áreas.


              .row.py-4.px-3.h-100
                .col-10.offset-1.offset-md-0.col-md-12.shadow-app.p-3.py-md-5.px-md-4.bg-color-white
                  .row.justify-content-center
                    .col-6.col-md-4.mb-4
                      img(src='@/assets/curso/t1/6.svg')
                    h4.text-center División
                    p.mb-0.text-center La #[b división] le ayudará a distribuir recursos o establecer proporciones. 

          .col-sm-12.col-lg-4.d-none.d-lg-block.mb-0
              img(src='@/assets/curso/t1/2.png', alt='Texto que describa la imagen')

    .bg-1.p-4.mb-5(data-aos="flip-up")
      p.mb-0 Dominar estas operaciones es crucial para desarrollar análisis más complejos y tomar decisiones fundamentadas en datos cuantitativos.
    p.mb-5(data-aos="flip-up") Parra y Saiz (2007), enfatizan la importancia de comprender las operaciones básicas como procesos interrelacionados, que forman la base del pensamiento matemático. Andonegui Zabala (2007) destaca cómo el sistema decimal facilita las operaciones en contextos prácticos, mientras que Ortiz Ceredo (2018), subraya la necesidad de dominar estas operaciones para el análisis de datos en entornos profesionales.
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-8
        .row.justify-content-center.align-items-center.mb-0
          .col-sm-12.col-lg-12
            .bg-color-white.shadow-soft.p-4
              .row.justify-content-around.align-items-center
                .col-md-auto.d-none.d-lg-block
                  img(src="@/assets/template/bg-icono-video.svg", style="width: 60px;")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-0
                      h3.mb-1 Para reforzar los conceptos generales sobre matemáticas y aprender a realizar operaciones básicas como la suma, resta, multiplicación y división, le invitamos a ver el siguiente video:
                      p.mb-0.mb-cus Ayala, M. (s. f.). Curso de fundamentos matemáticos [Video]. YouTube.
                    .col-sm-auto
                      a.boton.color-adicional-1.texto-blanco(href='https://www.youtube.com/playlist?list=PLWyONXRtuelT7e2waz4vGaYlc_Hi3YpYG' target="_blank")
                        span Ver video
                        i.fas.fa-arrow-right


    p.mb-3(data-aos="flip-up") A continuación, se darán a conocer algunas importancias generales de las operaciones matemáticas básicas, en el contexto profesional.
    .bg-full-width.bg-fondo-2.mb-5(data-aos="flip-up")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Toma de decisiones
              p La aritmética ofrece las herramientas básicas para el análisis cuantitativo, necesario en la toma de decisiones empresariales.
            .col-lg-5.d-none.d-lg-block
                img(src="@/assets/curso/t1/30.png")
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Optimización de recursos
              p Permite realizar cálculos precisos para la distribución y uso eficiente de recursos.
            .col-lg-5.d-none.d-lg-block
                img(src="@/assets/curso/t1/8.png")

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Análisis de datos
              p Facilita la interpretación y manipulación de datos numéricos, en entornos profesionales.
            .col-lg-5.d-none.d-lg-block
                img(src="@/assets/curso/t1/9.png")

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Gestión financiera
              p Es fundamental para comprender y gestionar las finanzas, adecuadamente.
            .col-lg-5.d-none.d-lg-block
                img(src="@/assets/curso/t1/11.png")


    p.mb-5(data-aos="flip-up") Las operaciones básicas son transformaciones que realizamos sobre los números, para obtener nuevos valores. Cada operación tiene su propia naturaleza y significado.
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-8
        .row.justify-content-center.align-items-center.mb-0
          .col-sm-12.col-lg-12
            .bg-color-white.shadow-soft.py-4.px-lg-5
              .row.justify-content-around.align-items-center
                .col-md-auto.d-none.d-lg-block
                  img(src="@/assets/template/bg-icono-video.svg", style="width: 60px;")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-0.mb-sm-0
                      h3.mb-1 Para reforzar los conceptos básicos de operaciones matemáticas, le invitamos a ver el siguiente video: 
                      p.mb-0.mb-cus Gómez Moya, S. (s. f.). Operaciones aritméticas [Video]. YouTube.
                    .col-sm-auto
                      a.boton.color-adicional-1.texto-blanco(href='https://www.youtube.com/watch?v=Ucox4j4w-gY' target="_blank")
                        span Ver video
                        i.fas.fa-arrow-right


    h3.mb-3(data-aos="flip-up") Suma
    .bg-1.p-4.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center.mb-0
        .col-sm-12.col-lg-6
          p.mb-3 La suma es una operación matemática que combina dos o más cantidades en una sola, representando la unión o adición de elementos.
          p La suma se realiza combinando unidades del mismo orden posicional:
          h5 Proceso:
          .row.justify-content-center.mb-5
            .col-sm-12.col-lg-2
              p.mb-2 2 , 3 4 5
              p.mb-2 1 , 2 3 4
              p.mb-2 3 , 4 5 6
              p.mb-2 7 , 0 3 5
            .col-sm-12.col-lg-10
              p.mb-2 #[b 1.] Unidades: 5 + 4 + 6 = 15, escribo 5, llevo 1
              p.mb-2 #[b 2.] Decenas: 1 + 4 + 3 + 5 = 13, escribo 3, llevo 1
              p.mb-2 #[b 3.] Centenas: 1 + 3 + 2 + 4 = 10, escribo 0, llevo 1
              p.mb-2 #[b 4.] Millares: 1 + 2 + 1 + 3 = 7
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src="@/assets/curso/t1/10.png")
    h3.mb-3(data-aos="flip-up") Propiedades de la suma
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src="@/assets/curso/t1/12.png")
      .col-sm-12.col-lg-8
        LineaTiempoD.color-acento-contenido.large
          div(numero="1" titulo="Propiedad conmutativa")
            p.fw-bold Propiedad conmutativa: a + b = b + a 
            p El orden de los sumandos no altera el resultado de la suma. Esta propiedad establece que podemos cambiar el orden de los números al sumar y el resultado será el mismo.
            h5 Ejemplo 1:
            p.text-center 23 + 45 = 45 + 23
            p.text-center 68 = 68
            h5 Ejemplo 2 (con múltiples sumandos):
            p.text-center (12 + 34) + 56   =   (34 + 12) + 56   =   56 + (12 + 34)
            p.text-center 46 + 56       =          46 + 56        =       56 + 46
            p.text-center 102          =              102           =          102
            h5 Utilidad práctica:
            ul.lista-ul--color
              li
                i.fas.fa-circle.icon-list
                | Simplifica cálculos mentales.
              li
                i.fas.fa-circle.icon-list
                | Facilita la verificación de resultados.
              li
                i.fas.fa-circle.icon-list
                | Permite reorganizar operaciones complejas.
      
          div(numero="2" titulo="Propiedad asociativa")
            p.fw-bold Propiedad asociativa: (a + b) + c = a + (b + c)
            p La forma de agrupar los sumandos no altera el resultado final. Esta propiedad permite reagrupar los números, de diferentes formas, sin afectar el resultado.
            h5 Ejemplo 1:
            p.text-center (15 + 25) + 10 = 15 + (25 + 10)
            p.text-center 40 + 10 = 15 + 35
            p.text-center 50 = 50
            h5 Ejemplo 2 (aplicación práctica) - suma de ventas diarias:
            p.text-center (1,234 + 2,345) + 3,456 = 1,234 + (2,345 + 3,456)
            p.text-center 3,579 + 3,456 = 1,234 + 5,801
            p.text-center 7,035 = 7,035
            h5 Utilidad práctica:
            ul.lista-ul--color
              li
                i.fas.fa-circle.icon-list
                | Optimiza cálculos largos.
              li
                i.fas.fa-circle.icon-list
                | Permite estrategias de cálculo mental.
              li
                i.fas.fa-circle.icon-list
                | Facilita la organización de datos.
          div(numero="3" titulo="Elemento neutro")
            p.fw-bold Elemento neutro: a + 0 = a
            p Al sumar cero a cualquier número, el resultado es el mismo número. El cero es el único número que, al sumarlo, no modifica la cantidad original.
            h5 Ejemplo 1:
            p.text-center 156 + 0 = 156
            p.text-center 0 + 156 = 156
            h5 Ejemplo 2 (aplicación contable):
            p.text-center Saldo: 2,345
            p.text-center Movimiento: 0
            p.text-center Nuevo saldo: 2,345
            h5 Utilidad práctica:
            ul.lista-ul--color
              li
                i.fas.fa-circle.icon-list
                | Validación de operaciones.
              li
                i.fas.fa-circle.icon-list
                | Control de errores.
              li
                i.fas.fa-circle.icon-list
                | Verificación de balances.
    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Suma de números con signo
            p.mb-4 La suma de números con signo, decimales y fracciones, es una habilidad matemática fundamental aplicada en diversos contextos prácticos, como el control de inventarios, estados financieros y totalización de datos. En el PDF #[b Suma de números con signo], se explicarán las reglas básicas y los procedimientos para realizar estas operaciones de manera precisa y eficiente, considerando casos con números positivos y negativos, alineación de decimales y fracciones con igual o diferente denominador. El dominio de estas técnicas permitirá resolver problemas cotidianos y profesionales, con mayor claridad y exactitud.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/suma_de_numeros_con_signo.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Suma de números con signo.

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t1/13.png', alt='')

    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t1/14.png', alt='')
          .col-lg-7
            h2.mb-4 Para reforzar los conceptos sobre leyes de los signos y operaciones con fracciones, le invitamos a ver los siguientes videos:
            p.mb-4 Barushnet. (s. f.). Aritmética: operaciones básicas, leyes de los signos y fracciones [Video]. YouTube.
            a.anexo.mb-4.bg-white.w-fit(href="https://www.youtube.com/watch?v=-lpq4c7_BV8" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-video.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Aritmética: operaciones básicas, leyes de los signos y fracciones

            p.mb-4 Épsilon Akdemy. (s. f.). Aritmética: fracciones y operaciones [Video]. YouTube.
            a.anexo.mb-4.bg-white.w-fit(href="https://www.youtube.com/watch?v=ro-fpmydR4s" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-video.svg")
              .anexo__texto
                p <strong>Anexo. </strong>  Aritmética: fracciones y operaciones

    h3.mb-3(data-aos="flip-up") Resta
    .bg-1.p-4.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center.mb-0
        .col-sm-12.col-lg-6
          p.mb-3 La resta es la operación que determina la diferencia entre dos cantidades o encuentra el valor que se debe añadir a una cantidad, para obtener otra.
          p La resta se realiza sustrayendo unidades del mismo orden posicional:
          h5 Proceso:
          .row.justify-content-center.mb-5
            .col-sm-12.col-lg-3
              p.mb-2 5 , 6 7 8
              p.mb-2.bb-1 - 3 , 4 5 6
              p.mb-2 2 , 2 2 2
            .col-sm-12.col-lg-9
              p.mb-2 #[b 1.] Unidades: 8 - 6 = 2
              p.mb-2 #[b 2.] Decenas: 7 - 5 = 2
              p.mb-2 #[b 3.] Centenas: 6 - 4 = 2
              p.mb-2 #[b 4.] Millares: 5 - 3 = 2
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src="@/assets/curso/t1/15.png")


    h3.mb-3(data-aos="flip-up") Propiedades de la resta
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src="@/assets/curso/t1/16.png")
      .col-sm-12.col-lg-8
        LineaTiempoD.color-acento-contenido.large
          div(numero="1" titulo="No conmutatividad")
            p El orden de los números, en la resta, sí afecta el resultado, por lo que no es conmutativa. La resta no es conmutativa porque: a - b ≠ b - a.
            
            h5 Ejemplo 1:
            p 25 - 13 = 12
            p 13 - 25 = -12
            
            h5 Ejemplo 2 (contexto práctico): inventario
            p Inicial: 1,000
            p Ventas: 300
            p 1,000 - 300 = 700 (#[i stock] restante)
            p 300 - 1,000 = -700 (operación sin sentido práctico)

          div(numero="2" titulo="Elemento neutro por la derecha")
            p Restar cero de cualquier número no altera su valor.
            p Para cualquier número a: a - 0 = a

            h5 Ejemplo 1:
            p 156 - 0 = 156

            h5 Ejemplo 2 (contexto práctico): inventario
            p Inicial: 1,000
            p Ventas: 300
            p 1,000 - 300 = 700 (#[i stock] restante)
            p 300 - 1,000 = -700 (operación sin sentido práctico)

          div(numero="3" titulo="Inversa de la suma")
            p La resta de un número por sí mismo siempre es cero. Para cualquier número a: a - a = 0

    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Metodologías para restar
            p.mb-4 El dominio de las metodologías para restar es esencial en situaciones cotidianas y profesionales donde se requiere precisión en los cálculos. En el PDF #[b Metodologías para restar], se estudiarán las tres metodologías más utilizadas: la resta con préstamo, la resta de decimales y la resta en contextos específicos, como el cálculo de diferencias temporales, control de inventario y análisis financiero. Estas técnicas facilitan la resolución de problemas relacionados con el manejo de recursos, control de gastos y evaluación de rendimiento, permitiendo tomar decisiones informadas y eficientes.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/metodologias_para_restar.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Metodologías para restar

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t1/17.png', alt='')


    h3.mb-3(data-aos="flip-up") Multiplicación
    .bg-1.p-4.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center.mb-0
        .col-sm-12.col-lg-6
          p.mb-3 La multiplicación es una suma repetida que permite calcular el resultado de combinar una cantidad, consigo misma, una cantidad determinada de veces.
          p La multiplicación se realiza multiplicando cada dígito del multiplicando, por cada dígito del multiplicador:
          .row.justify-content-center.mb-5
            .col-sm-12.col-lg-6
              h5 Ejemplo:
              p.mb-2  234
              p.mb-2.bb-1.w-25  x 56
              p.mb-2 1,404 (234 x 6)
              p.mb-2.bb-1.w-75 11,700 (234 x 50)
              p.mb-2 13,104
            .col-sm-12.col-lg-6
              h5 Proceso:
              p.mb-2 #[b 1.] 234 × 6 = 1,404.
              p.mb-2 #[b 2.] 234 × 50 = 11,700.
              p.mb-2 #[b 3.] Sumar resultados parciales.
              p.mb-2 #[b 4.] Resultado final: 13,104
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src="@/assets/curso/t1/31.png")
    h3.mb-3(data-aos="flip-up") Propiedades de la multiplicación
    .row.justify-content-center.mb-5(data-aos="flip-up")
      
      .col-sm-12.col-lg-8
        LineaTiempoD.color-acento-contenido.large
          div(numero="1" titulo="Propiedad conmutativa")
            p.mb-4.fw-bold Propiedad conmutativa (a × b = b × a)

            p.mb-3 #[b Definición formal:] la propiedad conmutativa establece que el orden de los factores no altera el producto. Esta propiedad significa que podemos intercambiar el orden de los factores y el resultado será el mismo.

            p.mb-2.fw-bold Demostración:
            p.mb-2.fw-bold Con números naturales:
            p.ml-1.mb-2 4 × 3 = 3 × 4 = 12

            p.mb-2.fw-bold Con decimales:
            p.ml-1.mb-2 2.5 × 3 = 3 × 2.5 = 7.5

            p.mb-2.fw-bold Con fracciones:
            p.ml-1.mb-2 (2/3) × 5 = 5 × (2/3) = 10/3

            p.mb-2.fw-bold Aplicaciones prácticas:
            p.mb-2.fw-bold 1. En cálculos de área:
            p.ml-1.mb-2 Largo × Ancho = Ancho × Largo
            p.ml-1.mb-2 8 m × 6 m = 6 m × 8 m = 48 m²

            p.mb-2.fw-bold 2. En producción:
            p.ml-1.mb-2 5 cajas × 12 unidades = 12 unidades × 5 cajas = 60 unidades.

            p.mb-2.fw-bold 3. En costos:
            p.ml-1 3 productos × $45 = $45 × 3 productos = $135


          div(numero="2" titulo="Propiedad asociativa")
            p.mb-4.fw-bold Propiedad asociativa ((a × b) × c = a × (b × c))

            p.mb-3 La forma de agrupar los factores no afecta el resultado final. Esta propiedad permite reorganizar los factores en diferentes grupos sin alterar el producto final.

            p.mb-2.fw-bold 1. Números enteros:
            p.ml-1.mb-2 (2 × 3) × 4 = 2 × (3 × 4)
            p.ml-1.mb-2 6 × 4 = 2 × 12
            p.ml-1.mb-2 24 = 24

            p.mb-2.fw-bold 2. Con decimales:
            p.ml-1.mb-2 (1.5 × 2) × 3 = 1.5 × (2 × 3)
            p.ml-1.mb-2 3.0 × 3 = 1.5 × 6
            p.ml-1.mb-2 9.0 = 9.0

            p.mb-2.fw-bold Aplicaciones prácticas:
            p.mb-2.fw-bold 1. En cálculos comerciales:
            p.ml-1.mb-2 (5 artículos × $20) × 3 tiendas = 5 artículos × ($20 × 3 tiendas).

            p.mb-2.fw-bold 2. En producción por lotes:
            p.ml-1 4 (cajas × 6 unidades) × 5 pedidos = 4 cajas × (6 unidades × 5 pedidos).

          div(numero="3" titulo="Propiedad distributiva")
            p.mb-4.fw-bold Propiedad distributiva (a × (b + c) = (a × b) + (a × c))

            p.mb-3 La forma de la multiplicación se distribuye sobre la suma o resta. Esta propiedad relaciona la multiplicación con la suma/resta, permitiendo descomponer operaciones complejas.

            p.mb-2.fw-bold 1. Con suma:
            p.ml-1.mb-2 4 × (5 + 3) = (4 × 5) + (4 × 3)
            p.ml-1.mb-2 4 × 8 = 20 + 12
            p.ml-1.mb-2 32 = 32

            p.mb-2.fw-bold 2. Con resta:
            p.ml-1.mb-2 3 × (8 – 2) = (3 × 8) – (3 × 2)
            p.ml-1.mb-2 3 × 6 = 24 – 6
            p.ml-1.mb-2 18 = 18

            p.mb-2.fw-bold Aplicaciones prácticas:
            p.mb-2.fw-bold 1. En cálculo de precios:
            p.ml-1.mb-2 Precio × (Cantidad1 + Cantidad2) =
            p.ml-1.mb-2 (Precio × Cantidad1) + (Precio × Cantidad2)

            p.mb-2.fw-bold 2. En descuentos:
            p.ml-1.mb-2 $100 × (1 – 0.20) = ($100 × 1) – ($100 × 0.20)
            p.ml-1 = $100 – $20 = $80
            
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src="@/assets/curso/t1/18.png")

    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Casos especiales de la multiplicación
            p.mb-4 El estudio de los casos especiales de la multiplicación, es fundamental para resolver operaciones con mayor rapidez y precisión. El PDF #[b Casos especiales de la multiplicación], aborda dos aspectos claves: la multiplicación por potencias de 10, que simplifica el desplazamiento del punto decimal, y la multiplicación de números con signo, donde las reglas de los signos permiten interpretar resultados positivos y negativos, en contextos como finanzas y análisis cuantitativo. Estas técnicas facilitan la comprensión de operaciones complejas y su aplicación en problemas prácticos del ámbito profesional y cotidiano.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/casos_especiales_de_la_multiplicacion.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Casos especiales de la multiplicación

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t1/19.png', alt='')

    h3.mb-3(data-aos="flip-up") División
    .bg-1.p-4.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center.mb-0
        .col-sm-12.col-lg-6
          p.mb-3 La división es la operación que distribuye una cantidad en partes iguales o determina, cuántas veces una cantidad contiene a otra. La división implica encontrar cuántas veces el divisor, cabe en el dividendo.
          
          .row.mb-5
            .col-sm-12.col-lg-6
              p.mb-2.fw-bold  1,234 ÷ 56 = 22.035...
              p.mb-2.fw-bold 1,234 | 56
              p.mb-2.fw-bold –112   | -------
              p.mb-2.fw-bold  114    22.035...
              p.mb-2.fw-bold –112
              p.mb-2.fw-bold    20
           
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src="@/assets/curso/t1/20.png")
    h3.mb-3(data-aos="flip-up") Propiedades de la división
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src="@/assets/curso/t1/21.png")
      .col-sm-12.col-lg-8
        LineaTiempoD.color-acento-contenido.large
          div(numero="1" titulo="No conmutatividad")
            p.mb-4.fw-bold No conmutativa (a ÷ b ≠ b ÷ a)

            p.mb-3 #[b Definición formal:] el orden de los términos en la división, afecta el resultado. A diferencia de la suma y la multiplicación, en la división, el orden es crucial.

            p.mb-2.fw-bold Ejemplo 1:
            p.ml-1.mb-2 10 ÷ 2 = 5
            p.ml-1.mb-2 2 ÷ 10 = 0.2

            p.mb-2.fw-bold Ejemplo 2:
            p.ml-1.mb-2 100 ÷ 4 = 25
            p.ml-1.mb-2 4 ÷ 100 = 0.04

          div(numero="2" titulo="No división por uno")
            p.mb-4.fw-bold No división por uno (a ÷ 1 = a)

            p.mb-3 #[b Definición formal:] cualquier número dividido entre 1, resulta en el mismo número. Esta propiedad establece que 1 es el elemento neutro de la división.

            p.mb-2.fw-bold Ejemplos:
            p.mb-2 1) 234 ÷ 1 = 234
            p.mb-2 2) 23.45 ÷ 1 = 23.45
            p.mb-2 3) (-15) ÷ 1 = -15

    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Casos especiales de la división
            p.mb-4 El análisis de los casos especiales de la división, es esencial para resolver problemas matemáticos con precisión y claridad. En el PDF #[b Casos especiales de la división], se explorarán tres situaciones claves: la división con decimales, la división con resto y la imposibilidad de la división por cero, destacando sus reglas, procesos y aplicaciones prácticas. Estos conceptos permiten abordar escenarios cotidianos, como la distribución de productos, la planificación de recursos y los cálculos aproximados, facilitando la toma de decisiones en contextos académicos y profesionales.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/casos_especiales_de_la_division.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Casos especiales de la división

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t1/22.png', alt='')

    h3.mb-5(data-aos="flip-up") Aplicaciones especializadas
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-7.bg-1.p-4
        p.mb-4.fw-bold División en proporciones
        p.mb-0.fw-bold Razones y proporciones:
        p.mb-0 La división se usa para establecer relaciones:
        p.mb-0 Razón precio / Proporción de ingredientes.
        p.mb-0 Ratios financieros cantidad.
      .col-sm-12.col-lg-5.d-none.d-lg-block
        img(src="@/assets/curso/t1/23.png")

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-5.d-none.d-lg-block
        img(src="@/assets/curso/t1/24.png")
      .col-sm-12.col-lg-7.bg-1.p-4
        p.mb-4.fw-bold Aplicaciones financieras:
        p.mb-0.fw-bold 1. Rentabilidad:
        p.mb-3 ROI = (Beneficio ÷ Inversión) × 100

        p.mb-0.fw-bold 2. Márgenes:
        p.mb-3 Margen = ((Precio – Costo) ÷ Precio) × 100

        p.mb-0.fw-bold 3. Ratios:
        p.mb-0 Liquidez = Activo Corriente ÷ Pasivo Corriente
      

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-6
          p.mb-2 Para reforzar lo aprendido, lo invitamos a participar en un juego que desafía su velocidad mental, a través de preguntas rápidas sobre operaciones matemáticas. 
          a.anexo.mb-4.w-fit(href="https://wordwall.net/es/resource/16370335/reforzando-las-operaciones-basicas-de-matematicas" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#DBE7FC'}")
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Reforzando las operaciones básicas de matemáticas
      .col-sm-12.col-lg-6
          p.mb-2 También, lo invitamos a poner en práctica los conceptos adquiridos, a través de la creación de operaciones matemáticas, en la siguiente herramienta online:
          a.anexo.mb-4.w-fit(href="https://www.educalim.com/biblioteca/mate/mate.html" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#DBE7FC'}")
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Crea operaciones matemáticas


    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Ejercicios propuestos
            p.mb-4 Las operaciones matemáticas básicas son fundamentales en el contexto industrial para optimizar procesos y tomar decisiones precisas. El PDF #[b Ejercicios propuestos], presenta ejercicios prácticos de suma, resta, multiplicación y división, aplicados a escenarios reales, como el cálculo de producción, análisis de inventarios y distribución de recursos. Estas actividades permiten resolver problemas complejos de manera estructurada, facilitando la mejora de la eficiencia, la planificación y el control en sectores como manufactura, comercio y logística.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Ejercicios_propuestos.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Ejercicios propuestos

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t1/25.png', alt='')
    p.mb-3(data-aos="flip-up") Para apoyarse en la solución de los ejercicios propuestos en la unidad, lo invitamos a utilizar la herramienta online Symbolab.       
    a.anexo.mb-5.w-fit(href="https://es.symbolab.com/solver/basic-operations-calculator/" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#DBE7FC'}")
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Calculadora de operaciones básicas
    p.mb-3(data-aos="flip-up") En la herramienta podrá ingresar los cálculos matemáticos a realizar y, posteriormente, dar clic en “ir” para ver los resultados detallados de cada ejercicio.
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-6
        .titulo-figura.mb-2
          h5 Figura 1. 
          span Symbolab. Captura de pantalla del sitio. 
        figure.mb-5
          img(src='@/assets/curso/t1/26.png', alt='').mb-0
          figcaption Nota. Tomado de: https://es.symbolab.com/solver/basic-operations-calculator/ 
      .col-sm-12.col-lg-6
        .titulo-figura.mb-2
          h5 Figura 2. 
          span Symbolab. Captura de pantalla del sitio. 
        figure.mb-5
          img(src='@/assets/curso/t1/27.png', alt='').mb-0
          figcaption Nota. Tomado de: https://es.symbolab.com/solver/basic-operations-calculator/ 

    .bg-full-width.bg-3.mb-5(data-aos="flip-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Importancia de las matemáticas
            p.mb-4 Las matemáticas desempeñan un papel fundamental en el mundo actual, facilitando soluciones precisas en distintos campos profesionales y cotidianos. En el PDF #[b Importancia de las matemáticas], se analiza su aplicación en sistemas e informática, contabilidad, logística, gestión humana y salud, destacando cómo permiten optimizar procesos, analizar datos y resolver problemas complejos. A través de ejemplos concretos y actuales, se demuestra la relevancia de las matemáticas en la toma de decisiones estratégicas y en el desarrollo de tecnologías avanzadas que impactan de manera positiva en la sociedad.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/importancia_de_las_matematicas.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Importancia de las matemáticas

          .col-lg-5.d-none.d-lg-block
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/t1/28.png', alt='')


    .row.align-items-center.bg-1.p-4(data-aos="flip-up")
        .col-lg-auto.d-none.d-lg-block
          img(src="@/assets/curso/t1/29.svg", style="max-width: 90px").mx-auto
        .col-lg
          p.mb-0 Las matemáticas no solo son el lenguaje universal para resolver problemas complejos, sino que también son una herramienta vital en el avance tecnológico y en la toma de decisiones, en un mundo dinámico y globalizado.











</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>
