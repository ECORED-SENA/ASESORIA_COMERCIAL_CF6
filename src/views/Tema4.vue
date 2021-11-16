<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Presentaciones
    p.mb-4 Se puede definir que una presentación de ventas es una especie de guion o argumento que tiene el equipo de ventas de una organización para ofrecer sus productos a los clientes. La presentación puede realizarse en persona, por vía telefónica, videollamada, videoconferencia u otro medio que lo permita, aunque en algunas empresas consideran que es más importante el contacto personal.

    .row.justify-content-center.mb-4
      .col-lg-10.mb-4
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema4/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4(data-aos="fade-left")
            p.mb-0 Una presentación en el proceso de ventas no solo consta de la llamada o la presentación personal, la presentación es parte de un conjunto de acciones que se desarrollan para cerrar la venta. La presentación puede incluir una conversación inicial, una reunión, una llamada (o videollamada), envío de una propuesta y hasta una demostración.
      .col-lg-10.mb-4
        p Realizar una presentación incluye una inversión de tiempo para su preparación y exposición o socialización, puede incluir una presentación digital en diapositivas o videos que apoyen el argumento del vendedor. De acuerdo con la especialidad de la presentación, pueden participar varias personas de la fuerza de ventas y el cliente puede estar conformado por un equipo directivo o de interés en el producto para adquirir. 
      .col-lg-10.mb-4
        .cajon.color-primario.p-4(data-aos="fade-right")
          p Todo el proceso que incluye la elaboración de la presentación, puede generar un alto estrés, incluso para el vendedor más experimentado, por lo que es necesario tener en cuenta una serie de pasos concretos, planificados y en perfecto control.
      .col-lg-10
        .tarjeta.color-blue-gradient.p-4(data-aos="fade-right")
          .row.align-items-center.mb-4
            .col-lg-2
              img(src='@/assets/curso/tema4/img02.svg')
            .col-lg-8
              .h4.text-white Ejemplo de presentación
              p.text-white Para esto, se usará la presentación que en Apple han realizado del iPhone 7 siempre bajo una estética profesional, limpia y atractiva han logrado que la expectativa envuelva cada presentación, y por lo general, nunca decepcionan. Para comprender qué es una presentación, observe la que se encuentra en el material complementario.
            .col-lg-2
              a.boton.color-acento-botones.me-3(href="https://www.youtube.com/watch?v=NS0txu_Kzl8" target="_blank" type="application/pdf")
                span Descargar
                i.fas.fa-file-download

    p.mb-4 Las presentaciones pueden ser de muchos tipos: de negocios, para producto nuevo o de relanzamiento, marca personal o de producto, profesionales o académicas, entre otras. También pueden estar dirigidas a públicos o personas de interés, por ejemplo, en la propia empresa, a un público general, accionistas o inversores.
    p.mb-4 Como bien se ha desarrollado a lo largo de este apartado, las presentaciones son recursos gráficos que apoyan en la promoción o venta de un producto y que presenta una estructura donde se va dando a conocer diferentes áreas o aspectos de un discurso profesional, académico o publicitario; de ahí la importancia de acertar en el tipo de presentación que se perfila. Se pueden clasificar las presentaciones de la siguiente forma:

    #MapaGroup01.row.justify-content-center.mb-4
      .col-lg-10
        .h4.text-center Clasificación de presentaciones
      .col-lg-3
        .row.justify-content-center
          button.col-6.col-md-12.tarjeta.color-light-blue--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse1' aria-expanded='true' aria-controls='.multi-collapse1')
            p.mb-0.text-bold.text-center Trabajo
          button.col-6.col-md-12.tarjeta.color-light-blue--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse2' aria-expanded='true' aria-controls='.multi-collapse2')
            p.mb-0.text-bold.text-center Breve o #[i pitch]
          button.col-6.col-md-12.tarjeta.color-light-blue--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse3' aria-expanded='true' aria-controls='.multi-collapse3')
            p.mb-0.text-bold.text-center Línea
          button.col-6.col-md-12.tarjeta.color-light-blue--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse4' aria-expanded='true' aria-controls='.multi-collapse4')
            p.mb-0.text-bold.text-center Marca
          button.col-6.col-md-12.tarjeta.color-light-blue--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse5' aria-expanded='true' aria-controls='.multi-collapse5')
            p.mb-0.text-bold.text-center Producto

      .col-lg-4
        .multi-collapse1.tarjeta.color-light-yellow--borde.p-4.collapse.show(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img08.svg')
          .h4.text-center Trabajo
          p Suele tener un carácter más interno. El público son tus trabajadores o socios.

        .multi-collapse2.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img09.svg')
          .h4.text-center Breve o #[i pitch]
          p Presenta un producto o marca en un tiempo récord. En ocasiones las presentaciones requieren ajustarse a unas normas, como suele suceder en las rondas de búsqueda de inversiones. 

        .multi-collapse3.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img10.svg')
          .h4.text-center Línea
          p Se caracteriza por estar en la web y se puede trasladar a cualquier lugar, puede estar almacenada en internet y ser enviada por correo electrónico.

        .multi-collapse4.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img11.svg')
          .h4.text-center Marca
          p En este tipo de presentación se puede hablar del proceso de configuración, de los valores que se quieren transmitir en la marca.

        .multi-collapse5.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img12.svg')
          .h4.text-center Producto
          p Presenta todo el proceso de desarrollo o de ciclo de vida del producto. La presentación de producto, puede ser la antesala a la demostración.

        .multi-collapse6.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img13.svg')
          .h4.text-center Inversionistas
          p Se deben resolver los puntos más importantes para aquellos que deben financiar el producto, servicio o iniciativa. En el caso de las rondas de inversión, son fundamentales varias partes: quién pide el dinero, para qué y cómo se va a devolver.
 
        .multi-collapse7.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img14.svg')
          .h4.text-center Corporativa
          p No existe un estilo único aunque sí es cierto que generalmente se piden modelos de presentación más serios y formales. Aquí se realiza una presentación de los valores organizacionales y elementos estratégicos de la empresa, tales como visión, misión, entre otros.

        .multi-collapse8.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img15.svg')
          .h4.text-center Plan de negocio
          p Usualmente, las presentaciones de los planes de negocio tienen una estructura definida de acuerdo con los inversores o aquellos a quienes vayamos a presentar la idea de negocio deben resolver todas sus dudas. En algunas convocatorias o invitaciones determinan qué estructura de presentación se debe realizar.

        .multi-collapse9.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img16.svg')
          .h4.text-center Profesional
          p Aquí se enmarcan aquellas que presentan un currículum u hoja de vida profesional, logros, títulos obtenidos, trabajos desarrollados, entre otros aspectos que ayudan a convencer a un empresario o empleador. Son creativas y diferentes de acuerdo con el tipo de profesión.

        .multi-collapse10.tarjeta.color-light-yellow--borde.p-4.collapse(data-bs-parent='#MapaGroup01')
          .row.justify-content-center
            .col-lg-3.col-sm-6
              img(src='@/assets/curso/tema4/img17.svg')
          .h4.text-center Proyecto
          p.mb-4 Similar que en la presentación de plan de negocio, tienen una estructura definida.
          p Principalmente, presentan factores interesantes para los inversionistas.

      .col-lg-3.mt-2
        .row.justify-content-center
          button.col-6.col-md-12.tarjeta.color-light-red--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse10' aria-expanded='true' aria-controls='.multi-collapse10')
            p.mb-0.text-bold.text-center Proyecto
          button.col-6.col-md-12.tarjeta.color-light-red--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse9' aria-expanded='true' aria-controls='.multi-collapse9')
            p.mb-0.text-bold.text-center Profesional
          button.col-6.col-md-12.tarjeta.color-light-red--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse8' aria-expanded='true' aria-controls='.multi-collapse8')
            p.mb-0.text-bold.text-center Plan de negocio
          button.col-6.col-md-12.tarjeta.color-light-red--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse7' aria-expanded='true' aria-controls='.multi-collapse7')
            p.mb-0.text-bold.text-center Corporativa
          button.col-6.col-md-12.tarjeta.color-light-red--borde.p-3.mb-2(data-bs-toggle='collapse' data-bs-target='.multi-collapse6' aria-expanded='true' aria-controls='.multi-collapse6')
            p.mb-0.text-bold.text-center Inversionistas

    p.mb-4 Más que el contenido, lo importante en una presentación, son aquellos elementos intangibles que juegan un papel importante durante el desarrollo. El lenguaje corporal, el tono de voz, la actitud, incluso, los movimientos, pueden ser determinantes para que el cliente pueda tomar la decisión de compra y cerrar el negocio. Algunos tips importantes para un buen desarrollo de una presentación se exponen en el siguiente video.
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/oxg7wHcdbrY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    p.mb-4 Así mismo, en cuanto al lenguaje corporal, se recomienda lo siguiente:
    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 11
      span #[i Lenguaje corporal]
    
    .row.justify-content-center.mb-4
      .col-lg-4(data-aos="fade-down")
        img(src='@/assets/curso/tema4/img03.svg')
      .col-lg-7
        .tarjeta.color-light-yellow--borde.p-3.mb-1(data-aos="fade-left")
          .row.align-items-center
            .col-lg-1
              img(src='@/assets/curso/tema4/img04.svg')
            .col-lg-11
              p Si la presentación es en línea, o a través de videoconferencia, los gestos, la sonrisa y la forma de mirar son elementos fundamentales para convencer.

        .tarjeta.color-light-blue--borde.p-3.mb-1(data-aos="fade-left")
          .row.align-items-center
            .col-lg-1
              img(src='@/assets/curso/tema4/img05.svg')
            .col-lg-11
              p Un buen uso del lenguaje corporal muestra confianza y seguridad el momento de realizar la presentación.

        .tarjeta.color-light-yellow--borde.p-3.mb-1(data-aos="fade-left")
          .row.align-items-center
            .col-lg-1
              img(src='@/assets/curso/tema4/img04.svg')
            .col-lg-11
              p El objetivo es transmitir calma, confianza y seguridad para el cierre del trato, por tanto, el contacto visual demuestra que el presentador está interesado en los prospectos y en lo que ellos dicen.

        .tarjeta.color-light-blue--borde.p-3.mb-1(data-aos="fade-left")
          .row.align-items-center
            .col-lg-1
              img(src='@/assets/curso/tema4/img05.svg')
            .col-lg-11
              p Si la presentación es “en persona”, sea en auditorio o sala de conferencia, es importante un buen uso del espacio. Si tienes un micrófono inalámbrico, puedes desplazarte o caminar por el escenario.

        .tarjeta.color-light-yellow--borde.p-3.mb-1(data-aos="fade-left")
          .row.align-items-center
            .col-lg-1
              img(src='@/assets/curso/tema4/img04.svg')
            .col-lg-11
              p Una buena postura también demuestra confianza. En el caso de la presentación en línea o por videoconferencia, está el modo de sentarse o ver a la cámara.

        .tarjeta.color-light-blue--borde.p-3.mb-1(data-aos="fade-left")
          .row.align-items-center
            .col-lg-1
              img(src='@/assets/curso/tema4/img05.svg')
            .col-lg-11
              p Si la presentación es presencial, ofrece un apretón de manos firme y decidido, pues genera una buena primera impresión. 
    
    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-blue-gradient.p-4(data-aos="fade-right")
          .row.align-items-center.mb-4
            .col-lg-2
              img(src='@/assets/curso/tema4/img02.svg')
            .col-lg-8
              .h4.text-white Desarrollo de una presentación
              p.text-white Para ver un ejemplo, se invita a observar el video Hablando con Julis, donde se pueden observar los momentos de la presentación anteriormente expuestos. El video se encuentra en el material complementario.
            .col-lg-2
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=0SjVNTAVdgs" target="_blank")
                span Ver Video
                i.fas.fa-video

    p.mb-4 Finalmente, existen diferentes herramientas y plataformas digitales para el diseño de presentaciones y que se pueden usar como apoyo al momento de presentar el producto ante el cliente. Algunas de las herramientas son:

    .row.justify-content-center.mb-4
      .col-lg-3.mb-5
        .cajon.color-primario.p-5(data-aos="fade-right")
          ul.lista-ul--color
            li 
              i.fas.fa-check
              | Knovio
            li 
              i.fas.fa-check
              | PowToon
            li 
              i.fas.fa-check
              | Prezi
            li 
              i.fas.fa-check
              | Emaze
            li 
              i.fas.fa-check
              | Hakiu Deck
            li 
              i.fas.fa-check
              | Slidebean
            li 
              i.fas.fa-check
              | Canva
            li 
              i.fas.fa-check
              | Google Slides
            li 
              i.fas.fa-check
              | Visme
            li 
              i.fas.fa-check
              | Swipe
      .col-lg-7(data-aos="fade-left")
        img(src='@/assets/curso/tema4/img06.png')

    .row.justify-content-center.mb-5
      .col-lg-10
        .tarjeta.color-blue-gradient.p-4(data-aos="fade-right")
          .row.align-items-center.mb-4
            .col-lg-2
              img(src='@/assets/curso/tema4/img02.svg')
            .col-lg-8
              .h4.text-white Medios de apoyo
              p.text-white En el artículo Los mejores programas para hacer presentaciones como un profesional escrito por Universia, y que se encuentra en el material complementario, se exponen las diez herramientas más utilizadas para el desarrollo de presentaciones dinámicas y visualmente agradables.
            .col-lg-2
              a.boton.color-acento-botones.me-3(href="https://www.universia.net/co/actualidad/orientacion-academica/mejores-programas-hacer-presentaciones-como-profesional-1098969.html" target="_blank" type="application/pdf")
                span Descargar
                i.fas.fa-file-download
    
    br
    .h4 Síntesis
    figure.mb-4(data-aos="flip-up")
      img(src='@/assets/curso/tema4/img07.svg')
    separador
</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
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
