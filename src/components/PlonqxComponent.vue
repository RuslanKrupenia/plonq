<template>
<div class="root">
    <section class="plonqX">
        <div class="plonqX__container">
            <div class="plonqX__content">
                <div class="plonqX__text">
                    <img src="@/assets/image/PlonqX-img.svg" alt="" class="plonqX__logo">
                    <h2 class="plonqX__title">Электронная сигарета, которая умеет удивлять.</h2>
                    <div class="plonqX__info">
                        <button class="plonqX__more-btn">Подробнее <span class="more-span">></span></button>
                        <p class="plonqX__soon">Скоро в продаже</p>
                    </div>
                </div>
                <div class="plonqX__img">
                    <img src="@/assets/image/Plonq-x.png" alt="" class="plonqX__img">
                </div>
            </div>
        </div>
    </section>
</div>

</template>

<script>

</script>

<style lang="scss">
.plonqX{
    background-color: #fff;
    &__container{
        width: 937px;
        min-height: 80vh;
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: auto;
    }
    &__content{
        margin: 200px auto;
        width: 100%;
        height: 750px;
        display: flex;
        justify-content: space-between;
    }
    &__text{
        align-items: center;
    }
    &__logo{
        width: 280px;
        height: 60px;
    }
    &__title{
        width: 402px;
        height: 88px;
        font-family: 'Gotham Pro';
        font-size: 32px;
        line-height: 44px;
        font-weight: 300;
        color: #000000;
        align-items: center;
    }
    &__info{
        display: flex;
        justify-content: space-between;
    }
    &__more-btn{
        border: none;
        background: none;
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
        color: #000000;
        cursor: pointer;
    }
    &__soon{
        color: #C8BB93;
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
    }
    &__img{
        width: 480px;
        height: 750px;
    }


}
</style>