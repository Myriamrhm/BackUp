<template>
<div>
    <div id="contenu">
        <section>
        <p>Brit Rock</p>
        <router-link to="/brit"><img class="img" src="../assets/CatBrit.jpg" alt=""></router-link>
        </section>
        <section>
        <p>New Indie/Rock</p>
        <router-link to="/indie"><img class="img" src="../assets/Categorie2.jpg" alt=""></router-link>
        </section>
        <section>
        <p>Chill</p>
        <router-link to="/partie"><img class="img" src="../assets/ChillCat.jpg" alt=""></router-link>
        </section>
        <section>
        <p>Band Eighties</p>
        <router-link to="/eighties"><div class="bloc"></div></router-link>
        </section>
        <section>
        <p>Hits Eighties</p>
        <div class="bloc"></div>
        </section>
        <section>
        <p>Get Down (dance)</p>
        <router-link to="/funk"><img class="img" src="../assets/Funk.jpg" alt=""></router-link>
        </section>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
#contenu{
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-left: 100px;
    margin-right: 100px;
}
p{
    // margin-top: 120px;
    font-size: 140%;
    font-family: 'Open Sans', sans-serif;
    font-weight: 700;
    background-color: rgba(0, 0, 0, 0.342);
    border-radius: 3px;
    margin-top: 25%;
}
.img{
    width: 220px;
    height: 220px;
    box-shadow: 8px 8px rgba(255, 255, 255, 0.404);
}
.img:hover{
    transform: scale(1.01);
    outline-style: solid;
    outline-color: rgb(187, 187, 187);
    outline-offset: 15px;
}
.bloc{
    width: 220px;
    height: 220px;
    background-color: darkcyan;
}


</style>
