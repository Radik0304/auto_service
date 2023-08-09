<template>
    <div class="main__container">
        <HeaderComponent/>
        <div class="main__header">
            <h1>Car music</h1>
            <img src="../assets/main-header-border.png" alt="header-border">
            <span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vitae orci urna amet penatibus.
            </span>
            <button>
                Наши услуги
            </button>
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
h1, span {
    font-family: ReformaGroteskMediumC;
    color: #fff;
}
h1{
    color: #DB3138;
    font-size: 150px;
    font-weight: 700;
    margin: 0;
    line-height: 187px;
}
img{
    width: 146px;
    height: 14px;
}
span{
    font-size:40px;
    font-weight: 500;
    line-height: 48px;
    width: 437px;
    margin: 41px auto 40px auto
}
button {
    width:144px;
    height: 61px;
}
.main__container{
    background-image: url("../assets/green-car.png");
    height: 100%;
    background-size: contain;
    background-repeat: no-repeat;
}
.main__header{
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>