<script setup>
import ChallengeInfo from "../components/ChallengeInfo.vue";
</script>

<template>
    <footer class="footer-main-container">
        <div class="footer-logo-container">
            <img src="../assets/images/logo.svg" alt="" class="footer-logo">
        </div>
        <div class="footer-section">
            <div class="footer-first">
                <img src="../assets/images/icon-location.svg" alt="" class="footer-first-img">
                <p class="footer-main-container-p">Lorem ipsum dolor sit amet, consectetur<br>
                    adipiscing elit, sed do eiusmod tempor incididunt
                    ut labore et dolore magna aliqua
                </p>
            </div>
            <div class="footer-second">
                <div class="footer-second-contact">
                    <img src="../assets/images/icon-phone.svg" alt="">
                    <a href="tel:+" class="footer-main-container-a"> +1-543-123-4567</a>
                </div><br>
                <div class="footer-second-contact">
                    <img src="../assets/images/icon-email.svg" alt="">
                    <a href="mailto:" class="footer-main-container-a">example@fylo.com</a>
                </div>
            </div>
            <div class="footer-third">
                <ul class="footer-list">
                    <li><a href="" class="footer-main-container-a">About Us</a></li><br>
                    <li><a href="" class="footer-main-container-a">Jobs</a></li><br>
                    <li><a href="" class="footer-main-container-a">Press</a></li><br>
                    <li><a href="" class="footer-main-container-a">Blog</a></li><br>
                </ul>
            </div>
            <div class="footer-fourth">
                <ul class="footer-list">
                    <li><a href="" class="footer-main-container-a">Contact Us</a></li><br>
                    <li><a href="" class="footer-main-container-a">Terms</a></li><br>
                    <li><a href="" class="footer-main-container-a">Privacy</a></li><br>
                </ul>
            </div>
            <div class="footer-fifth">
                <div class="footer-main-container-a-icon"><i class='bx bxl-facebook' ></i></div>
                <div class="footer-main-container-a-icon"><i class='bx bxl-twitter'></i></div>
                <div class="footer-main-container-a-icon"><i class='bx bxl-instagram' ></i></div>
            </div>
        </div><br>
        <ChallengeInfo></ChallengeInfo>
    </footer>
</template>
<style scoped>
.footer-logo-container{
    margin: auto 0 ;
}
.footer-logo{
    height:25px;
}
.footer-main-container{
    font-family: 'Open Sans', sans-serif;
    background-color: hsl(216, 53%, 9%);
    padding: 70px 100px 20px;
}
.footer-main-container-a{
    font-family: 'Raleway', sans-serif;
    text-decoration:none;
    color: hsla(0, 0%, 100%, 0.671);
}
.footer-main-container-p{
    color: hsla(0, 0%, 100%, 0.671);
    margin:0;
}
.footer-section{
    display:flex;
    justify-content: space-between;
    gap: 40px;
    margin-top:10px;
}
.footer-first{
    width:30vw;
    display: flex;
    gap:10px;
}
.footer-second-contact{
    display: flex;
    gap:10px;
}
.footer-fifth{
    display: flex;
    gap:10px;
}
.footer-first-img{
    height:20px;
}
.footer-list{
    margin:0;
    list-style: none;
}
.footer-main-container-a:hover{
    color: hsl(0, 0%, 100%);
}
.footer-main-container-a-icon{
    color:hsl(0, 0%, 100%);
    border:2px solid hsla(0, 0%, 100%, 0.671);
    border-radius: 70px;
    padding: 2px 12px;
    display:flex;
    place-items: center;
    justify-content: center;
    height: 40px;
}
.footer-main-container-a-icon:hover{
    color: hsl(0, 0%, 100%);
    border: 2px solid hsla(0, 0%, 100%, 0.671);
    transform:scale(1.1);
}
@media screen and (max-width:850px){
    .footer-section{
        flex-direction: column;
        margin:3vh 0;
    }
    .footer-main-container{
        padding:5vh 5vw;
    }
    .footer-list{
        padding:0 5vw;
    }
    .footer-first{
        width:100%;
    }
    .footer-second{
        margin:-3vh 0 0;
    }
    .footer-fifth{
        display:flex;
        justify-content: center;
        gap:4vw;
    }
} 
    

</style>