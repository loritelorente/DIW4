<template>
    <header id="Cabecera">
        <img src="../assets/logo.svg" alt="logo empresa" copyright="cc-by graphicsprings" id="logo"/>

        <nav>
            <ul>
                <li><a href="#">INICIO</a></li>
                <li><a href="#">ORDENADORES</a></li>
                <li><a href="#">MÓVILES</a></li>
                <li><a href="#">PERIFÉRICOS</a></li>
            </ul>
        </nav>

        <form @submit.prevent="handleEnviar">
            <input type="text" placeholder="Buscar productos...">
            <button><span class="material-icons">search</span></button>
        </form>

        <ul>
            <li><a href="#">REGISTRO</a></li>
            <li><a href="#">INICIAR SESIÓN</a></li>
        </ul>

        <a href="#" class="carrito"><span class="material-icons">shopping_cart</span></a>

    </header>
</template>

<script>
export default {
    name: 'Cabecera',
    methods: {
        handleEnviar(){
            console.log("Busqueda enviada");
        }
    }

}
</script>

<style>

#Cabecera {
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #ff6000;
    padding:0.5rem 0;
}

#logo {
    width: 6rem;
}

#Cabecera ul {
    display: flex;
    list-style: none;
    margin: 0rem 0.5rem;
    padding: 0;
}

#Cabecera ul li a {
    color: #333;
    font-weight: 900;
    text-decoration: none;
    padding-right: 1rem;
    padding-left: 1rem;
}

#Cabecera ul li a:hover {
    color: #ff6000;
    background-color: #333;
    border-radius: 10px;
}

#Cabecera form {
    display: flex;
    justify-content: center;
    align-items: center;
    flex: 0 1 30%;
}

#Cabecera form input {
    border-style: solid;
    outline: none;
    border-radius: 15px;
    font-size:1.2rem;
}
#Cabecera form button {
    margin-left:0.5rem;
    border-radius: 15px;
    border: none;
    cursor:pointer;
}

#Cabecera .carrito {
    text-decoration: none;
    color: #333;
    border:0.5rem solid transparent;
    flex: 0 1 1%;
}

#Cabecera .carrito:hover {
    color: #ff6000;
    background-color: #333;
    border-radius: 30px;
    border:0.5rem solid #333;
}

</style>