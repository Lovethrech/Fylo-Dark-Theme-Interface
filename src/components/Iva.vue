<template>
    <div class="iva-main-container">
        <div class="iva-review">
            <p class="iva-review-p">Fylo has improved our team productivity by an order of magnitude.
                Since making the switch our team has become a well-oiled collaboration machine.
            </p>
        </div>
        <div class="iva-profile">
            <div class="iva-image-container">
                <img src="../assets/images/profile-3.jpg" alt="" class="iva-image">
            </div>

            <div class="iva-info">
                <p class="iva-info-h5" style="font-family: 'Raleway', sans-serif; font-weight:700;">Iva Boyd<br><small class="iva-info-h6" style="font-family: 'Open Sans', sans-serif;">Founder & CEO, Huddle</small></p>
            </div>
        </div>
    </div>
</template>
<style scoped>
.iva-main-container {
    padding: 2vh 2vw;
    margin-bottom: 2vh;
    background-color: hsl(217, 28%, 15%);
}

.iva-profile {
    display: flex;
    gap: 1vw;
}
.iva-image-container{
    display:flex;
}
.iva-image {
    width: 30px;
    border-radius: 100px;
    margin: auto 0;
}

.iva-info-h6 {
    font-weight:400;
    color:hsla(0, 0%, 100%, 0.671);
}
.iva-review-p{
    font-family: 'Open Sans', sans-serif;
    font-weight:400;
    color:hsla(0, 0%, 100%, 0.671);
}
</style>