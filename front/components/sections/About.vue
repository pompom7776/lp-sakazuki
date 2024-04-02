<template>
    <div class="about">
        <div class="about-content">
            <div class="about-logo">
                <img src="https://cdn.discordapp.com/attachments/1219948957048770610/1220980066511749160/sakazuki_logo_box_rgb.png?ex=6610e94c&is=65fe744c&hm=b0ddea06be9f2e8ec0fc725daed366242553b573a8181817d9f561e7d94a0a5a" alt="Sakazuki Logo">
                <p>とは？</p>
            </div>
            <div class="about-description">
                <p class="about-text">メンバー1人1人に対して<br>証明書を発行</p>
                <div class="about-right-bottom">
                    <p>メンバーの実績、活動歴、人柄を<br>まとめた独自の証明書を発行できます。</p>
                </div>
                <div class="about-right-bottom">
                    <p>企業へ証明書をアピールすることで、<br>メンバーでオファーを獲得できます。</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.about {
    margin-top: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.about-content {
    margin-right: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 100%;
    margin-bottom: 50px;
}

.about-logo {
    width: 40%;
    margin-right: 30px;
    text-align: center;
}

.about-logo img {
    max-width:70%;
    height: auto;
}

.about-logo p {
    font-size: 28px;
    margin-top: 10px;
    font-weight: bold;
    color: rgb(39, 68, 141);
}

.about-description {
    max-width: 600px;
    text-align: center;
}

.about-text {
    font-size: 35px;
    font-weight: bold;
    color: rgb(39, 68, 141);
    margin-bottom: 20px;
}

.about-right-bottom {
    font-size: 22px;
    line-height: 1.5;
    margin-bottom: 20px;
}

@media screen and (max-width: 768px) {
    .about-content {
        flex-direction: column;
        margin-bottom: 50px;
        margin-right: 0px
    }
  
    .about-logo {
        width: 600px;
        text-align: center;
        margin-top: 10px;
        margin-bottom: 50px;
        margin: 0px;
    }
    .about-logo img {
        max-width: 400px;
        height: auto;
    }
  
    .about-description {
        text-align: center;
    }
}
</style>
