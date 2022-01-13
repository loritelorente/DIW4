<template>
   
    <section id="pie">

        <ul>
            <li class="cabecera">Por qué comprar</li>
            <li><a href="#">Cómo comprar</a></li>
            <li><a href="#">Formas de pago</a></li>
            <li><a href="#">Gastos de envio</a></li>
            <li><a href="#">Preguntas frecuentes</a></li>
            <li><a href="#">Opiniones de clientes</a></li>
        </ul>

        <ul>
            <li class="cabecera">Quiénes somos</li>
            <li><a href="#">Quiénes somos</a></li>
            <li><a href="#">Nuestras tiendas</a></li>
            <li><a href="#">Condiciones de compra</a></li>
            <li><a href="#">Marcas</a></li>
            <li><a href="#">Afiliados</a></li>
            <li><a href="#">Privacidad</a></li>
        </ul>

        <ul>
            <li class="cabecera">Contactar</li>
            <li><a href="#">Contacto</a></li>
            <li><a href="#">Devoluciones y garantías</a></li>
            <li><a href="#">Trabaja con nosotros</a></li>
            <li><a href="#">Centro de soporte</a></li>
        </ul>

        <ul>
            <li class="cabecera">Redes Sociales</li>
            <li><a href="#">Instagram</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Youtube</a></li>
        </ul>
    

    </section>
    
</template>

<script>
export default {


}
</script>

<style>

#pie{
    background-color: #333;
    display:flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding-top: 1rem;
}

#pie ul {
    list-style-type: none;
}

#pie ul li {
    padding-bottom: 1.5rem;
}

#pie ul li a {
    text-decoration: none;
    color: #ff6000;
}

#pie ul .cabecera {
    padding-bottom: 2rem;
    font-weight: 700;
    color: #ff6000;
}


</style>