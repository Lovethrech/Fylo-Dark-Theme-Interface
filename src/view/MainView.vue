<script setup>
import MainHeader from "../components/MainHeader.vue";
import SemiHeader from "../components/SemiHeader.vue";
import SectionedArea from "../components/SectionedArea.vue";
import ProductiveSection from "../components/ProductiveSection.vue";
import ReviewStage from "../components/ReviewStage.vue";
import News from "../components/News.vue";
import Footer from "../components/Footer.vue";
</script>

<template>
    <div class="main-view-container">
        <div class="head-section">
            <MainHeader></MainHeader>
            <SemiHeader></SemiHeader>
        </div>
        <div class="main-section">
            <SectionedArea></SectionedArea>
            <ProductiveSection></ProductiveSection>
            <ReviewStage></ReviewStage>
        </div>
        <div class="news">
            <News></News>
        </div>
        <Footer></Footer>
    </div>
</template>
<style scoped>
.head-section{
    background: url("../assets/images/bg-curvy-desktop.svg") hsl(217, 28%, 15%)  bottom/100vw auto no-repeat;
}
.main-section{
    background-color:  hsl(218, 28%, 13%);
    color:hsl(0, 100%, 100%);
    padding: 0 0 10vh;
}
.news{
    background: linear-gradient(to bottom, hsl(218, 28%, 13%) 50%, hsl(216, 53%, 9%) 50%);
    padding: 5vh 5vw;
    margin:0;
}
@media screen and (max-width:850px){
    .news{
        padding:1vh 5vw;
    }
   
}
</style>