<template>
  <div id="app">
    <Loading v-if="loading" />
    <div v-else>
      <Page />
      <particles-bg type="circle" :num="5" :bg="true" />
    </div>
  </div>
</template>

<script>
import { ParticlesBg } from "particles-bg-vue";
import Loading from "./components/Loading.vue";
import Page from "./components/Page.vue";
export default {
  name: "Portfolio",
  data: function () {
    return {
      loading: true,
    };
  },
  components: {
    Loading,
    Page,
    ParticlesBg,
  },
  mounted() {
    window.setTimeout(() => {
      this.loading = false;
    }, 3000);
  },
};
</script>
<style>
#app {
  font-family: "Roboto Slab", serif;
  font-size: 25px;
}

</style>
