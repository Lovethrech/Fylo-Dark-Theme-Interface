<template>
    <div class="sectioned-area-main-container">
        <div class="sectioned-area-main-container-first-section">
            <div class="sectioned-workflow">
                <div class="access-image-container">
                    <img src="../assets/images/icon-access-anywhere.svg" alt="" class="sectioned-images">
                </div>
                <div class="access-text-container">
                    <h3 style="font-family: 'Raleway', sans-serif;">Access your files, anywhere</h3>
                    <p class="sectioned-area-p" style="font-family: 'Open Sans', sans-serif;">The ability to use a smartphone, tablet, or computer to access
                        your account means your files follow you everywhere. 
                    </p> 
                </div>
            </div>
            <br>
            <div class="sectioned-workflow">
                <div class="security-image-container">
                    <img src="../assets/images/icon-security.svg" alt="" class="sectioned-images">
                </div>
                <div class="security-text-container">
                    <h3 style="font-family: 'Raleway', sans-serif;">Security you can trust</h3>
                    <p class="sectioned-area-p" style="font-family: 'Open Sans', sans-serif;">2-factor authentication and user-controlled encryption are just
                    a couple of the security features we allow to help secure your files.
                    </p>
                </div>
            </div>
        </div>

        <div class="sectioned-area-main-container-second-section">
            <div class="sectioned-workflow">
                <div class="collaborate-image-container">
                    <img src="../assets/images/icon-collaboration.svg" alt="" class="sectioned-images">
                </div>
                <div class="collaboration-text-container">
                    <h3 style="font-family: 'Raleway', sans-serif;">Real-time collaboration</h3>
                    <p class="sectioned-area-p" style="font-family: 'Open Sans', sans-serif;">Securely share files and folders with friends, family and
                    colleagues for live collaboration. No email attachments required.
                    </p>
                </div>
            </div>
            <br>
            <div class="sectioned-workflow">
                <div class="store-image-container">
                    <img src="../assets/images/icon-any-file.svg" alt="" class="sectioned-images">
                </div>
                <div class="store-text-container">
                    <h3 style="font-family: 'Raleway', sans-serif;">Store any type of file</h3>
                    <p class="sectioned-area-p" style="font-family: 'Open Sans', sans-serif;">Whether you're sharing holidays photos or work documents, Fylo
                    has you covered allowing for all file types to be securely stored and shared.
                    </p>
                </div>
            </div>
        </div>
    </div>

</template>
<style scoped>
.sectioned-area-p{
    color:hsla(0, 0%, 100%, 0.671);
}
.sectioned-area-main-container{
    padding:3vh 0 6vh;
}
.sectioned-area-main-container-first-section{
    display:flex;
    justify-content: center;
    place-items:center;
    gap:4vw;
    padding: 40px 100px;
    text-align: center;
    transition: all 2s;
}
.sectioned-area-main-container-second-section{
    display:flex;
    justify-content: center;
    place-items:center;
    gap:4vw;
    padding: 40px 100px;
    text-align: center;
    transition: all 2s;
}
.sectioned-images{
    height:10vh;
    margin:0
}
.sectioned-workflow{
    margin:0;
    color:hsl(0, 0%, 100%);
}

@media screen and (max-width:850px) {
    .sectioned-area-main-container-first-section{
        flex-direction: column;
        padding:0 5vw;
        margin:0 0 4vh;
    }
    .sectioned-area-main-container-second-section{
        flex-direction: column;
        padding:0 5vw;
    }
}

</style>