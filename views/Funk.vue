<template>
    <div class="funk">
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <h1>Qui est l'interprete de cette chanson ?</h1>
        <Countdown></Countdown>
        <BritC></BritC>
        <TuneFunk></TuneFunk>

    </div>
</template>

<script>

import BritC from '@/components/BritComponent.vue'
import Countdown from '@/components/countdown.vue'
import TuneFunk from '@/components/TuneFunk.vue'

export default {
  components: {
    BritC,
    Countdown,
    TuneFunk
  }
}
</script>

<style lang="scss" scoped>
.funk{
    background: url("../assets/Break.jpg");
    background-size: cover;
    height: 1200px;
    width: auto;
    margin-top: -82px;
    margin-right: -8px;
    margin-left: -8px;
}
h1{
    font-family: 'Open Sans', sans-serif;
    font-weight: 900;
    font-size: 160%;
}
</style>
