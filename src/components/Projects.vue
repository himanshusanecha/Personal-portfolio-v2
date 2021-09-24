<template>
<div class="mt-5">
    <h1 align="center"> <strong> Projects </strong></h1>
    <div class="container mt-5" id="Projects">
        <Scripture data-aos="fade-up" data-aos-duration="1000" />
        <br />
        <Ecommerce data-aos="fade-up" data-aos-duration="1000"/>
        <br />
        <SocialProject data-aos="fade-up" data-aos-duration="1000" />
        <br />
        <HearYourVision data-aos="fade-up" data-aos-duration="1000" />
        <br />
        <blogCast data-aos="fade-up" data-aos-duration="1000" />
    </div>
</div>
</template>

<script>
import Scripture from './Projects/Scripture.vue'
import SocialProject from './Projects/SocialProject.vue'
import Ecommerce from './Projects/Ecommerce.vue';
import blogCast from './Projects/blogCast.vue';
import HearYourVision from './Projects/HearYourVision.vue';

export default {
  components: { Scripture, SocialProject, Ecommerce, blogCast, HearYourVision},
    name: 'Projects',
}
</script>
<style scoped>
.image {
    width: 100%;
    max-width: 1200px
}
h1 {
    font-size: 40px;
    font-weight: 700;
}
</style>