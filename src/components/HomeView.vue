<template>
  <TopoView />
  <IntroducaoView />
</template>

<script>
import TopoView from "../components/TopoView.vue";
import IntroducaoView from "../components/IntroducaoView.vue";

export default {
  name: "HomeView",
  components: {
    TopoView,
    IntroducaoView,

  },
};
</script>

<style>

</style>