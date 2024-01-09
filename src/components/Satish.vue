<template>
    <div class="satish-main-container">
        <div class="satish-review">
            <p class="satish-review-p">Fylo has improved our team productivity by an order of magnitude.
                Since making the switch our team has become a well-oiled collaboration machine.
            </p>
        </div>
        <div class="satish-profile">
            <div class="satish-image-container">
                <img src="../assets/images/profile-1.jpg" alt="" class="satish-image">
            </div>
            <div class="satish-info">
                <p class="satish-info-h5" style="font-family: 'Raleway', sans-serif; font-weight:700;">Satish Patel<br><small class="satish-info-h6" style="font-family: 'Open Sans', sans-serif;">Founder & CEO, Huddle</small></p>
            </div>
        </div>
    </div>
</template>
<style scoped>

.satish-main-container{
    padding:2vh 2vw;
    margin-bottom:2vh;
    background-color:hsl(217, 28%, 15%);
}
.satish-profile{
    display:flex;
    gap:1vw;
}
.satish-image-container{
    display:flex;
}
.satish-image{
    width:30px;
    border-radius:100px;
    margin:auto 0;
}

.satish-info-h6{
    font-weight:400;
    color:hsla(0, 0%, 100%, 0.671);
}
.satish-review-p{
    font-family: 'Open Sans', sans-serif;
    font-weight:400;
    color:hsla(0, 0%, 100%, 0.671);
}
</style>