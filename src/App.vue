<template>
  <div id="app">
    <InfiniteScroll class="infi-scroll"> </InfiniteScroll>
  </div>
</template>

<script>
import InfiniteScroll from "./components/InfiniteScroll";

export default {
  name: "App",
  components: {
    InfiniteScroll,
  },
};
</script>

<style lang="scss">
#app {
  height: 80vh;
  margin-top: 10%;

  font-family: "Avenir", Helvetica, Arial, sans-serif;

  .infi-scroll {
    width: 100%;
    margin-left: auto;
    margin-right: auto;
    height: 100%;
  }
}
</style>
