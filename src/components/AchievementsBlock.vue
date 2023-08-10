<template>
    <div class="achievements__container">
        <div class="achievements__info">
            <h2>Наши достижения от кубка россии до чемпионатов мира</h2>
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
                        <h3>#1</h3>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li class="achievements__descriptions-info">
                        <h3>#6</h3>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li class="achievements__descriptions-info">
                        <h3>#2</h3>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li class="achievements__descriptions-info">
                        <h3>#1</h3>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                </ul>
            </div>
            <div class="achievements__descriptions_second-block">
                <ul>
                    <li class="achievements__descriptions-info">
                        <h3>#4</h3>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li class="achievements__descriptions-info">
                        <h3>#3</h3>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li class="achievements__descriptions-info">
                        <h3>#1</h3>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                    <li class="achievements__descriptions-info">
                        <img src="../assets/cup.png" alt="">
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dui </span>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AchievementsBlock'
}
</script>

<style scoped>
.achievements__container {
    display: flex;
    justify-content: center;
    margin-top: 180px;
}

@media screen and (max-width:600px) {
    .achievements__container {
        flex-direction: column;
        align-items: center;
    }

    .achievements__info {
        margin-right: 0 !important;
        align-items: center !important;
        ;
    }

    .achievements__info h2,
    .achievements__info span {
        text-align: center !important;
    }

    .achievements__container {
        margin-top: 50px;
    }

    .achievements__info img{
    margin: 20px 0 30px 0!important;
}

.achievements__descriptions{
    margin-top: 50px;
}
}

.achievements__descriptions {
    display: flex;
    width: 40%;
}

.achievements__info {
    display: flex;
    align-items: start;
    flex-direction: column;
    width: 40%;
    margin-right: 24px;
}

.achievements__descriptions-info {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: #fff;
    margin: auto;
    font-size: 16px;
    font-weight: 600;
    font-family: ReformaGroteskDemiC;
    border: 1px solid #898989;
}

.achievements__descriptions-info span {
    margin-top: 22px;
}

.achievements__descriptions_second-block {
    margin-top: 40px;
}

.achievements__descriptions-info img {
    width: 37px;
    height: 45px;
}

.achievements__info span {
    font-family: ReformaGroteskMediumC;
    font-size: 24px;
    font-weight: 500;
    color: #fff;
    text-align: start;
}

ul {
    padding: 0;
    margin: 0;
}

li {
    height: 177px;
    max-width: 318px;
}

.achievements__info img {
    width: 146px;
    height: 14px;
    margin: 40px 0 60px 0;
}

h2 {
    font-size: 52px;
    font-weight: 600;
    color: #fff;
    text-transform: uppercase;
}

h2 {
    text-align: start;
}

h2,
h3 {
    font-family: ReformaGroteskDemiC;
    margin: 0;
}

h3 {
    font-size: 24px;
    font-weight: 600;
    color: #DB3138;
}</style>