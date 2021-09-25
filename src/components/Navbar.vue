<template>
<div class="nav-bar mt-5">
      <span class="mx-auto" >
      <ul class="nav justify-content-center">
        <li class="nav-item fontmax" @click="ChangeRoute('#About')" :class="{active: value=='#About'}"><vs-button
        circle
        size="large"
      >
       <strong> About </strong>
      </vs-button></li>
        <li class="nav-item fontmax" href="#Projects" @click="ChangeRoute('#Projects')" :class="{active: value=='#Projects'}"><vs-button
        circle
        size="large"
        success
        href="#Projects"
      >
      <strong> Projects </strong>
      </vs-button></li>
        <li class="nav-item fontmax" href="#Skills" @click="ChangeRoute('#Skills')" :class="{active: value=='#Skills'}"><vs-button
        circle
        size="large"
         warn
         href="#Skills"
      >
       <strong> Skills </strong>
      </vs-button></li>
        <li class="nav-item fontmax" href="" @click="ChangeRoute('#About')"><vs-button
        circle
        size="large"
        href="#Experience"
        dark
      >
       <strong> Experience </strong>
      </vs-button></li>
      <li class="nav-item fontmax" href="" @click="ChangeRoute('#About')"><vs-button
        circle
        size="large"
        danger
        blank
        href="https://drive.google.com/file/d/1EPJvOQpk7KLHBAAX7vlJde_iZk_i5KxN/view?usp=sharing"
      >
       <strong> Resume </strong>
      </vs-button></li>
      
      </ul>
      </span>
</div>
</template>

<script>

export default {
  name: 'Navbar',
  data() {
    return {
      value: "#About"
    }
  },
  methods: {
    ChangeRoute(value) {
      console.log(value);
      this.value = value;
      this.$route.push(value);
    }
  }
}
</script>

<style>
.navbar {
  background: white;
}
.active {
  color: rgba(0, 0, 0, 0.9)
}
.fontmax {
  font-size: 50px;
  margin-right: 2%;
}
.nav-bar {
  position: sticky;
}
</style>
