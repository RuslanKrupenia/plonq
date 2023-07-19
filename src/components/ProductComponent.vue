<template>
<div class="root">
    <section class="product">
        <div class="product__container">
            <div class="product__content">
                    <div class="product__item">
                    <div class="product__img">
                        <img src="@/assets/image/plonq-1.png" alt="" class="prouct__img-1">
                    </div>
                    <div class="product__text">
                        <img src="@/assets/image/plonq-400.png" alt="" class="product__logo-400">
                        <h2 class="product__title">Одноразовое устройство Plonq на 400 затяжек</h2>
                        <h2 class="product__price">370 грн</h2>
                        <button class="product__buy-btn">Где купить</button>
                    </div>
                    </div>
                <div class="product__item">
                    <div class="product__img">
                        <img src="@/assets/image/plonq-2.png" alt="" class="prouct__img-2">
                    </div>
                    <div class="product__text">
                        <img src="@/assets/image/plonq-500.png" alt="" class="product__logo-500">
                        <h2 class="product__title">Одноразовое устройство Plonq на 500 затяжек</h2>
                        <h2 class="product__price">430 грн</h2>
                        <button class="product__buy-btn">Где купить</button>
                    </div>
                </div>
                <div class="product__item">
                    <div class="product__img">
                        <img src="@/assets/image/plonq-3.png" alt="" class="prouct__img-3">
                    </div>
                    <div class="product__text">
                        <img src="@/assets/image/plonq_X.png" alt="" class="product__logo-400">
                        <h2 class="product__title">Стартовый набор
                            Plonq X</h2>
                        <p class="product__coon">Скоро в продаже</p>
                    </div>
                </div>
                <div class="product__item">
                    <div class="product__img">
                        <img src="@/assets/image/plonq-4.png" alt="" class="prouct__img-4">
                    </div>
                    <div class="product__text">
                        <img src="@/assets/image/plonq_X.png" alt="" class="product__logo-400">
                        <h2 class="product__title">Два сменных картриджа
                            для устройства Plonq X</h2>
                        <p class="product__coon">Скоро в продаже</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>

</template>

<script>

</script>

<style lang="scss">
.product{
    background-color: #fff;
    &__container{
        min-height: 100vh;
        height: 100%;
        width: 1136px;
        margin: auto;
        display: flex;
        

    }
    &__content{
        width: 100%;
        height: 1135px;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        
    }
    &__item{
        width: 500px;
        height: 452px;
        display: flex;
    }
    &__item:first-of-type{
        margin-left: auto;
    }
    &__item:last-of-type{
        margin-left: auto;
    }
    &__img-1,&__img-2,&__img-4{
        width: 125px;
        height: 450px;
    }
    &__text{
        margin: auto 0;
    }
    &__title{
        font-family: 'Gotham Pro';
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
        color: #000000;
    }
    &__price{
        font-family: 'Gotham Pro Bold';
        font-weight: 400;
        font-size: 21px;
        line-height: 30px;
        color: #000000;
    }
    &__coon{
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 15px;
        line-height: 21px;
        color: #C8BB93;
    }
    &__buy-btn{
        border: 1px solid #000;
        background: none;
        font-family: 'Gotham Pro Bold';
        font-style: normal;
        font-weight: 400;
        font-size: 13px;
        line-height: 24px;
        display: flex;
        align-items: center;
        text-align: center;
        color: #000000;
        padding: 12px 67px;
        border-radius: 100px;
        cursor: pointer;
    }
}

</style>