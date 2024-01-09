<template>
    <div class="main-header-main-container">
        <div class="main-header-logo-container">
            <img src="../assets/images/logo.svg" alt="" class="main-header-logo">
        </div>
        <div class="main-header-nav-container">
            <ul class="main-header-nav-list">
                <li class="main-header-nav"><a href="" class="main-header-nav-link">Features</a></li>
                <li class="main-header-nav"><a href="" class="main-header-nav-link">Team</a></li>
                <li class="main-header-nav"><a href="login.html" target="_top" rel="noreferrer" class="main-header-nav-link">Sign in</a></li>
            </ul>
        </div>
    </div>
</template>

<style scoped>
.main-header-main-container{
    padding:2vh 5vw;
    display:flex;
    justify-content: space-between;
    transition: all 2s;
}
.main-header-logo-container{
    margin: auto 0 ;
}
.main-header-logo{
    height:25px;
}
.main-header-nav-container{
    margin: auto 0 ;
}

.main-header-nav-list{
    display:flex;
    justify-content: space-between;
    gap:2vw;
    font-size:14px;
    font-family: 'Raleway', sans-serif; 
}
.main-header-nav-link{
    position:relative;
    color: hsla(0, 0%, 100%, 0.671);
    font-family: 'Raleway', sans-serif;
    text-decoration:none;
}

.main-header-nav-link::after{
    content:' ';
    position:absolute;
    left:2px;
    bottom:-6px;
    width:100%;
    height:1px;
    background: hsl(0, 0%, 100%);
    border-radius:3px;
    transform-origin: left;
    transform:scaleX(0);
    transition: transform .5s;
}
.main-header-nav-link:hover{
    color:hsl(0, 0%, 100%);
}
.main-header-nav-link:hover::after{
    cursor:pointer;
    color:hsla(0, 0%, 100%);
    transform: scaleX(0.9);
    transform-origin: left;
}

@media screen and (max-width:350px){
    .main-header-logo{
        height:20px;
    }
    .main-header-nav{
        font-size:2vh;
    }
}
</style>