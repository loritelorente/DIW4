<template>
   
    <section id="breadcrumb">

        <a href='#' > Inicio </a> >
        <a href='#' > Periféricos </a> >
        <a class='actual' href='#' > Teclado mecánico </a>

    </section>
    
</template>

<script>
export default {

}
</script>

<style>

#breadcrumb  {
    margin-left: 2rem;
    display: flex;
    color: #ff6000;
    padding-top:2rem;
    align-items: center;
}

#breadcrumb a{
    font-size: 1.2rem;
    margin-left: 1rem;
    margin-right:1rem;
    color: #ff6000;
}

#breadcrumb a.actual {
    font-weight: 600;
}

</style>