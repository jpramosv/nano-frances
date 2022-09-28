<template>
  <TopoView />
  <IntroducaoView />
  <ApresentacaoView />
  <LaLune />
  <CardsModulos />
</template>

<script>
import TopoView from "../components/TopoView.vue";
import IntroducaoView from "../components/IntroducaoView.vue";
import ApresentacaoView from "../components/ApresentacaoView.vue";
import LaLune from "../components/LaLune.vue";
import CardsModulos from "../components/CardsModulos.vue";

export default {
  name: "HomeView",
  components: {
    TopoView,
    IntroducaoView,
    ApresentacaoView,
    LaLune,
    CardsModulos
  },
};
</script>

<style>

</style>  