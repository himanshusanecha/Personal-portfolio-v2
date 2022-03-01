<template>
  <div id="app">
    <Loading v-if="loading" />
    <div v-else class="mt-3">
      <Page />
      <particles-bg type="circle" :num="5" :bg="true" />
    </div>
  </div>
</template>

<script>
import { ParticlesBg } from "particles-bg-vue";
import Loading from "./components/Loading.vue";
import Page from "./components/Page.vue";
//comment
export default {
  name: "Himanshu Sanecha",
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
@media only screen and (max-width: 600px) {
  #app {
    overflow-x: hidden;
    overflow-y: hidden;
    margin-top: 0.5%;
  }
}
@media only screen and (min-width: 600px) {
  #app {
    overflow-x: hidden;
    overflow-y: hidden;
    margin-top: 0.5%;
  }
}

</style>
