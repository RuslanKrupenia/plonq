<template>
<div class="root">
<section class="map">
    <div class="map__container">
        <div class="map__content">
        <img src="@/assets/image/map.png" alt="" class="map__image">
        <div class="map__text">
            <h2 class="map__title">Найдите Plonq 
                среди <span class="map__quantity">{{ 4244 }} </span> магазинов</h2>
            </div> 
                    <button class="map__button">Найти магазин</button>
        </div>
    </div>
</section>
</div>

</template>

<script>

</script>

<style lang="scss">
.map{
    background-color: #fff;
    &__container{
        width: 1409px;
        min-height: 100vh;
        height: 100%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        text-align: center;
    }
    &__content{
        width: 100%;
        height: 690px;
        background-color: #F9F9F9;
        justify-content: space-between;
        display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 32px;
            justify-content: space-evenly;
    }
    &__image{
        width: 100%;
        height: 455px;
    }
    &__title{
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 22px;
        line-height: 32px;
        margin: auto;
        color: #000000;
        width: 250px;
        height: 65px;
    }
    &__quantity{
        text-align: center;
        font-family: 'Gotham Pro Bold';
        font-size: 22px;
        line-height: 32px;
        color: #000000; 
    }
    &__button{
        font-family: 'Gotham Pro Bold';
        font-size: 13px;
        line-height: 24px;
        color: #000000;
        width: 208px;
        height: 48px;
        border: 1px solid #000000;
        border-radius: 100px;
        cursor: pointer;
        text-align: center;
    }
}
</style>