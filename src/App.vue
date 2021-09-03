<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from "@/components/Title.vue";
import Hero from "@/components/Hero.vue";
export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  text-align: center;
}

img {
  width: 100px;
  margin: 40px 0;
}
</style>
