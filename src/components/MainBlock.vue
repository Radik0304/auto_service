<template>
    <div class="main__container">
        <HeaderComponent />
        <div class="main__header">
            <h1>Car music</h1>
            <img src="../assets/main-header-border.png" alt="header-border">
        </div>
        <div class="main__content">
            <span>
                Сотрясаем улицы и дворы Москвы с 2007 года!
            </span>
            <button>
                <span>
                    Наши услуги
                </span>
            </button>
        </div>
        <div class="main__contacts">
            <div class="main__contacts_adress">
                <h6>Адрес</h6>
                <span>
                    <p>Москва, ул. Пушкина, дом Колотушкина</p>
                </span>
            </div>
            <div class="main__contacts_phone">
                <h6>Телефон</h6>
                <span>
                    <p>+7 (917) 111 15 45</p>
                    <p>+7 (846) 220 12 20</p>
                </span>    
            </div>
            <div class="main__contacts_working">
                <h6>Режим работы</h6>
                <span>
                    <p>пн-пт: 10.00 - 20.00</p>
                    <p>сбт-вск: 12.00 - 20.00</p>
                </span>
            </div>
        </div>
    </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue'
export default {
    name: 'MainBlock',
    components: {
        HeaderComponent
    }
}
</script>

<style  scoped>
h1,
span {
    font-family: ReformaGroteskMediumC;
    color: #fff;
}

h1 {
    color: #DB3138;
    font-size: 150px;
    font-weight: 700;
    margin: 0;
    line-height: 187px;
}

img {
    width: 146px;
    height: 14px;
}

span {
    font-size: 40px;
    font-weight: 500;
    line-height: 48px;
    max-width: 437px;
    margin: 41px auto 40px auto
}
p, h1, h6{
    margin: 0;
    padding:0;
}

button {
    width: 144px;
    height: 61px;
    background: linear-gradient(to right, #DB3138 70%, #141414CC 30%);
    border: none;
    padding: 0;
}   
button span {
    font-family: ReformaGroteskDemiC;
    font-size: 24px;
    font-weight: 600;
    color: #fff;
    line-height: 33px;
}

.main__container {
    background-image: url("../assets/green-car.png");
    height: 100%;
    background-size: contain;
    background-repeat: no-repeat;
}

.main__header {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 168px;
}

.main__content{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 103px;
}

.main__contacts{
    width: 100%;
    height: 213px;
    display: flex;
    justify-content: space-around;
    border-top: 1px solid #898989;
    border-bottom: 1px solid #898989;
}
.main__contacts_adress, .main__contacts_phone, .main__contacts_working{
    font-family: ReformaGroteskDemiC;
    width: 33%;
}
.main__contacts_adress{
    border-right: 1px solid #898989
}
.main__contacts_phone{
    border-right: 1px solid #898989;
}
.main__contacts div h6 {
    font-size: 18px;
    font-weight: 600;
    color: #fff;
    margin: 50px 0 20px 0;
}
.main__contacts div span {
    font-size: 24px;
    font-weight: 600;
    color: #DB3138;
    margin: 0;
}
.main__contacts div span p {
    line-height: 33px;
}

/** медиазапросы */

</style>