<template>
  <div>
<!--    头部-->
    <Header />

<!--    主题-->
    <div style="display: flex">
<!--      侧边栏-->
      <Aside />
<!--      内容区域-->
      <router-view style="flex: 1"/>
    </div>
  </div>

</template>

<style>

</style>

<script>
import Header from "./components/Header.vue";
import Aside from "./components/Aside.vue";

export default {
  name: "Layout",
  components: {
    Header,
    Aside
  }
}
</script>
