<template>
  <Header></Header>
  <main>
    <div>トップページ</div>
  </main>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "HomeView",
  components: {
    Header,
  },
};
</script>

<style scoped>
main {
  padding: 1rem;
}
</style>
