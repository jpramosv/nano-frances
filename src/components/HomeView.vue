<template>
  <TopoView />
  <IntroducaoView />
  <ApresentacaoView />
  <LaLune />
  <CardsModulos />
  <DepoimentoAlunos />
  <BonusCourse />
  <InformationSection />
</template>

<script>
import TopoView from "../components/TopoView.vue";
import IntroducaoView from "../components/IntroducaoView.vue";
import ApresentacaoView from "../components/ApresentacaoView.vue";
import LaLune from "../components/LaLune.vue";
import CardsModulos from "../components/CardsModulos.vue";
import DepoimentoAlunos from "../components/DepoimentoAlunos.vue";
import BonusCourse from "../components/BonusCourse.vue";
import InformationSection from "../components/InformationSection.vue";

export default {
  name: "HomeView",
  components: {
    TopoView,
    IntroducaoView,
    ApresentacaoView,
    LaLune,
    CardsModulos,
    DepoimentoAlunos,
    BonusCourse,
    InformationSection
  },
};
</script>

<style>

</style>  