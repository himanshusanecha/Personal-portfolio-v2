<template>
<div class="center">
    <img src="./../assets/loading.gif" class="responsive" />
</div>
</template>

<script>
export default {
    name: 'Loading'
}
</script>

<style scoped>
.responsive {
width: 100%;
  max-width: 400px;
  height: 100%;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: auto;
  margin-top: auto;
}
.center {
    display: flex;
    margin: auto;
}
</style>
