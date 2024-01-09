<template>
    <div class="bruce-main-container">
        <div class="bruce-review">
            <p class="bruce-review-p">Fylo has improved our team productivity by an order of magnitude.
                Since making the switch our team has become a well-oiled collaboration machine.
            </p>
        </div>
        <div class="bruce-profile">
            <div class="bruce-image-container">
                <img src="../assets/images/profile-2.jpg" alt="" class="bruce-image">
            </div>

            <div class="bruce-info">
                <p class="bruce-info-h5" style="font-family: 'Raleway', sans-serif; font-weight:700;">Bruce McKenzie<br><small class="bruce-info-h6" style="font-family: 'Open Sans', sans-serif;">Founder & CEO, Huddle</small></p>
            </div>
        </div>
    </div>
</template>
<style scoped>
.bruce-main-container {
    padding: 2vh 2vw;
    margin-bottom: 2vh;
    background-color: hsl(217, 28%, 15%);
}

.bruce-profile {
    display: flex;
    gap: 1vw;
}
.bruce-image-container{
    display:flex;
}
.bruce-image {
    width: 30px;
    border-radius: 100px;
    margin: auto 0;
}

.bruce-info-h6 {
    font-weight:400;
    color:hsla(0, 0%, 100%, 0.671);
}
.bruce-review-p{
    font-family: 'Open Sans', sans-serif;
    font-weight:400;
    color:hsla(0, 0%, 100%, 0.671);
}
</style>