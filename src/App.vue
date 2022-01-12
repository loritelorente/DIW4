<template>
  <Cabecera/>
  <Breadcrumb/>
  <div class="dos_columnas">
    <ProductoImagen/>
    <ProductoCompra/>
  </div>
  <ProductoDescripcion/>
</template>

<script>
import Cabecera from './components/Cabecera.vue'
import Breadcrumb from './components/Breadcrumb.vue'
import ProductoImagen from './components/ProductoImagen.vue'
import ProductoCompra from './components/ProductoCompra.vue'
import ProductoDescripcion from './components/ProductoDescripcion.vue'

export default {
  name: 'App',
  components: {
    Cabecera,
    Breadcrumb,
    ProductoImagen,
    ProductoCompra,
    ProductoDescripcion
  }
}


</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap');

body {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}

.dos_columnas {
  padding-top:4rem;
  display: flex;
  align-content: center;
  justify-content: space-around;
  flex-wrap:wrap;
}

</style>

