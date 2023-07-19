<template>
<div class="root">
<section class="home">
    <div class="home__container">
        <div class="home__content">
            <img src="@/assets/image/header-logo.png" alt="" class="home__content-logo">
            <h2 class="home__content-title">Новый стандарт
                одноразовых e-сигарет.</h2>
            <div class="home__buttons">
                <button class="home__more-btn">Подробнее <span class="more-span">></span></button>
                <button class="home__buy-btn">Где купить</button>
            </div>
        </div>
    </div>
</section>
</div>
</template>

<script>

</script>

<style lang="scss">
.home{
    background-image: url(../assets/image/header-bg.png);
    background-position: top center;
    background-repeat: no-repeat;
    background-size: cover;
    &__container{
        width: 937px;
        min-height: 100vh;
        height: 100%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    &__content{
        width: 450px;
        height: 310px;
    }
    &__content-logo{
        width: 388px;
        height: 78px;
    }
    &__content-title{
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 32px;
        line-height: 44px;
        color: #FFFFFF;
    }
    &__buttons{
        width: 388px;
        height: 48px;
        display: flex;
        justify-content: space-between;
    }
    &__more-btn{
        width: 119px;
        height: 21px;
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
        border: none;
        background: none;
        color: #FFFFFF;
        justify-content: space-between;
        display: flex;
        margin-top: 10px;
        cursor: pointer;
    }
    &__buy-btn{
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 13px;
        line-height: 24px;
        text-align: center;
        width: 208px;
        height: 48px;
        color: #FFFFFF;
        background: none;
        border: 1px solid #FFFFFF;
        border-radius: 100px;
        cursor: pointer;
    }

}
.more-span{
    margin-left: 30px;
}

</style>