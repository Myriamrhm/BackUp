<template>
<div>
<div id="parent">
    <div class="block"></div>
    <div class="block"></div>
    <div class="block"></div>
    <div class="block"></div>
</div>
</div>
    
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
#parent{
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}
.block{
    background-color: rgba(255, 255, 255, 0.596);
    width: 180px;
    height: 180px;
    margin-left: 2%;
    margin-right: 2%;
    border-radius: 3px;
    box-shadow: 8px 8px rgba(255, 255, 255, 0.342);
    margin-top: 5%;
}
.block:hover{
    background-color: rgba(255, 255, 255, 0.705);
}

</style>
