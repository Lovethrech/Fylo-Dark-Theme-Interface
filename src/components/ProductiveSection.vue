<template>
    <div class="productive-section-main-container">
        <div class="productive-section-image-container">
            <img src="../assets/images/illustration-stay-productive.png" alt="" class="productive-section-image">
        </div>
        <div class="productive-section-text-container">
            <h2 style="font-family: 'Raleway', sans-serif;">Stay productive, wherever you are</h2>
            <p style="color:hsla(0, 0%, 100%, 0.671);font-family: 'Open Sans', sans-serif;">Never let location be an issue when accessing your files.
                Fylo has you covered for all of your file storage needs.<br><br>
                Securely share files and folders with friends, family and colleagues
                for live collaboration. No email attachments required.
            </p>  
            <a href="" class="productive-section-link">
                <p class="productive-section-link-p">See how Fylo works</p>
                <img src="../assets/images/icon-arrow.svg" class="productive-section-link-img">
            </a>
        </div>
    </div>
</template>

<style scoped>
.productive-section-main-container{
    display:flex;
    place-items:center;
    justify-content:center;
    gap:20px;
    padding: 0 3vw;
}
.productive-section-image{
    width:50vw;
}
.productive-section-text-container{
    margin:auto 0;
    color:hsl(0, 0%, 100%);
}
.productive-section-link{
    display:flex;
    place-items: center;
}

.productive-section-link-p{
    color: hsl(176, 68%, 64%);
    text-decoration:underline;
    font-weight:100;
}
.productive-section-link-img{
    height:20px;
}
.productive-section-link:hover{
    color:hsla(0, 0%, 100%, 0.671);
    transform: scaleX(0.98);
    transition: all .42s;
}
@media screen and (max-width:850px){
    
    .productive-section-main-container{
        flex-direction: column;
    }
    .productive-section-image{
        width:100%;
    }
}
</style>