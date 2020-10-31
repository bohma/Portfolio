<template>
  <div id="app">
    <MainWrapper />
  </div>
</template>

<script>
import MainWrapper from "./components/MainWrapper.vue";

export default {
  name: "App",
  components: {
    MainWrapper,
  },
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: "Roboto", sans-serif;
}
.title {
  font-weight: 500;
  font-size: 32px;

  &__note {
    margin-left: 30px;
    transition: 1s;
    opacity: 0;
    font-size: 20px;
    color: #9c9c9c;
  }
}
.description {
  color: #727272;
  &_black {
    color: #000000;
  }
}
.btn {
  text-decoration: none;
  padding: 25px 40px;
  background: #34547a;
  color: #ffffff;
  text-transform: uppercase;
  transition: 0.3s;

  &:hover {
    background: #1b416e;
  }
}
img {
  max-width: 100%;
}
.sprite {
  display: none;
}
.nav__burger {
  display: none;
}
@media screen and (max-width: 767px) {
  .title {
    font-size: 28px;
  }
}
</style>
