<template>
<footer class="footer">
    <div class="container">
        <div class="footer__content">
            <div class="footer__first-row">
                <div class="footer__logo"><img src="@/assets/image/logo.jpg" alt=""></div>
                <div class="footer__search">
                    <div class="footer__search-text">Подпишитесь на наши обновления</div>
                    <div class="search">
                        <div class="search__content">
                            <input type="text" placeholder="Пошта" class="search__input">
                            <a href="#" class="search__button">Подписаться</a>
                        </div>
                    </div>
                </div>
                <div class="footer__language-switcher"><p>RU|EN</p></div>
            </div>
            <div class="footer__second-row">
                <div class="footer__mobile-apps">
                    <div class="footer__apple">
                        <div class="footer__apple-image">
                            <img src="@/assets/image/Apple_icon.png" alt="">
                        </div>
                        <div class="footer__apple-text">
                            <div class="footer__apple-title">Coming soon</div>
                            <div class="footer__apple-subtitle">for iOS</div>
                        </div>
                    </div>
                    <div class="footer__android">
                        <div class="footer__andorid-image">
                            <img src="@/assets/image/Android_icon.png" alt="">
                        </div>
                        <div class="footer__android-text">
                            <div class="footer__android-title">Coming soon</div>
                            <div class="footer__android-subtitle">for Android</div>
                        </div>
                    </div>
                </div>

                <div class="footer__useful-links">
                    <div class="footer__useful-item">
                        <div class="footer__useful-item-header">Продукты</div>
                        <ul class="footer__link-list">
                            <li> <a href="" class="footer__link">Plonq 400</a> </li>
                            <li> <a href="" class="footer__link">Plonq 500</a> </li>
                            <li> <a href="" class="footer__link">Plonq X</a> </li>
                        </ul>
                    </div>
                    <div class="footer__useful-item">
                        <div class="footer__useful-item-header">Технологии</div>
                        <ul class="footer__link-list">
                            <li> <a href="" class="footer__link">О приложении</a> </li>
                            <li> <a href="" class="footer__link">Об электронных
                                сигаретах</a> </li>
                        </ul>
                    </div>
                    <div class="footer__useful-item">
                        <div class="footer__useful-item-header">Поддержка</div>
                        <ul class="footer__link-list">
                            <li> <a href="" class="footer__link">Связаться с нами</a> </li>
                            <li> <a href="" class="footer__link">Условия возврата</a> </li>
                            <li> <a href="" class="footer__link">Политика
                                конфиденциальности</a> </li>
                        </ul>
                    </div>
                    <div class="footer__useful-item">
                        <div class="footer__useful-item-header">Прочее</div>
                        <ul class="footer__link-list">
                            <li> <a href="" class="footer__link">Точки продаж</a> </li>
                            <li> <a href="" class="footer__link">О Компании</a> </li>
                            <li> <a href="" class="footer__link">Оптовым покупателям</a> </li>
                        </ul>
                    </div>
                </div>
                <div class="footer__info">
                    <div class="footer__instagram">
                        <img src="@/assets/image/Instagram_icon.svg" alt="">
                    </div>
                    <div class="footer__address">
                        © 2021 PLONQ LLC <br>
                        40900 Woodward Avenue Suite <br>
                        111 Bloomfield Hills <br>
                        MI 48304 USA
                    </div>
                </div>
            </div>
            <div class="footer__third-row">
                <div class="footer__restriction">
                    ПРОДАЖА НЕСОВЕРШЕННОЛЕТНИМ ЗАПРЕЩЕНА. <br>
Сайт используется исключительно в целях информирования действующих потребителей продукции PLONQ <br>
Защищено выпущенными и/или находящимися на одобрении международными патентами.. 
                </div>
            </div>
        </div>
    </div>
</footer>

</template>

<script>

</script>

<style lang="scss">
.container{
    max-width: 1408px;
    width: 100%;
    margin: 0 auto; 
}
.footer{
    &__content{
        display: flex;
        flex-direction: column;
        height: 610px;
    }
    &__first-row{
        display: flex;
        flex-direction: row;
        width: 100%;
        height: 85px;
        margin-bottom: 54px;
        justify-content: space-between;
    }
    &__second-row{
        display: flex;
        flex-direction: row;
        width: 100%;
        height: 174px;
        margin-bottom: 87px;
        justify-content: space-between;
    }
    &__logo{
        width: 100px;
    }
    &__search{
        width: 702px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    &__language-switcher{
        width: 310px;
        text-align: right;
    }
    &__mobile-apps{
        width: 152px;
    }
    &__useful-links{
        width: 810px;
    }
    &__info{
        width: 256px;
    }
    &__mobile-apps{
        width: 152px;
        display: flex;
        flex-direction: column;
    }
    &__apple,&__android{
        display: flex;
        flex-direction: row;
        align-items: center;
        margin-bottom: 29px;
        &-text{
            margin-left: 17px;
        }
        &-title{
            color: #000;
        }
        &-subtitle{
            color: #aaa;
        }
    }
    &__info{
        width: 256px;
        text-align: right;
        display: flex;
        flex-direction: column;
    }
    &__instagram{
        margin-bottom: 48px;
    }
    &__address{
        color: #aaa;
        line-height: 21px;
    }
    &__useful-links{
        width: 810px;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    &__useful-item{
        display: flex;
        flex-direction: column;
        width: 153px;
        margin-left: 89px;
        &:first-child{
            margin-left: 0;
        }
        &-header{
            color: #000;
            margin-bottom: 23px;
        }

    }
    &__link-list{
        list-style: none;
        padding: 0;
        margin: 0;
        & li{
            margin-bottom: 17px;
        }
    }
    &__link{
        color: #aaa;
        line-height: 21px;
    }
    &__restriction{
        text-align: center;
        line-height: 21px;
        color: #aaa;
    }
}
.search{
    &__input{
        background: #f9f9f9;
        width: 424px;
        height: 40px;
        border-radius: 4px;
    }
    &__content{
        display: flex;
        flex-direction: row;
        align-items: center;
    }
    &__button{
        background: #000;
        border-radius: 4px;
        color: #fff;
        width: 152px;
        height: 20px;
        text-align: center;
        padding: 10px 0px;
        margin-left: 24px;
        text-decoration: none;
    }
   
}
</style>