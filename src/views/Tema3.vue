<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Demostraciones
    
    p.mb-4 En el proceso de ventas la demostración se define como presentar pruebas y hechos que afirmen lo que se dice de un producto. La demostración es uno de los momentos más importantes en los cuales el consumidor puede estar en contacto con el producto y, a su vez, se pueden fortalecer sus argumentos y finalizar con el cierre de venta.

    .row.justify-content-center.mb-4
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema3/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4(data-aos="fade-left")
            p.mb-0 Puede decirse que el momento de la demostración es el más importante y decisivo que tiene un vendedor para cerrar un proceso de venta.
    
    p.mb-4 Es fundamental tener en cuenta que una buena demostración debe considerarse como un factor que refuerce los argumentos que lleven al cierre de la venta, por tanto, debe cumplir con dos propósitos principalmente, dirigirse a las necesidades del consumidor y crear confianza, tal como se describe a continuación.
    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 9
      span #[i Objetivos de una demostración]

    .row.align-items-center.mb-4
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        .row.mb-4
          .col-lg-2
            img(src='@/assets/curso/tema3/img02.svg') 
        .h4 Dirigirse a las necesidades específicas del consumidor
        p Orientarse a su impulso o deseo de degustar, tocar, oler, sentir y ver, estos aspectos se unen para brindarle al consumidor una experiencia cercana con el producto. Darle la oportunidad al consumidor que esté en contacto con el producto, lo lleva integrar todos sus deseos, expectativas e ideales, y a través de la “prueba y ejemplo” puede tomar una mejor decisión de compra.
      .col-lg-4.mb-4.mb-lg-0
        img(src='@/assets/curso/tema3/img03.svg')(data-aos="flip-up")
      .col-lg-4.mb-0(data-aos="fade-left")
        .row.mb-4
          .col-lg-2
            img(src='@/assets/curso/tema3/img04.svg') 
        .h4 Crear confianza 
        p La demostración le permitirá al comprador estar convencido de los beneficios que recibirá con la compra del producto. Es importante que el comprador experimente los beneficios del producto antes de adquirirlo, para que lo pueda adquirir y tenga plena satisfacción con lo que recibe.

    .row.justify-content-center.mb-4
      .col-lg-8
        .tarjeta.color-light-blue.p-4.mb-4(data-aos="fade-right")
          p Ahora bien, aunque no hay una “regla de oro” para estructurar una demostración, sí es posible recomendar una serie de elementos que debe contener esta actividad para que sea exitosa.
        
        LineaTiempoD.color-acento-contenido.mb-5
          .row.justify-content-center(numero="1" titulo="Claridad de los beneficios y ventajas")
            .col-md-11.mb-4.mb-md-0
              p.mb-4 Primero, debe tenerse claridad en los beneficios y ventajas que ofrece el producto según el tipo de cliente que lo va a adquirir. En alguno de los casos no es fácil informarle al cliente acerca de las características del producto, por eso, es más eficiente hacer una demostración. Algunas de las características son:
              p.mb-4 Antes de la demostración, es importante hacernos las siguientes preguntas:
            .col-md-10.mb-4.mb-md-0
              ul.lista-ul--color
                li 
                  i.fas.fa-check-circle
                  | ¿Quién es el cliente?
                li 
                  i.fas.fa-check-circle
                  | ¿Por qué se interesa en mi producto?
                li 
                  i.fas.fa-check-circle
                  | ¿Qué productos similares tiene mi competidor?
                li 
                  i.fas.fa-check-circle
                  | ¿Qué estrategia se ejecutará en la demostración?
          .row.justify-content-center(numero="2" titulo="Diseño de estrategia")
            .col-md-11.mb-4.mb-md-0
              p.mb-4 En segundo lugar, es importante que, antes de la demostración, se diseñe una estrategia para mostrar el producto, por ejemplo, si se hablará del precio final, se entregará un descuento, se realizará un concurso o se hará mención de algunos beneficios destacando sus ventajas. Los atributos son las “características técnicas del producto”, así como sus cualidades principales.
          .row.justify-content-center(numero="3" titulo="Lo que se espera de la demostración")
            .col-md-11.mb-4.mb-md-0
              p.mb-4 Teniendo en cuenta lo anterior, es posible que la demostración arroje los siguientes resultados:
            .col-md-10.mb-4.mb-md-0
              ul.lista-ul--color
                li 
                  i.fas.fa-check-circle
                  | Aumento en la motivación y deseo de obtener el producto.
                li 
                  i.fas.fa-check-circle
                  | Mayor retención de atención de los clientes, ayudando al cierre de la venta.
                li 
                  i.fas.fa-check-circle
                  | Proveer al consumidor una verdadera experiencia real de uso haciendo que el producto se venda por sí mismo.
                li 
                  i.fas.fa-check-circle
                  | Disminución de objeciones al momento de comprar el producto por parte del cliente.
                li 
                  i.fas.fa-check-circle
                  | Aumento de la confianza del cliente hacia el producto y la empresa.

    .h4 De otro lado, una buena demostración requiere del siguiente proceso para que sean exitosas:

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 10
      span #[i Proceso de una demostración]
    
    .row.justify-content-center.mb-4
      .col-lg-10
        .row.justify-content-center
          .col-lg-3.mb-4
            .tarjeta.color-light-red--borde.p-4(data-aos="fade-right")
              .row.justify-content-center
                .col-lg-8
                  img(src='@/assets/curso/tema3/img05.svg')
              p Planifique su demostración con anticipación.
          .col-lg-3.mb-4
            .tarjeta.color-light-blue--borde.p-4(data-aos="flip-right")
              .row.justify-content-center
                .col-lg-8
                  img(src='@/assets/curso/tema3/img06.svg')
              p Muestre principalmente las ventajas que tiene el producto.
          .col-lg-3.mb-4
            .tarjeta.color-light-red--borde.p-4(data-aos="flip-left")
              .row.justify-content-center
                .col-lg-8
                  img(src='@/assets/curso/tema3/img07.svg')
              p Comience primero por las características obvias.
              br
          .col-lg-3.mb-4
            .tarjeta.color-light-blue--borde.p-4(data-aos="fade-left")
              .row.justify-content-center
                .col-lg-8
                  img(src='@/assets/curso/tema3/img08.svg') 
              p Deje que el cliente tenga una experiencia directa con el producto.

          .col-lg-3.mb-4
            .tarjeta.color-light-red--borde.p-4(data-aos="fade-right")
              .row.justify-content-center
                .col-lg-8
                  img(src='@/assets/curso/tema3/img09.svg')
              p Aproveche la demostración para ir comprometiendo al cliente progresivamente.
              br
          .col-lg-3.mb-4
            .tarjeta.color-light-blue--borde.p-4(data-aos="flip-up") 
              .row.justify-content-center
                .col-lg-8
                  img(src='@/assets/curso/tema3/img10.svg')
              p Utilice material audiovisual como videos, imágenes, animaciones, entre otros, para que cautive al cliente.
          .col-lg-3.mb-4
            .tarjeta.color-light-red--borde.p-4(data-aos="fade-left")
              .row.justify-content-center
                .col-lg-8
                  img(src='@/assets/curso/tema3/img11.svg')
              p Esté listo para el cierre de la venta del producto, tenga a mano opciones para el cliente.
              br
    p.mb-5 Finalmente, existen tres tipos de demostraciones:
    SlyderB.mb-5(:datos="datosSlyder")
    separador
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Demostraciones uno a uno',
        texto:
          'Son demostraciones rápidas que el agente de ventas o representante realiza con una persona. Generalmente son detalladas, pues tiene la oportunidad de hablar de todas las características del producto.',
        imagen: require('@/assets/curso/tema3/img12.png'),
      },
      {
        titulo: 'Demostraciones express',
        texto:
          'Una demostración <um>express</um> se enfoca principalmente en una solución o beneficio específico del producto. Se realiza en lugares públicos, con pocos invitados y se desarrolla una experiencia rápida y sencilla. Lo importante es mantener la atención del usuario.',
        imagen: require('@/assets/curso/tema3/img13.png'),
      },
      {
        titulo: 'Demostraciones temáticas',
        texto:
          'Se organizan con grupos medianos o grandes que pueden pertenecer a un sector específico, por ejemplo, construcción, gastronómico, textil, etc. Aquí se enfoca en alguna funcionalidad del producto, de acuerdo con el sector invitado.',
        imagen: require('@/assets/curso/tema3/img14.png'),
      },
    ],
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
