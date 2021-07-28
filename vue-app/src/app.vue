<script>
import HeaderBar from '@/components/header-bar.vue';
import NavBar from '@/components/nav-bar.vue';

export default {
  name: 'App',
  data() {
    return {};
  },
  components: {
    HeaderBar,
    NavBar,
  },
};
</script>


<script>
      "use strict";
      let now = new Date();
      alert( now ); // 현재 날짜 및 시간이 출력됨
      </script>


<template>
  <div id="app">
    <HeaderBar />
    <div class="section columns">
      <NavBar />
      <main class="column">
        <router-view />
      </main>
    </div>
  </div>
</template>

<style lang="scss">
@import 'styles.scss';
</style>
