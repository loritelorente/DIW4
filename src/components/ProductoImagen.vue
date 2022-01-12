<template>
   
    <section id="producto">

        <section class="imagenes_muestra">
            <a @click="cambiarFoto(1)"><img v-bind:src="fotos[1]" alt="Teclado mecánico AK33" copyright="cc-by amazon" /></a>
            <a @click="cambiarFoto(2)"><img v-bind:src="fotos[2]" alt="Teclado mecánico AK33" copyright="cc-by amazon" /></a>
            <a @click="cambiarFoto(3)"><img v-bind:src="fotos[3]" alt="Teclado mecánico AK33" copyright="cc-by amazon" /></a>
            <a @click="cambiarFoto(4)"><img v-bind:src="fotos[4]" alt="Teclado mecánico AK33" copyright="cc-by amazon" /></a>
        </section>

        <div class="principal"> 
            <img v-bind:src="fotos[0]"  alt="Teclado mecánico AK33" copyright="cc-by amazon"/>
        </div>

    </section>
    
</template>

<script>
export default {
    Name: 'ProductoImagen',
    data () {
        return {
            fotos: [
                require ("../assets/img1.jpg"),
                require ("../assets/img1.jpg"),
                require ("../assets/img2.jpg"),
                require ("../assets/img3.jpg"),
                require ("../assets/img4.jpg")
            ]
        }
    },
    methods: {
        cambiarFoto(id) {
            this.fotos[0] = this.fotos[id]
        }
    }

}
</script>

<style>

#producto  {
    display: flex;
    justify-content: center;
    align-items: center;
}

#producto .imagenes_muestra {
    display:flex;
    flex-direction: column;
}
#producto .imagenes_muestra img{
    border: 1px solid #d8d8d8;
    width:8rem;
}
#producto .principal {
    padding-left:1rem;
}
#producto .principal img{
    width:35rem;
    height: 25rem;
}


</style>