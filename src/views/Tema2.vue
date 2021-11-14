<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Exhibición
    
    p.mb-4 Las actividades que permiten mostrar los productos en el punto de venta y que estén al alcance del cliente para su compra, se denomina exhibición. Esta se concibe como la clasificación, selección, colocación y presentación del producto en el punto o lugar de venta para atraer la atención del comprador actual o bien el potencial.
    .row.mb-4
      .col-lg-10
        figure(data-aos="flip-up")
          img(src='@/assets/curso/tema2/img01.png') 
      .col-5
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
          h5 La exhibición del producto, en el punto de venta, se realiza con el uso de muebles o elementos especiales que lo ponen al alcance de los clientes.
    
    p.mb-4 Entre los propósitos de la exhibición, se tienen:
    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 5
      span #[i Propósitos de la exhibición]

    figure.mb-4
      img(src='@/assets/curso/tema2/img02.svg')(data-aos="flip-up")
    
    p.mb-4 El espacio en el punto de venta juega un papel importante en la exhibición del producto que puede organizarse de acuerdo con la disposición que se tenga en el lugar. El administrador, como responsable del sitio y de la exhibición, deberá organizarlo según las secciones, espacios de circulación, ubicación de zonas y puntos de venta fríos o calientes, ubicación de elementos externos al establecimiento y áreas complementarias.
    
    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 6
      span #[i Zonas frías y calientes según los accesos y la circulación]
  
    figure.mb-4
      img(src='@/assets/curso/tema2/img03.png')(data-aos="flip-up")
      figcaption Nota. Tomada de Seggiaro (2017).
    
    p.mb-4 Este análisis debe realizarse de acuerdo con el espacio en el punto de venta y definir los tipos de exhibición que se pueden aplicar. Los consumidores realizan gran parte de las decisiones de compra directamente en el piso de ventas, por lo que una exhibición efectiva de los productos puede influir en varias de ellas.

    TabsC.color-acento-contenido.mb-4
      .py-3.py-md-4(titulo="Exhibición vertical")
        .row.justify-content-center
          .col-md-6.mb-4.mb-md-0
            h4 Exhibición vertical
            p En las exhibiciones verticales se organiza un mismo producto de arriba hacia abajo. Donde la exhibición de colores se recomienda hacerla de claro a oscuro y de izquierda a derecha.
          .col-md-5.mb-0
            img(src='@/assets/curso/tema2/img04.png')
      .py-3.py-md-4(titulo="Exhibición horizontal")
        .row.justify-content-center
          .col-md-6.mb-4.mb-md-0
            h4 Exhibición horizontal
            p El producto se dispone de izquierda a derecha en los distintos niveles de visibilidad: nivel de la cabeza, nivel de los ojos, nivel de las manos y nivel del suelo.
          .col-md-5.mb-0
            img(src='@/assets/curso/tema2/img05.png')
      .py-3.py-md-4(titulo="Exhibición bloque")
        .row.justify-content-center
          .col-md-6.mb-4.mb-md-0
            h4 Exhibición bloque
            p La marca se agrupa en una estantería ocupando dos o tres peldaños o entrepaños.
          .col-md-5.mb-0
            img(src='@/assets/curso/tema2/img06.png')
      .py-3.py-md-4(titulo="Exhibición mixta")
        .row.justify-content-center
          .col-md-6.mb-4.mb-md-0
            h4 Exhibición mixta
            p Puede decirse que es una combinación de la exhibición vertical y la horizontal. Se utiliza para llamar la atención de los consumidores de una forma más efectiva.
          .col-md-5.mb-0
            img(src='@/assets/curso/tema2/img07.png')

    p.mb-4 De acuerdo con la estrategia del comercio, pueden emplearse otras formas de exhibición, haciendo una combinación de las anteriores o bien organizando los productos de una forma creativa, que pueda resultar asertiva al generar ventas.
    p.mb-4 Otro factor importante al momento de exhibir el producto es el uso de las vitrinas, aquí se muestra el producto en diferentes ángulos y, a pesar que el consumidor no pueda acceder al producto, igualmente se siente atraído por este. Las vitrinas pueden clasificarse de la siguiente forma:

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 7
      span #[i Tipos de vitrinas] 
    
    .row.justify-content-center.mb-5
      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img08.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .row.justify-content-center.mb-4
                .col-4
                  img(src='@/assets/curso/tema2/img15.svg')
              h1.text-center Vitrinas de prestigio
              p Son aquellas donde la belleza de sus artículos expuestos supone un impacto visual que, ante todo, vende el prestigio del establecimiento.

      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img09.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .row.justify-content-center.mb-4
                .col-4
                  img(src='@/assets/curso/tema2/img16.svg')
              h1.text-center Vitrinas de temporada
              p Se exponen al comienzo de una temporada, informando de nuevos productos y tendencias del mercado.

      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img10.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .row.justify-content-center.mb-4
                .col-4
                  img(src='@/assets/curso/tema2/img17.svg')
              h1.text-center Vitrinas promocionales
              p Exponen productos promocionados o de oferta, identificando una clara oportunidad de compra.

      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img11.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .row.justify-content-center.mb-4
                .col-4
                  img(src='@/assets/curso/tema2/img18.svg')
              h1.text-center Vitrinas comerciales
              p Presentan los productos que conforman el surtido del establecimiento con un claro directo mensaje de venta.

      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img12.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .row.justify-content-center.mb-4
                .col-4
                  img(src='@/assets/curso/tema2/img19.svg')
              h1.text-center Vitrinas de precios
              p Son aquellas que, ante todo, destacan el precio del producto, siendo este el principal motivo de compra.

      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img13.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .row.justify-content-center.mb-4
                .col-4
                  img(src='@/assets/curso/tema2/img20.svg')
              h1.text-center Vitrinas informativas
              p Su misión consiste en dar a conocer nuevos o desconocidos productos o servicios que supongan un cambio o un avance en la concepción de los mismos.

      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img14.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .row.justify-content-center.mb-4
                .col-4
                  img(src='@/assets/curso/tema2/img21.svg')
              h1.text-center Vitrinas estacionales
              p Contienen productos sometidos a una fuerte estacionalidad en función de la época del año y motivados por la moda.

    p.mb-4 En el uso estratégico de las vitrinas, se destacan los siguientes aspectos:

    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema2/img22.svg')

      .tarjeta.color-light-blue.p-3(x="7%" y="53%" numero="+")
        .h5.mb-2 La naturalidad 
        p La presentación física debe ser lo más natural para que se perciba el mensaje que se quiere transmitir.
      
      .tarjeta.color-light-blue.p-3(x="84%" y="42%" numero="+")
        .h5.mb-2 La luz 
        p El conocimiento técnico del manejo de la luz al montar una vitrina es muy importante por los efectos negativos o positivos que pueda causar en la presentación de los productos.

      .tarjeta.color-light-blue.p-3(x="40%" y="14%" numero="+")
        .h5.mb-2 Los colores 
        p Son elementos visuales que provocan reacciones en el consumidor para atraer la atención hacia el producto. La aplicación adecuada del color en cuanto a su significado psicológico, genera reacciones que pueden motivar la compra del producto. 

      .tarjeta.color-light-blue.p-3(x="46%" y="80%" numero="+")
        .h5.mb-2 Los olores 
        p Provocan diferentes reacciones, sensaciones y evocaciones que ejercen una influencia sobre el ánimo y los sentidos del consumidor.

      .tarjeta.color-light-blue.p-3(x="60%" y="52%" numero="+")
        .h5.mb-2 La psicología 
        p Busca llamar la atención, despertar el interés, incitar el deseo, hacer entrar al cliente.

      .tarjeta.color-light-blue.p-3(x="28%" y="85%" numero="+")
        .h5.mb-2 La composición 
        p Es el arte de ordenar los volúmenes en un espacio, con armonía y gusto, guardando el orden y el sentido de la unidad.

      .tarjeta.color-light-blue.p-3(x="30%" y="48%" numero="+")
        .h5.mb-2 La creatividad 
        p Acorde con el momento, las costumbres, estilos de vida de los consumidores a persuadir, impresionar y satisfacer.

      .tarjeta.color-light-blue.p-3(x="10%" y="14%" numero="+")
        .h5.mb-2 La mercancía 
        p Es el protagonista de la vitrina, debe estar perfectamente expuesta, con el contraste de color acertado y con las proyecciones luminosas acertadas.

      .tarjeta.color-light-blue.p-3(x="43%" y="30%" numero="+")
        .h5.mb-2 La línea 
        p Conduce la mirada por toda la exposición de la vitrina.

    .h4 Material P.O.P.
    p.mb-4 El material P.O.P. es básicamente cualquier objeto o cosa que tenga un logo o emblema que represente una marca, empresa u organización que requiera que un público determinado la conozca. 
      span.etiqueta.text-bold P.O.P. es una sigla en inglés que significa #[i Point Of Purchase] es decir “Punto de Compra”. 
      | De este significado se desprende que el material P.O.P. no es más que aquel que impulsa de manera indirecta el reconocimiento de una marca o producto entre el consumidor.

    .row.align-items-center.mb-4
      .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img23.png')
      .col-lg-6.mb-0
        .cajon-b.color-acento-contenido.p-3.mb-5
          p.mb-0 Este concepto ha estado enmarcado entre diferentes opiniones y aportes de profesionales del #[i marketing]. Entre las diferentes definiciones y acuerdos que se han escrito, se toman como referencia algunos de ellos para describir esta importante estrategia de mercadeo:

    .h4 Definiciones de P.O.P.

    .row.mb-5
      .col-lg-5.mb-5.mb-lg-0
        .bloque-texto-b.color-primario.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            h2.mb-0 POPAI y Graphispack Asociación la definen como una “técnica del marketing (…) cuyo objetivo es llamar la atención sobre los detalles o características del producto (…) que otorgan un valor añadido al mismo sobre el resto de productos promocionados en el sitio en el que se puede comprar
            i.fas.fa-quote-right
            br
            p (Robles, 2009, p. 92).
      
      .col-lg-5.mb-5.mb-lg-0
        .bloque-texto-b.color-primario.p-4.mb-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            h2.mb-0 A pesar de ser en el punto de venta donde el consumidor toma la mayor parte de decisiones de compra, la publicidad en el punto de venta, continúa siendo la gran desconocida, aunque la venta impersonal, las grandes superficies comerciales y la alta competencia por la gran variedad de productos, han proliferado el uso de la misma
            i.fas.fa-quote-right
            br
            p Mahave (2003, p. 10) 
        p El #[i marketing] en el punto de venta (#[i marketing] at retail) enmarca un conjunto de técnicas que le ayudan el comerciante a atraer público en el mismo lugar donde se realiza la compra. 

      .col-lg-5.mb-5.mb-lg-0
        .bloque-texto-b.color-primario.p-4.mb-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            h2.mb-0 La una buena disposición del producto en el punto de venta, hace que la presentación del producto adquiera un “rol activo”, y sea más atractivo mediante “su colocación en el punto de venta, el fraccionamiento del producto, el envase y presentación y la exhibición del producto” 
            i.fas.fa-quote-right
            br
            p (Kotler, Bower y Makens, 2008).

    .row.mb-4
      .col-lg-8
        p La publicidad en el punto de venta continúa generando un vínculo entre el consumidor y la marca a través de una adecuada promoción de sus productos; y #[strong esta se divide en las siguientes clases]:

    .row.justify-content-center.mb-4
      .col-lg-3.col-sm-4.mb-4  
        img(src='@/assets/curso/tema2/img24.svg')(data-aos="fade-right")
      .col-lg-3.col-sm-4.mb-4
        img(src='@/assets/curso/tema2/img25.svg')(data-aos="flip-up")
      .col-lg-3.col-sm-4.mb-4
        img(src='@/assets/curso/tema2/img26.svg')(data-aos="fade-left")
      .col-lg-9.mb-4
        .tarjeta.color-light-red.p-4(data-aos="flip-up")
          p.mb-4 #[strong Puntual]: son aquellas que se realizan con el objeto de dar a conocer una promoción u oferta que tiene una duración determinada –menos de cuatro semanas– y que se realiza como algo extraordinario, es decir, que no entra dentro de la dinámica habitual del producto o servicio.
          p.mb-4 #[strong Estacional]: es aquella que se realiza para un periodo determinado generalmente caracterizado por unos altos índices de consumo de ese producto o servicio. Por ejemplo los juguetes en Navidad o las cremas solares en verano. Suelen tener una duración de entre tres y cuatro meses.
          p #[strong Fija]: es aquella que está fija en un punto de venta y que por lo tanto está fabricada con materiales menos flexibles, de mayor calidad y que mantienen sus cualidades pasado un tiempo prolongado.

    .row.justify-content-center.mb-4
      .col-lg-3.col-sm-4.mb-4  
        img(src='@/assets/curso/tema2/img24.svg')(data-aos="fade-right")
      .col-lg-3.col-sm-4.mb-4
        img(src='@/assets/curso/tema2/img25.svg')(data-aos="flip-up")
      .col-lg-3.col-sm-4.mb-4
        img(src='@/assets/curso/tema2/img26.svg')(data-aos="fade-left")
      .col-lg-9.mb-4
        .tarjeta.color-light-blue.p-4(data-aos="flip-up")
          p.mb-4 #[strong Fijos]: son aquellos materiales que pueden soportar un largo periodo de tiempo en el punto de venta sin perder calidad. Suelen ser madera, metal y plástico. Se utilizan para acciones de más de tres meses.
          p #[strong Temporales]: son materiales que se utilizan para acciones de pequeña duración o de escasa escala. Son retirados cuando se acaba el producto o las semanas marcadas por la agencia.

    .row.justify-content-center.mb-4
      .col-lg-3.col-sm-4.mb-4  
        img(src='@/assets/curso/tema2/img24.svg')(data-aos="fade-right")
      .col-lg-3.col-sm-4.mb-4
        img(src='@/assets/curso/tema2/img25.svg')(data-aos="flip-up")
      .col-lg-3.col-sm-4.mb-4
        img(src='@/assets/curso/tema2/img26.svg')(data-aos="fade-left")
      .col-lg-9.mb-4
        .tarjeta.color-light-yellow.p-4(data-aos="flip-up")
          p.mb-4 #[strong De marca]: el objetivo es generar recuerdo de marca o asociar un determinado producto a una firma. Para ello la PLV debe guardar una coherencia con la imagen de marca para generar corporatividad y asociación.
          p.mb-4 #[strong De producto o servicio]: su finalidad es promocionar un producto para diferenciarlo de la competencia o simplemente recordar la existencia del mismo.
          p.mb-4 #[strong Promoción]: destacar una oferta extraordinaria que aporta un valor distintivo y adicional al consumidor.
          p #[strong Lanzamiento]: su fin es promocionar un nuevo producto presentándolo al público y llamando la atención sobre el mismo para que se tenga conocimiento de su salida al mercado
    
    p.mb-4 De igual forma, la publicidad en el punto de venta puede clasificarse en tres categorías: según el tiempo de permanencia en el punto de venta, según los materiales y según el objetivo de comunicación.

    .tarjeta.color-light-blue.p-4.mb-5
      LineaTiempoC.color-acento-contenido(text-small)
        .row(titulo="Expositores semipermanentes")
          .col-md-6.mb-4.mb-md-0
            .h4 Expositores semipermanentes
            p Los expositores semipermanentes son pantallas que se ubican en un centro comercial, gran almacén o supermercado. Las pantallas suelen estar en este espacio entre tres meses o hasta un año y pueden ser parte de una campaña de lanzamiento o relanzamiento de un producto. También son conocidas como pantallas secundarias.
          .col-md-6
            img(src='@/assets/curso/tema2/img27.png')

        .row(titulo="Expositores permanentes")
          .col-md-6.mb-4.mb-md-0
            .h4 Expositores permanentes
            p.mb-4 Se refiere a expositores electrónicos o análogos que se ubican de forma permanente en un centro comercial, punto de venta o supermercado; también pueden encontrarse en paraderos de buses muy cercanos supermercados.
            p Usualmente son utilizados por grandes marcas que pueden cubrir los costos de mantenimiento.
          .col-md-6
            img(src='@/assets/curso/tema2/img28.png')

        .row(titulo="Display o glorificador")
          .col-md-6.mb-4.mb-md-0
            .h4 #[i Display] o glorificador
            p Este es uno de los elementos más comunes y exitosos de la publicidad en el punto de venta. Sus diseños son muy variados, se pueden presentar en diferentes formatos y materiales, aunque el más común es el cartón.
          .col-md-6
            img(src='@/assets/curso/tema2/img29.png')

        .row(titulo="Exhibidores de piso")
          .col-md-6.mb-4.mb-md-0
            .h4 Exhibidores de piso
            p.mb-4 Son una especie de estanterías en cartón o algún material fuerte, que permite exhibir el producto de forma llamativa y de fácil alcance para el usuario y brindando un valor agregado a la marca. 
            p El exhibidor de piso se utiliza, preferiblemente, para el lanzamiento o promoción de un producto teniendo como resultado un mayor impacto y aumento en las ventas.
          .col-md-6
            img(src='@/assets/curso/tema2/img30.png')

        .row(titulo="Rejillas")
          .col-md-6.mb-4.mb-md-0
            .h4 Rejillas
            p.mb-4 Las rejillas son usadas en el punto de venta en las esquinas o terminaciones de las estanterías, justo para “interrumpir” el tráfico visual de los consumidores.
            p También pueden aparecer al lado de las cajas registradores, justo antes de pagar por los productos que se llevan los consumidores. Son de larga duración y su éxito puede depender de la rotación del producto o los cambios en el surtido.
          .col-md-6
            img(src='@/assets/curso/tema2/img31.png')

        .row(titulo="Floor graphics")
          .col-md-6.mb-4.mb-md-0
            .h4 #[i Floor graphics]
            p Son una especie de calcomanía o papel adhesivo, con diseño atractivo y son impresos para aplicación en pisos. Llevan mensajes alusivos a la marca o producto que promocionan y, en algunos casos, señalan el entorno para guiar al usuario hacia alguna promoción.
          .col-md-6
            img(src='@/assets/curso/tema2/img32.png')

        .row(titulo="Puntas de góndola")
          .col-md-6.mb-4.mb-md-0
            .h4 Puntas de góndola
            p Las Puntas de Góndola (PDG) son elementos que contienen los productos a exhibir pero con visibilidades que aumentan la comunicación visual, con accesorios como son cabezotes, laterales, frontales, cenefas y partes móviles. Su desempeño es aumentar la visibilidad y posicionar la marca en el Punto de Venta (PDV), por lo tanto, son bastantes útiles y precisas para darle un toque más personal y sutil a distintos tipos de exhibiciones, con medios impresos diseñados especialmente para puntos de ventas, supermercados y contextos comerciales.
          .col-md-6
            img(src='@/assets/curso/tema2/img33.png')

        .row(titulo="Rompetráficos")
          .col-md-6.mb-4.mb-md-0
            .h4 Rompetráficos
            p Los rompetráficos publicitarios son elementos diseñados en cartón o plástico que se ponen principalmente en las estanterías de productos, son pequeños pero muy llamativos. Pueden encontrarse en pequeños comercios, así como en grandes superficies.
          .col-md-6
            img(src='@/assets/curso/tema2/img34.png')

        .row(titulo="Tecnología digital y otros")
          .col-md-7.mb-4.mb-md-0
            .h4 Tecnología digital y otros
            p.mb-4 Actualmente, con el auge de la tecnología digital, hay un mayor uso de pantallas táctiles, proyecciones de video, códigos QR, incluso hay pantallas dinámicas en las que se puede realizar la compra directa del producto a través de los canales digitales, pero en el punto de venta. Este último, conlleva un acompañamiento o soporte técnico en caso de que haya algún inconveniente.
            p.mb-4 Otros soportes o piezas publicitarias para el punto de venta son:
            .row
              .col-11
                ul.lista-ul--color
                  li 
                    i.fas.fa-check-circle
                    | Los carteles “clásicos” de interior o exterior.
                  li 
                    i.fas.fa-check-circle
                    | Pantallas digitales (pasillos de centros comerciales, puntos de venta de video lineales, pantallas de efectivo, etc.).
                  li 
                    i.fas.fa-check-circle
                    | Delimitadores.
                  li 
                    i.fas.fa-check-circle
                    | Expositores de mostrador y de suelo.
                  li 
                    i.fas.fa-check-circle
                    | Vinilos.
                  li 
                    i.fas.fa-check-circle
                    | Folletos.
          .col-md-4
            img(src='@/assets/curso/tema2/img35.png')
    
    p.mb-4 Como se mencionó anteriormente, la publicidad en el punto de venta (P.O.P.) se usa para promover la venta del producto hacia el consumidor (#[i marketing] de empuje), brindar información complementaria y generar un canal de comunicación. Su presencia puede ser decisiva en el acto de compra.
    p.text-bold.mb-4 Para que el material P.O.P. cumpla con los objetivos de la marca, se recomienda:

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 8
      span #[i Recomendaciones para el uso del P.O.P.]
    
    .row.justify-content-center.mb-4
      .col-lg-10
        LineaTiempoB.color-primario.mb-5(:datos="datosLineaTiempoB")
    
    p.mb-4 Finalmente, las acciones de #[i marketing] en el punto de venta deben centrarse en generar un estímulo en el consumidor, entendiendo el estímulo como “agente físico, químico, mecánico, etc., que desencadena una reacción funcional en un organismo” (RAE, 2020). Es por ello que la publicidad en el punto de venta se debe encargar especialmente de estimular los sentidos de los consumidores.
    separador
        
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    datosLineaTiempoB: [
      {
        titulo: 'Análisis de la competencia',
        texto:
          'Realizar un análisis de la competencia siempre será una buena opción para generar ideas innovadoras.',
        icono: require('@/assets/curso/tema2/img36.svg'),
      },
      {
        titulo: 'Benchmarking',
        texto:
          'Con el mercado en constante evolución, es importante estar siempre un paso adelante. Por eso, hay que pensar en estrategias a corto y a largo plazo.',
        icono: require('@/assets/curso/tema2/img37.svg'),
      },
      {
        titulo: 'Conocimiento del producto',
        texto:
          'Tener claro cuál es la categoría que se está manejando para no afectar la proyección de la imagen.',
        icono: require('@/assets/curso/tema2/img38.svg'),
      },
      {
        titulo: 'Beneficios del producto',
        texto:
          'Los mensajes en la publicidad en el punto de venta, deben enviar un mensaje al consumidor con los beneficios del producto, modo de uso, fecha de vencimiento, etc. para brindar una mayor confianza en la compra.',
        icono: require('@/assets/curso/tema2/img39.svg'),
      },
      {
        titulo: 'Buen diseño',
        texto:
          'Es muy importante enfocar el desarrollo de la estrategia POP en la línea de diseño, así el cliente podrá reconocer la marca de manera fácil pues le es atractiva.',
        icono: require('@/assets/curso/tema2/img40.svg'),
      },
      {
        titulo: 'Destacado',
        texto: 'Procurar que la publicidad en el punto de venta se destaque.',
        icono: require('@/assets/curso/tema2/img41.svg'),
      },
      {
        titulo: 'No saturar',
        texto:
          'A pesar que es una publicidad muy importante para cada producto, se recomienda no saturar demasiado el punto de venta',
        icono: require('@/assets/curso/tema2/img42.svg'),
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
