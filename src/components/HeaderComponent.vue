<template>
  <div class="header">
    <div class="header__text">
      <a href="#">Главная</a>
      <a href="#">Оклейка автомобилей</a>
      <a href="#">Детейлинг автомобилей</a>
    </div>
    <button class="header__burger"></button>
  </div>
</template>

<script>
export default {
  name: 'HeaderComponent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  display: flex;
  justify-content: space-between;
  font-family: ReformaGroteskMediumC;
  font-size: 24px;
  line-height: 29px;

  margin: 0 auto;
  width: 70%;
}

.header__text{
  width: 521px;
  gap: 40px;
  display: flex;
}

a{
  /* color: #fff; */
  color: black;
  text-decoration: none;
}
.header__burger{
  border:none;
  width: 50px;
  height: 25px;
  background-color: rgba(0,0,0,0);
  background-image: url("../assets/burger_icon.png");
}

.header__burger:hover{
  cursor: pointer;
}
</style>
