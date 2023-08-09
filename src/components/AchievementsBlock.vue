<template>
    <div class="achievements__container">
        <div class="achievements__info">
            <h3>Наши достижения от кубка россии до чемпионатов мира</h3>
            <img src="../assets/main-header-border.png" alt="header-border">
            <span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Habitant tincidunt aliquam tincidunt pretium
                sodales.
                Tristique odio pellentesque et tincidunt posuere arcu purus lobortis risus. Urna, ut amet odio orci magnis
                praesent ultrices. Praesent malesuada lacus tellus tristique sit at. Sed viverra nulla nam arcu, non iaculis
                pretium, volutpat.
            </span>
        </div>
        <div class="achievements__descriptions">
            <div class="achievements__descriptions_first-block">
                 <!-- Переписать потом с v-for -->
                <ul>
                    <li class="achievements__descriptions-info">
                        <img src="../assets/1.png" alt="number-one">
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li>
                        <img src="../assets/6.png" alt="number-six">
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li>
                        <img src="../assets/2.png" alt="number-two">
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li>
                        <img src="../assets/1.png" alt="number-one">
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                </ul>
            </div>
            <div class="achievements__descriptions_second-block"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AchievementsBlock'
}
</script>

<style scoped>
/** обнуляем стандарные стили */
h3{
    margin: 0;
}
.achievements__container{
    display: flex;
    align-items: center;
    justify-content: center;
}
.achievements__descriptions{
    width: 30%;
}
.achievements__info{
    display: flex;
    flex-direction: column;
    width: 30%;
}
.achievements__descriptions-info{
    display: flex;
    flex-direction: column;
}
.achievements__info span {
    font-family: ReformaGroteskMediumC;
    font-size: 24px;
    font-weight: 500;
    color: #fff;
}
img{
    width: 146px;
    height: 14px;
}
h3 {
    font-family: ReformaGroteskDemiC;
    font-size: 52px;
    font-weight: 600;
    color: #fff;
    text-transform: uppercase;
}
</style>