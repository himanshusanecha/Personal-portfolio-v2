<template>
  <div class="mt-5">
    <Navbar />
    <div class="container" data-aos="fade-up" data-aos-duration="1000" id="About">
    <div class="row justify-content-center">
        <div class="col-sm-7">
        <MyCard />
        </div>
        <div class="col image">
            <div class="limit mx-auto mt-2">
            <img src="./../assets/himanshu.gif"/> 
        </div>
        </div>
    </div>
  </div>
  <Projects id="Projects" />
  <br />
  <br />
  <Experience id="Experience" />
  <br />
  <div align="center">
  <Skills data-aos="fade-up" data-aos-duration="1000" id="Skills" />
  </div>
  <div class="container" data-aos="fade-up" data-aos-duration="1000" id="Contact">
    <div class="row justify-content-center">
        <div class="col-sm-7">
        <ContactForm />
        </div>
        <div class="col image">
            <div class="limit mx-auto">
            <img src="./../assets/contact.gif"/> 
        </div>
        </div>
    </div>
  </div>
</div>
</template>

<script>
import Skills from './Skills.vue';
import MyCard from "./MyCard.vue";
import Navbar from "./Navbar.vue";
import Projects from "./Projects.vue";
import Experience from "./Experience.vue";
import ContactForm from './ContactForm.vue';
export default {
  name: "Page",
  components: {
    Navbar,
    MyCard,
    Projects,
    Experience,
    Skills,
    ContactForm,
  },
};
</script>
<style scoped>
.limit{
        width: 300px;
        height: 300px;
        max-height: 300px;
        overflow: hidden;
     }
    .limit img{
       width: 100%;
       height: 100%;
       padding-left: auto; 
       padding-right: auto;
     }
     .image {
         margin-top: 10%;
     }
</style>
