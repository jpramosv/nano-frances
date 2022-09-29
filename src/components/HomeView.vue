<template>
  <TopoView />
  <IntroducaoView />
  <ApresentacaoView />
  <LaLune />
  <CardsModulos />
  <DepoimentoAlunos />
  <BonusCourse />
</template>

<script>
import TopoView from "../components/TopoView.vue";
import IntroducaoView from "../components/IntroducaoView.vue";
import ApresentacaoView from "../components/ApresentacaoView.vue";
import LaLune from "../components/LaLune.vue";
import CardsModulos from "../components/CardsModulos.vue";
import DepoimentoAlunos from "../components/DepoimentoAlunos.vue"
import BonusCourse from "../components/BonusCourse.vue"

export default {
  name: "HomeView",
  components: {
    TopoView,
    IntroducaoView,
    ApresentacaoView,
    LaLune,
    CardsModulos,
    DepoimentoAlunos,
    BonusCourse
  },
};
</script>

<style>

</style>  