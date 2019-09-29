<template>
  <div>
    <Mapa class="mapa"/>
  </div>
</template>

<script>
import Mapa from "./components/Mapa";

export default {
  name: "App",
  components: {
    Mapa
  }
};
</script>

<style lang="scss" scoped>
  .mapa {
    height: 425px;
  }
</style>