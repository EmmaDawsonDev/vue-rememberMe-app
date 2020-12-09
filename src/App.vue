<template>
  <the-header title="RememberMe"></the-header>
  <the-resources></the-resources>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';
export default {
  components: {
    TheHeader,
    TheResources
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;900&display=swap');

* {
  box-sizing: border-box;
}
html {
  font-family: 'Noto Sans JP', sans-serif;
}

body {
  margin: 0;
}
</style>
