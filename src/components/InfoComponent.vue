<template>
<div class="root">
    <section class="info">
        <div class="info__container">
            <div class="info__content">
                <div class="info__cigarette">
                    <div class="info__cigarette-text">
                        <h2 class="info__title">Об электронных
                            сигаретах</h2>
                        <p class="info__word">Plonq — электронный испаритель, который преобразует жидкость в пар.</p>
                        <button class="info__more">Подробнее <span class="info__span">></span></button>
                    </div>
                        <img src="@/assets/image/sigarette.png" alt="" class="info__cigarette-image">
                </div>
                <div class="info__app">
                    <div class="info__app-text">
                        <h2 class="info__app-title">О приложении</h2>
                            <p class="info__app-word">Plonq AI создан на основе поведенческой терапии, которая доказала свою эффективность.</p>
                        <button class="info__more">Подробнее <span class="info__span">></span></button>
                    </div>
                        <img src="@/assets/image/phone.png" alt="" class="info__app-phone">
                </div>
            </div>
        </div>
    </section>
</div>

</template>

<script>

</script>

<style lang="scss">
.info{
    background: #fff;
    &__container{
        width: 1408px;
        height: 100%;
        min-height: 100vh;
        margin: 0 auto;
    }
    &__content{
        width: 100%;
        height: 465px;
        display: flex;
        justify-content: space-between;
    }
    &__cigarette{
        width: 688px;
        height: 465px;
        display: flex;
        background-color: #F9F9F9;
        align-items: center;
        justify-content: center;
    }
    &__cigarette-text{
        width: 330px;
        height: 200px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    &__title{
        font-family: 'Gotham Pro';
        width: 197px;
        height: 56px;
        font-weight: 400;
        font-size: 23px;
        line-height: 28px;
        color: #000000;
    }
    &__word{
        font-family: 'Gotham Pro';
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
        color: #000000;
        width: 328px;
        height: 42px;
    }
    &__more{
        text-align: left;
        background: none;
        border: none;
        width: 106px;
        height: 21px;
        cursor: pointer;
        display: flex;
        font-family: 'Gotham Pro';
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
        color: #000000;
        transition: all 1s;
    }
    &__span{
        margin-left: 15px;
        transition: all 1s;
    }
    &__more:hover &__span{
        margin-left: 30px;
    }
    &__cigarette-image{
        margin-left: 42px;
        margin-top: auto;
    }
    &__app{
        width: 688px;
        height: 465px;
        display: flex;
        justify-content: space-between;
        background-color: #f9f9f9;
    }
    &__app-text{
        width: 300px;
        height: 172px;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    &__app-title{
        font-family: 'Gotham Pro';
        width: 176px;
        height: 28px;
        font-weight: 400;
        font-size: 23px;
        line-height: 28px;
        color: #000000;
    }
    &__app-word{
        font-family: 'Gotham Pro';
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
        color: #000000;
        width: 296px;
        height: 63px;
    }

}
</style>