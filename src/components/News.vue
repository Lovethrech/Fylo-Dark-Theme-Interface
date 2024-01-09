<template>
    <div class="news-main-container">
        <div class="news-text-container">
            <h3 style="font-family: 'Raleway', sans-serif;font-weight:700;">Get early access today</h3>
            <p style="font-family: 'Open Sans', sans-serif;color:hsla(0, 0%, 100%, 0.671);">It only takes a minute to sign up and our free starter tier
            is extremely generous. If you have any questions, our support
                team would be happy to help you.
            </p>
        </div>
        <div class="news-mail-container">
            <input type="email" placeholder="email@example.com" class="news-mail-container-input">
            <a href="login.html" target="_top" rel="noreferrer" class="news-mail-container-link">
                <button class="news-mail-container-btn">Get Started For Free</button>
            </a>
        </div>
    </div>
</template>

<style scoped>

.news-main-container{
    background-color: hsl(217, 28%, 15%);
    color:hsl(0, 0%, 100%);
    padding:30px;
    text-align: center;
}
.news-mail-container{
    margin-top:20px;
    width:100%;
}
.news-mail-container-input{
    padding: 5px 20px;
    border-radius:20px;
    border:1px hsl(218, 28%, 13%) solid;
    width:70%;
}
.news-mail-container-btn{
    padding: 5px 20px;
    border-radius:20px;
    border:1px hsl(218, 28%, 13%) solid;
    background: linear-gradient(to right, hsl(176, 68%, 64%) 2%, hsl(198, 60%, 50%) 100% );
    font-family: 'Raleway', sans-serif;
    font-weight:400;
    color:hsl(0, 0%, 100%);
    font-size:14px;
}

.news-mail-container-btn:hover{
    cursor: pointer;
    transform: scaleX(0.9);
}
</style>