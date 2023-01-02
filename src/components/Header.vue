<template>
  <nav class="navber">
    <!-- ロゴ -->
    <div class="title">ロゴ</div>
    <!-- メニュー -->
    <section class="menu">
      <div class="btn">
        <span class="material-symbols-outlined"> home </span><span>ホーム</span>
      </div>
      <div class="btn">
        <span class="material-symbols-outlined"> face </span
        ><span>アカウント</span>
      </div>
      <div class="btn">
        <span class="material-symbols-outlined"> output </span
        ><span>ログアウト</span>
      </div>
    </section>
  </nav>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      name: "test",
    };
  },
};
</script>

<style scoped>
.navber {
  padding: 0.5rem 1rem;
  display: flex;
  background-color: var(--main-color);
}
.title {
  font-size: 1.5rem;
  font-weight: bold;
}
.navber .menu {
  margin-left: auto;
  display: flex;
  gap: 0.5rem;
}
.navber .btn {
  display: flex;
  background-color: var(--sub-color);
  padding: 0.5rem;
  border-radius: 0.5rem;
}
</style>
