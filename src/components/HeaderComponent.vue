<template>
<div class="root">
<header class="header">
    <div class="header__conatainer">
        <div class="header__menu">
            <img src="@/assets/image/logo.jpg" alt="" class="header__logo">
            <nav class="menu">
                <ul class="menu__list">
                    <li class="menu__item"><a class="menu__link" href="">Продукты</a></li>
                    <li class="menu__item"><a class="menu__link" href="">Приложение</a></li>
                    <li class="menu__item"><a class="menu__link" href="">Дистрибуция</a></li>
                    <li class="menu__item"><a class="menu__link" href="">Где купить</a></li>
                </ul>
            </nav>
        </div>
    </div>
</header>
</div>
</template>

<script>

</script>

<style lang="scss">
.header{
    background-color: #fff;
    &__container{
        width: 100%;
        margin: 0 auto;
        height: 65px;
        width: 937px;
        
    }
    &__menu{
        width: 80%;
        display: flex;
        justify-content: space-between;
    }
    &__logo{
        width: 88px;
        height: 19px;
        margin: auto;
    }

}
.menu{
    font-family: 'Gotham Pro';
    width: 687px;
    height: 64px;
    margin-top: 15px;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    gap: 124px;
    &__list{
        display: flex;
        justify-content: space-between;
        list-style: none;
    }
    &__link{
        text-decoration: none;
        color: #000;
        font-family: 'Gotham Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 13px;
        line-height: 12px;
        display: flex;
        align-items: center;
    }
}
@media (max-width: 960px) {
    
  }
</style>