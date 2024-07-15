
<script setup>
// import NestedItem from './components/NestedItem.vue';
// import NestedMenu from './components/NestedMenu.vue';
import Calculator from './MiniTask/Calculator.vue';
import CRUD from './MiniTask/CRUD.vue';
import FlightBooker from './MiniTask/FlightBooker.vue';
import TempConvert from './MiniTask/TempConvert.vue';
import Timer from './MiniTask/Timer.vue';
</script>

<template>
  <!-- <nested-item></nested-item>
  <nested-menu></nested-menu> -->
<calculator> </calculator>
<CRUD></CRUD>
<flight-booker></flight-booker>
<temp-convert></temp-convert>
<timer></timer>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
