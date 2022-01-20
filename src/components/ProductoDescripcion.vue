<template>
   
    <section id="producto_descripcion">

     <div class="descripcion">

         <h1>DESCRIPCIÓN DEL PRODUCTO</h1>

         <ul>
             <li>【Interruptor: el núcleo del teclado mecánico】 Cada botón del teclado mecánico AK33 tiene un interruptor independiente para controlar, y las pulsaciones de las teclas son fuertes, dando como resultado una sensación especial para el entretenimiento del juego. Hay dos tipos de interruptores para elegir, el azul y el negro. </li>
             <li>【Design Diseño simple de 82 teclas】 Seleccione los botones que se usan comúnmente, sin cambiar los hábitos de operación, cree este teclado mecánico de 82 teclas, que le dará al ratón derecho la actividad completa, que es una subversión de la estructura, la visión al espacio. </li>
             <li>【Cree una tapa de botón ergonómica pura】 Para el uso común de los juegos de teclado, utilizando la altura R5, tendrá una velocidad de respuesta más rápida en el juego, la disposición alta y baja, reducirá la fatiga de los dedos. </li>
             <li>【Conveniente y rápido】 El teclado blanco tiene una luz de fondo azul única, y el teclado negro tiene una luz de fondo blanca, que es muy adecuado para el uso nocturno. Diseño de cable USB independiente, todo para la comodidad del reproductor para usar y transportar.</li>
             <li>【Durabilidad y compatibilidad】 Llave de caracteres de tallado por láser para un uso prolongado. Fabricado en ABS de primera calidad y material metálico, con textura de acabado mate, es resistente y robusto. Compatibilidad con sistemas informáticos, incluidos Windows10, Windows 8, Windows 7, Mac OS X, Windows XP, Windows VISTA, etc. </li>
         </ul>
     </div>

         <video controls="controls" preload="auto" poster="../assets/miniatura.jpg">
             <source src="../assets/video.mp4" type="video/mp4" />
         </video>

    </section>
    
</template>

<script>
export default {


}
</script>

<style>
#producto_descripcion  {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    align-items: center;
    padding:2rem;
}

#producto_descripcion .descripcion {
    padding-right: 3rem;
    flex: 0 1 65%;
}

#producto_descripcion .descripcion h1 {
    color: #ff6000;
}

#producto_descripcion .descripcion ul  {
    list-style-type:disc;
}

#producto_descripcion .descripcion ul li {
    margin-bottom: 0.5rem;
}

#producto_descripcion  video {
    padding-top:2rem;
    height:15rem;

}

</style>