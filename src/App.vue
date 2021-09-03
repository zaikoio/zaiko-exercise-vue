<template>
  <CouponComponent />
  <PremiumComponent />
</template>

<script>
import CouponComponent from "./components/CouponComponent";
import PremiumComponent from "./components/PremiumComponent";

export default {
  name: 'App',
  components: {
    CouponComponent,
    PremiumComponent,
  }
}
</script>

<style>
@import '~bootstrap/dist/css/bootstrap.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 960px;
  margin: auto;
}
</style>
