<script>
import CompCaixas from "@/components/CompCaixas.vue";
export default {
  components: { CompCaixas },
  data() {
    return {
      musicas1: [],
      musicas2: [],
    };
  },
};
</script>
<template>
  <main id="content">
    <CompCaixas titulo="The Clash" />
    <CompCaixas titulo="Nirvana" />
    <CompCaixas titulo="Pentakill" />
    <CompCaixas titulo="The Beatles" />
    <CompCaixas titulo="Peatch" />
    <CompCaixas titulo="One Pice" class="one" />
  </main>
</template>
<style></style>
