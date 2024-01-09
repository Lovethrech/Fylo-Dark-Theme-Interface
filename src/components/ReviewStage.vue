<script setup>
import Satish from "../components/Satish.vue";
import Bruce from "../components/Bruce.vue";
import Iva from "../components/Iva.vue";
</script>

<template>
    <div class="review-stage-main-container">
        <Satish></Satish>
        <Bruce></Bruce>
        <Iva></Iva>
    </div>
</template>
<style scoped>
.review-stage-main-container{
    margin:15vh 5vw 0;
    display:flex;
    gap:2vh;
    padding-top:40px;
    background: url("../assets/images/bg-quotes.png") hsl(218, 28%, 13%) top left/50px auto no-repeat;
}

@media screen and (max-width:850px){
    .review-stage-main-container{
        flex-direction: column;
        margin:10vh 10vw;
    }
}
</style>