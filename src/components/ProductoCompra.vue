<template>
   
    <section id="producto_compra">

        <h1 id="titulo">Teclado mecánico AK33</h1>

        <p>Precio: <span class="precio">45,99€</span></p>

        <form>
            <label for="cantidad">Cantidad:  </label>
            <button @click="cambiarContador('-1')" type="button" name="button">-</button>
            <input type="text" :value="contador" name="cantidad"/>
            <button @click="cambiarContador('1')" type="button" name="button">+</button>
        </form>

        <button class="boton_compra"> <span class="material-icons">shopping_cart</span> AÑADIR A LA CESTA</button>

    </section>
    
</template>

<script>
export default {
    Name: 'ProductoCompra',
    data () {
        return {
            contador: 1
        }
    },
    methods: {
        cambiarContador(num){
            this.contador += +num;
            if(!isNaN(this.contador) && (this.contador < 0)) {
                this.contador = 0
            }
        }
    }

}
</script>

<style>
#producto_compra #titulo {
    font-size:2rem;
}

#producto_compra .precio {
    font-weight: 600;
    font-size:1.4rem;
    color:#ff6000;
}

#producto_compra .boton_compra {
    margin-top: 2rem;
    background-color: #ff6000;
    font-size:1.5rem;
    font-weight: 600;
    color: #333;
    cursor:pointer;
    border:none;
    border-radius: 18px;
    padding:1rem;

}

#producto_compra form input {
    width:2rem;
    text-align:center;
    border: 1px solid #d8d8d8;
    font-size: 1rem;
    height:2rem;
}
#producto_compra form button {
    height:2.3rem;
    width:2rem;
    border: 1px solid #d8d8d8;
}

</style>