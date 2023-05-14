<template>
    <div class="nav">

       <div class="item home">
        <span><NuxtLink to="/">Strona domowa</NuxtLink></span>
       </div>
       <div class="item onas">
        <span><NuxtLink to="/onas">O nas</NuxtLink></span>
       </div>

    </div>
</template>

<script>

</script>
<style scoped>
.nav {
    display: flex;
    border-bottom: 5px solid red;
    background-color: rgb(0, 110, 255);
    color: white;
    height: 70px;
    width: 100%;
    min-height: 70px;
    max-width: 100vw;
    min-width: 200px;
    flex-wrap: wrap;
}

.item{
    font-size: 24;
    align-self: center;
    text-decoration: none;
    margin-right: 20px;
    
}

.home {

}

/* px, rem, em, vh, vw, % */
.onas {

}
</style>