<template>
    <div class="container" id="Experience">
        <h1 align="center"> <strong> Experience </strong></h1>
        <WorkExperience data-aos="fade-left" data-aos-duration="2000" />
        <br />
        <WebDev data-aos="fade-right" data-aos-duration="2000" />
        <br />
        <VicePresident data-aos="fade-left" data-aos-duration="2000" />
        <br />
        <StudentPlacement data-aos="fade-right" data-aos-duration="2000" />
    </div>
</template>

<script>
import WorkExperience from './Experience/Experience.vue';
import StudentPlacement from './Experience/StudentPlacement.vue';
import VicePresident from './Experience/VicePresident.vue'
import WebDev from './Experience/WebDev.vue';

export default {
  components: { WorkExperience, StudentPlacement, VicePresident, WebDev },
    name: 'Experience',
}
</script>