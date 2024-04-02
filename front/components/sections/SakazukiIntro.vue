<template>
    <div class="melit-body">
        <h1 class="melit-title">導入メリット</h1>
        
        <!-- melit 1 -->
        <div class="melit-content">
            <div class="melit-block melit-right">
                <img class="melit-image" src="https://cdn.discordapp.com/attachments/1219948957048770610/1220979552155729941/2024-03-23_15.16.34.png?ex=6610e8d1&is=65fe73d1&hm=ec7c134ea967bdb9560daf81ac2c7582301d5f3f7a8999115c7ae41c7cf00c9d">
            </div>
            <div class="melit-block melit-left">
                <div class="block-title">
                    <span>1.</span>
                    <div>
                        <h2 class="title-row1">メンバーのキャリアを<br>証明書として可視化できる</h2>
                    </div>
                </div>
                <div class="block-text">
                    <p>
                        メンバーの成長を「キャリア証明書」で管理することで、<br>デジタル上で検証可能な個人情報として扱えます。
                    </p>
                </div>
            </div>
        </div>

        <!-- melit 2 -->
        <div class="melit-content">
            <div class="melit-block melit-left">
                <img class="melit-image" src="https://cdn.discordapp.com/attachments/1219948957048770610/1220989420988137504/2024-03-23_15.55.40.png?ex=6610f202&is=65fe7d02&hm=1ab9943d3d2f296afe735de2069566f7474b82f6b53340b7643874d616fdeaaf">
            </div>
            <div class="melit-block melit-right">
                <div class="block-title">
                    <span>2.</span>
                    <div>
                        <h2 class="title-row1">証明書で、企業からの<br>オファーを受け取れる</h2>
                    </div>
                </div>
                <div class="block-text">
                    <p>
                        キャリア証明書をスカウトプラットフォームに連携すると、<br>さまざまな企業から優良なオファーが届きます。
                    </p>
                </div>
            </div>
        </div>

        <!-- melit 3 -->
        <div class="melit-content">
            <div class="melit-block melit-right">
                <img class="melit-image" src="https://cdn.discordapp.com/attachments/1219948957048770610/1220980065953906688/sakazuki_logo_black_rgb.png?ex=661a23cc&is=6607aecc&hm=86e6a657fb10b9446ae0912e813a8545bc6d29f1805365b4c377e4c5dc2b1f7b">
            </div>
            <div class="melit-block melit-left">
                <div class="block-title">
                    <span>3.</span>
                    <div>
                        <h2 class="title-row1">キャリアパス推薦から<br>キャリア計画をスムーズに</h2>
                    </div>
                </div>
                <div class="block-text">
                    <p>
                        独自のダッシュボードで、「所属大学」「インターン先」<br>「就職先」までの一連のキャリアを可視化できます。
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.melit-body {
    padding: 25px;
    background-color: #7FC0EA;
    color: #1D4592;
    text-align: center;
}

.melit-title {
    font-size: 48px;
    margin-bottom: 40px;
}

.melit-content {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.melit-block {
    flex: 1;
    padding: 30px;
    text-align: center;
}

.melit-left {
    order: 1;
}

.melit-image {
    max-width: 100%;
    height: auto;
    border-radius: 20px;
    box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.1);
    background-color: #ffffff;
}

.block-title {
    margin-bottom: 20px;
}

.block-title span {
    text-align: left;
    display: block;
    font-size: 48px;
    color: #1D4592;
    font-weight: bold;
}

.title-row1 {
    font-size: 30px;
    margin-bottom: 10px;
    margin-top: 0px;
}

.block-text {
    font-size: 18px;
    line-height: 1.6;
}

.new-div {
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 100%;
    height: 50px;
    background-color: #7FC0EA;
}

@media screen and (max-width: 768px) {
    .melit-block {
        width: 100%;
        padding: 10px;
    }
    .block-title span {
        text-align: left;
        display: block;
        font-size: 30px;
        color: #1D4592;
        font-weight: bold;
        margin: 0px;
    }
    .title-row1 {
        font-size: 22px;
        margin-top: 0px;
        margin-bottom: 10px;
    }

    .new-div {
        height: 30px;
    }
}
</style>
