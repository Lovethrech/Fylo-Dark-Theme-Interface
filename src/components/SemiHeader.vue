<template>
    <div class="semi-header-main-container">
        <div class="semi-header-image-container">
            <img src="../assets/images/illustration-intro.png" alt="" class="semi-header-image">
        </div>
        <div class="semi-header-text-content-container">
            <h1 style="font-family: 'Raleway', sans-serif;">All your files in one secure location,<br> accessible anywhere.</h1>
            <p style="color:hsla(0, 0%, 100%, 0.671);font-family: 'Open Sans', sans-serif;">Fylo stores all your most important files in one secure location.<br>
                Access them wherever you need, share and collaborate with<br> friends
                family, and co-workers.
            </p>
            <a href="login.html" target="_top" rel="noreferrer" class="semi-header-text-content-container-link">
                <button class="semi-header-text-content-container-btn">Get Started</button>
            </a>
        </div>
    </div>
</template>
<style scoped>
.semi-header-main-container{
    text-align:center;
    transition:all 5s;
}
.semi-header-image{
    width: 70vw;
}

.semi-header-text-content-container{
    text-align: center;
    padding: 0 5vw;
    color:hsl(0, 100%, 100%);
    transition:all;
}
.semi-header-text-content-container-btn{
    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    margin:20px 0 50px;
    padding:10px 60px;
    border-radius:20px;
    border: 2px solid hsl(198, 60%, 50%);
    color:hsl(0, 0%, 100%);
    background-color:hsl(198, 60%, 50%);
}
.semi-header-text-content-container-btn:hover{
    cursor: pointer;
    background-color:hsl(198, 49%, 62%);
    border: 2px solid hsl(218, 28%, 13%);
}
</style>