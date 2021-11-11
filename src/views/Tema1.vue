<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 #[i Merchandising]
    
    p.mb-4 El #[i merchandising] es considerado, según Pérez, Pérez y Cristo (2018), como una técnica que incentiva la compra mediante la interacción del cliente con el producto. Las técnicas de comercialización han adquirido gran importancia en los puntos de venta para lograr la satisfacción con el cliente mediante incentivos de venta, lo que puede llamarse #[i merchandising] de seducción y el #[i merchandising] de gestión o de visualización.

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img01.png')})`}"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 El término #[i merchandising] se puede dividir en dos partes, #[i «merchandise»], que significa mercancía o mercadería, y la terminación «-ing», que significa acción. En este sentido, puede decirse que es el mercado en acción o producto en acción; dicho en otras palabras, el #[i merchandising] es el movimiento de la mercancía hacia el consumidor en el punto de venta.

    p.mb-4 Otros autores definen el #[i merchandising] de la siguiente forma:
    
    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/img02.svg')
      .tarjeta.color-acento-botones.p-3(x="17%" y="95%" numero="1")
        p “Conjunto de técnicas coordinadas entre fabricante y distribuidor, aplicadas en el punto de venta para motivar el acto de compra de la forma más rentable para ambos, satisfaciendo las necesidades del consumidor” Asociación Española de Codificación Comercial (Fernández y Pastor, 2007). 
      .tarjeta.color-acento-contenido.p-3(x="52%" y="95%" numero="2")
        p “El #[i merchandising] es la implantación y el control necesario para la comercialización de bienes y servicios, en los lugares, en los momentos, en los precios en las cantidades susceptibles de facilitar la consecución de los objetivos de #[i marketing] de la empresa” American #[i Marketing] Association. (Fernández y Pastor, 2007). 

      
      .tarjeta.color-primario.p-3(x="87%" y="95%" numero="3")
        p “El #[i marketing] evoluciona para estimular la intención de compra (el #[i merchandising]) para provocar el deseo de poseer o consumir el producto a través de un escenario con una atmósfera adaptada a la mente del consumidor” (Palomares, 2009).
      
    .cajon.color-primario.p-4.mb-4(data-aos="fade-right")
      p.mb-4 El #[i merchandising], entonces, se puede definir como una técnica del #[i marketing] aplicada y desarrollada a fabricantes y distribuidores dirigida a estimular el deseo y producir la compra. Ahora bien, desde la perspectiva de la comunicación visual, el #[i merchandising] busca influir en el público a través de los sentidos, teniendo en cuenta que las personas reciben estímulos a través de los sentidos en 80% visuales, 10% estímulos sonoros y el otro 10% entre el tacto, olfato y gusto.
      p Como técnica del #[i marketing], siempre se buscará la #[strong rentabilidad, disponibilidad, impacto, precio y exhibición].

    p.mb-4 No obstante, esta técnica comercial comenzó con el surgimiento de los puntos de ventas modernos, en los que se aplicaban diversas acciones de visualización de los productos para potenciar la mercadería, así como la rápida rotación de inventarios. #[strong De esta manera, se destacan los siguientes hitos]:

    .tarjeta.color-curuba.p-4.mb-5
      LineaTiempoC.color-acento-contenido(text-small)
        .row.justify-content-center(titulo="1840")
          .col-md-8.mb-4.mb-md-0
            p Pequeños almacenes pudieron llevar el escaparatismo como escenario, el producto se exponía sin orden. 
        .row.justify-content-center(titulo="1852")
          .col-md-8.mb-4.mb-md-0
            p Nacimiento del gran almacén en Francia.
        .row.justify-content-center(titulo="1878")
          .col-md-8.mb-4.mb-md-0
            p Origen de los almacenes populares en los EE. UU.
        .row.justify-content-center(titulo="1920")
          .col-md-8.mb-4.mb-md-0
            p Con la aparición del mercadeo, el escaparatismo se basaba en estudios de mercado y del consumidor.
        .row.justify-content-center(titulo="1930")
          .col-md-8.mb-4.mb-md-0
            p Nacimiento de los supermercados en los EE. UU.
        .row.justify-content-center(titulo="1950-1960")
          .col-md-8.mb-4.mb-md-0
            p Se fortaleció el diseño en los escaparates.
        .row.justify-content-center(titulo="1970")
          .col-md-8.mb-4.mb-md-0
            p El escaparate se convierte en el centro de la venta.
        .row.justify-content-center(titulo="1980")
          .col-md-8.mb-4.mb-md-0
            p Se utiliza el término #[i merchandising] en los grandes almacenes.
        .row.justify-content-center(titulo="1990")
          .col-md-8.mb-4.mb-md-0
            p Se comienza con el  “minimalismo”, centrado en la venta de un único producto.
        .row.justify-content-center(titulo="Hoy")
          .col-md-8.mb-4.mb-md-0
            p Hoy día, se puede decir que el escaparate o exhibidor es el principal vendedor del producto en el punto de venta, porque logra que el cliente se detenga y le motive diferentes percepciones, haciendo que más personas ingresen al punto de venta.

    p.mb-4 El #[i merchandising], como parte del proceso de comunicación, presenta la interacción entre dos elementos básicos, el punto de venta, la marca o el comerciante, con el cliente o comprador. Se ha convertido en una parte fundamental activa y dinámica de la estrategia de la empresa, en el que se tienen los siguientes alcances:

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 1
      span #[i Objetivos del merchandising]
    
    figure.mb-4(data-aos="flip-up")
      img(src='@/assets/curso/tema1/img03.svg')
    
    p.mb-4 De acuerdo con su definición y objetivos, se puede determinar que #[strong la principal función del] #[i merchandising] #[strong es colocar, impulsar, hacer seguimiento y actualizar los productos, su exhibición y su publicidad].
    p.mb-4 Entre las funciones del #[i merchandising] se encuentran las siguientes:

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 2
      span #[i Objetivos del merchandising]
    
    ImagenInfografica.color-acento-contenido.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/img04.svg')
      .tarjeta.color-acento-botones.p-3(x="60%" y="15%" numero="A")
        p Presentar óptimamente el producto en la estantería o góndola.
      .tarjeta.color-acento-botones.p-3(x="60%" y="30%" numero="B")
        p Disponer los productos para los clientes de acuerdo con el espacio en la vitrina.
      .tarjeta.color-acento-botones.p-3(x="60%" y="45%" numero="C")
        p Integridad en el suministro del producto para que lo seleccione el cliente.
      .tarjeta.color-acento-botones.p-3(x="60%" y="60%" numero="D")
        p Planificar el área de la sala de negociación o espacio para la distribución del producto.
      .tarjeta.color-acento-botones.p-3(x="60%" y="75%" numero="E")
        p Destacar el producto frente a la competencia en la vitrina o estantería.
      .tarjeta.color-acento-botones.p-3(x="60%" y="90%" numero="F")
        p Uso adecuado del espacio en la estantería.

    p.mb-4 Sin embargo, existe otro el elemento del #[i merchandising] que es importante destacar y es la relación entre el fabricante y distribuidor, en donde el distribuidor debe convertirse en un socio estratégico, con la capacidad de difundir las bondades del producto y de la marca para atraer más consumidores al punto de venta, elemento que se combina con la publicidad del producto.
    p.text-bold De ahí que se encuentren otras funciones que cumple el #[i merchandising] a partir de los diferentes públicos, tal y como se aprecia a continuación.

    .row.justify-content-center
      .col-md-9.mb-4
        img(src='@/assets/curso/tema1/img05.svg')(data-aos="flip-up")   
    
    .h4 Clases y tipos de #[i merchandising]

    p.mb-4 No hay clasificaciones absolutas en el mundo del #[i marketing], teniendo en cuenta que algunos autores y expertos lo clasifican de diferentes maneras. De acuerdo con el ciclo de vida del producto, existen cuatro clases de #[i merchandising]: de nacimiento, de ataque, de mantenimiento y de defensa; cada uno conlleva unas actividades relacionadas con el producto, así:

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 3
      span #[i Clases de #[i merchandising]]

    figura.mb-4
      img(src='@/assets/curso/tema1/img06.svg')(data-aos="flip-up") 
    
    p.mb-4 De la misma forma, hay clases de #[i merchandising] en relación con el ciclo de vida del producto. Existen diferentes clases de productos para cada una de las necesidades de los consumidores que, de acuerdo con sus motivaciones, los pueden adquirir en cualquier momento. Es importante identificar en el punto de venta cuáles productos pueden clasificarse en alguna de estas categorías:

    PasosA.color-primario.mb-5(tipo="n")
      .row
        .col-md-6.mb-4.mb-md-0
          h3 Productos de atracción
          p Son los más vendidos y deben distribuirse en todo el establecimiento para que el consumidor lo pueda recorrer.
        .col-md-6(data-aos="fade-left")
          img(src='@/assets/curso/tema1/img07.png')
      .row
        .col-md-6.mb-4.mb-md-0(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img08.png') 
        .col-md-6
          h3 Productos de compra racional e irracional
          p Los de compra irracional (impulsiva), es mejor situarlos en cajas. Los productos de compra racional (reflexiva) deben estar en una zona amplia y que no genere tensiones. 
      .row
        .col-md-6.mb-4.mb-md-0
          h3 Productos complementarios
          p Son productos que complementan a otros, por ejemplo, el café puede ser complementario de la leche o viceversa. Estos productos deben situarse en secciones seguidas.
        .col-md-6(data-aos="fade-left")
          img(src='@/assets/curso/tema1/img09.png') 

    .cajon.color-primario.p-4.mb-4(data-aos="fade-right")
      p.mb-4 Combinando las dos clasificaciones anteriores, clases de #[i merchandising] y clases de productos, deben tenerse en cuenta los siguientes factores:
      .row.justify-content-center.mb-4
        .col-lg-10
          ul.lista-ul--color
            li 
              i.fas.fa-check-circle
              p 
                strong La manipulación de los productos
                | : si el producto es pesado, debe colocarse en un lugar que privilegie la comodidad para seleccionarlo y transportarlo, así mismo, almacenarlo en el punto de venta.
            li 
              i.fas.fa-check-circle
              p 
                strong La conservación de los productos
                | : si el producto debe permanecer refrigerado, congelado, a temperatura ambiente o con higienización especial.

      p.mb-4 Finalmente, es importante ponerlos en un espacio que facilite el surtido y la rotación.
      p.mb-4 Ahora bien, adicional a las clases, se pueden identificar dos tipos de #[i merchandising], el visual y el de gestión.

      .h4 #[i Merchandising] visual
      p.mb-4 El #[i merchandising] visual aprovecha la ubicación, el recorrido y la distribución del producto en el punto de venta para motivar la venta, sea irracional (impulsiva) o racional (reflexiva). Un buen diseño del espacio permite exhibir el producto estratégicamente para que siempre esté al alcance del cliente para que cumpla un propósito en la decisión de compra.

    .row.justify-content-center
      .col-md-9.mb-4(data-aos="flip-up")
        figure
          img(src='@/assets/curso/tema1/img10.svg')
          figcaption Tomado de Mundo constructor (2019).
  
    p.mb-4 En el #[i merchandising] visual también se tienen en cuenta factores como la decoración del establecimiento, las áreas de exposición, tamaño, iluminación, entre otros.

    .h4 #[i Merchandising] de gestión
    p.mb-4 Se denomina #[i merchandising] de gestión porque apoya sus decisiones basado en cuatro áreas fundamentales: estudio del mercado, gestión del espacio, gestión del surtido y la comunicación en el punto de venta. Este tipo de #[i merchandising] conlleva los siguientes procesos:

    .row.justify-content-center
      .col-md-3.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img11.svg')
      .col-md-3.mb-4(data-aos="flip-up")
        img(src='@/assets/curso/tema1/img12.svg')
      .col-md-3.mb-4(data-aos="flip-up")
        img(src='@/assets/curso/tema1/img13.svg')
      .col-md-3.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img14.svg')

    p.mb-4 Un buen análisis y estudio del mercado, junto con la política comercial, una política clara de surtido y las políticas de comunicación, traen consigo la satisfacción del cliente y el camino para obtener una mayor rentabilidad del punto de venta.

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-left")
      h5 Figura 4
      span #[i Funciones de la gestión estratégica]
    
    figure.mb-4(data-aos="flip-up")
      img(src='@/assets/curso/tema1/img15.svg') 

    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-3.mb-4.mb-lg-0
          h2.text-white.mb-0 #[i Merchandising] 
        .col-lg-9(data-aos="fade-right")
          .bloque-texto-a__texto.p-4
            p Para profundizar en el tema de #[i merchandising], se puede consultar el documento Estrategias de innovación en el #[i merchandising] en el capítulo 3, que se encuentra en el material complementario.
    

</template>

<script>
export default {
  name: 'Tema1',
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
