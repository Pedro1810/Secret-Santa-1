<template>
    <div>
        <div class="body">
            <div class="wrapper">
                <div class="steps">
                    <div class="step1">
                        <img src="../../assets/about/1step.svg" class="icon" alt="">
                        <div class="text">
                            <p class="title">1. Подаешь заявку</p>
                            <p class="about">В ней нужно немного рассказать о своих увлечениях и помочь Санте намекнуть,
                                какому подарку ты был бы рад, или что точно не хочешь получить.</p>
                        </div>
                    </div>

                    <div class="greenLine" />

                    <div class="step2">
                        <img src="../../assets/about/2step.svg" class="icon" alt="">
                        <div class="text">
                            <p class="title">2. Получаешь уведомление</p>
                            <p class="about">Оно подтвердит твое участие, а также покажет, для кого ты стал Тайным
                                сантой. В твоем профиле будет информация о коллеге его увлечениях и желаниях.</p>
                        </div>
                    </div>

                    <div class="greenLine" />

                    <div class="step3">
                        <img src="../../assets/about/3step.svg" class="icon" alt="">
                        <div class="text">
                            <p class="title">3. Готовишь подарок</p>
                            <p class="about">Приготовь подарок, придумай для него название  и скачай ваучер на доставку - можешь найти его у себя в личном кабинете.
                                Отправь доставку курьерской службой  и получи свою скидку в декабрьском Боброшопе!</p>
                        </div>
                    </div>

                    <div class="greenLine" />

                    <div class="step4">
                        <img src="../../assets/about/4step.svg" class="icon" alt="">
                        <div class="text">
                            <p class="title">4. Ждешь радостные уведомления</p>
                            <p class="about">Их будет два: о том, что твой подарок получили и о том, что принесли подарок для тебя. Когда заберешь подарок, в личном кабинете можно будет оставить послание для Тайного Санты и прислать фотку:)</p>
                        </div>
                    </div>
                <div class="discount">
                    <img class="img_" src="../../assets/BoBro_А4_new-06.png" alt="">
                    <p class="discountText">За участие в Тайном Санте ты получишь скидку в Боброшопе.
                        Как только ты отправишь подарок, станет доступной беспроигрышная лотерея: участвуй и получай
                        свою скидку на любой лот в декабрьской Бобромании и радуй себя новогодними
                        покупками за бобры!
                    </p>
                </div>
                </div>
            </div>
        </div>
        <div class="redline"></div>
    </div>
</template>

<script>

</script>

<style scoped>
    .body {
        background-color: white;
        justify-content: space-between;
        padding-top: 90px;
        width: 100%;
        color: #494949;
    }
    .redline {
        height: 40px;
        background-color: #FF645A;
        box-shadow: 0px 4px 7px rgba(0, 0, 0, 0.1);
    }
    .greenLine {
        height: 2px;
        width: 85px;
        background-color: #00A460;
        box-shadow: 0px 4px 7px rgba(0, 0, 0, 0.1);
        /* position: absolute;
        right: -60px;
        top: 40px; */
        margin-top: 50px;
    }
    .steps {
        display: flex;
        justify-content: space-between;
        position: relative;
        padding-bottom: 250px;
    }
    p {
        font-size: 15px;
        text-align: left;
    }
    .img_{
        width: 200px;
        height:200px;
    }
    .discount {
        position: absolute;
        right: calc(50% - (600px/2) - 10px);
        /* margin-top: 40px; */
        bottom: 0;
        padding: 5px 20px;
        width: 600px;
        background: #FF645A;
        border-radius: 20px 20px 0 0;
        display: flex;
        justify-content: space-between;
        /* box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.1); */
    }
    .discountText {
        font-size: 18px;
        font-family: CrocWebBold;
        color: white;
    }
    .ps {
        font-size: 11px;
        color: #6B6B6B;
    }
    .title {
        color: #00A460;
    }
    .text {
        padding: 10px;
        width: 260px;
        border-radius: 28px;
        box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.1);
        min-height: 200px;
    }
    .step1,
    .step2,
    .step3,
    .step4{
        position: relative;
        text-align: center;
    }
    .wrapper {
        margin-right: auto;
        margin-left: auto;
        max-width: 85%;
        padding-right: 10px;
        padding-left: 10px;
    }
    @media screen and (max-width: 1665px) {
        img {
            height: 70px;
        }
        .img_{
            width: 150px;
            height: 150px;
        }
        .text {
            padding: 10px;
            width: 220px;
            border-radius: 28px;
            box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.1);
            min-height: 250px;
        }
        .discountText {
            font-size: 16px;
        }
    }

    @media screen and (max-width: 1430px) {

        .body {
            padding-top: 70px;
        }
        img {
            height: 70px;
        }
        .img_ {
            height: 120px;
            width: 120px;
        }
        .text {
            padding: 10px;
            width: 180px;
            border-radius: 28px;
            box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.1);
            min-height: 200px;
        }
        p {
            font-size: 12px;
            text-align: left;
        }
        .ps {
            font-size: 10px;
            color: #6B6B6B;
        }
        .discountText {
            font-size: 14px;
        }
        /* .discount {
            padding: 10px;
            width: 400px;
        } */
    }
</style>