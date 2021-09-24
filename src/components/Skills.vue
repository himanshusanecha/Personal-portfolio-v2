<template>
  <div class="card">
    <div class="card-body">
      <h2 class="card-title gradient-text" align="center">
        <strong>Skills</strong>
      </h2>
      <div class="card-text pt-4" align="center">
        <h5><strong>Languages</strong></h5>
        <span
          ><img
            src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"
            class="label"
        /></span>
        <span
          ><img
            src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"
            class="label"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white"
        /></span>
        <span
          ><img
            src="https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white"
        /></span>
        <h5 class="mt-3"><strong>Frameworks</strong></h5>
        <span
          ><img
            src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"
            class="label"
        /></span>
        <span
          ><img
            src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D"
            class="label"
        /></span>
        <span
          ><img
            src="https://img.shields.io/badge/-Bootstrap-05122A?style=flat&logo=bootstrap&logoColor=563D7C"
            class="label"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black"
        /></span>
        <span class="mr-1"
          ><img
            src="https://img.shields.io/badge/-Bootstrap-05122A?style=flat&logo=bootstrap&logoColor=563D7C"
        /></span>
        <h5 class="mt-3"><strong>Databases</strong></h5>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"
        /></span>
        <span
          ><img
            src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"
        /></span>
        <h5 class="mt-3"><strong>Package managers</strong></h5>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white"
        /></span>
        <span
          ><img
            src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white"
        /></span>
        <h5 class="mt-3"><strong>IDE</strong></h5>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"
        /></span>
        <span
          ><img
            src="https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white"
        /></span>
        <h5 class="mt-3"><strong>Others</strong></h5>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"
        /></span>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"
        /></span>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white"
        /></span>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"
        /></span>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"
        /></span>
        <span class="mr-2"
          ><img
            src="https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white"
        /></span>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Skills",
};
</script>
<style scoped>
.image {
  width: 100%;
  max-width: 1200px;
}
.card {
  border: 0;
  outline: 0;
}
.label {
  margin-right: 0.5%;
}
.gradient-text {
  /* Fallback: Set a background color. */
  background-color: #ca4246;

  /* Create the gradient. */
  background-image: linear-gradient(
    45deg,
    #0026fd 16.666%,
    #0051ff 16.666%,
    #0026ff 33.333%,
    rgb(25, 0, 255) 33.333%,
    #1900ffce 50%,
    black 50%,
    #000000da 66.666%,
    #6797ff 66.666%,
    #b0c9ff 83.333%,
    #0051ff 83.333%
  );

  /* Set the background size and repeat properties. */
  background-size: 100%;
  background-repeat: repeat;

  /* Use the text as a mask for the background. */
  /* This will show the gradient as a text color rather than element bg. */
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;

  /* Animate the text when loading the element. */
  /* This animates it on page load and when hovering out. */
  animation: rainbow-text-simple-animation-rev 0.75s ease forwards;
}

.gradient-text:hover {
  animation: rainbow-text-simple-animation 0.5s ease-in forwards;
}

/* Move the background and make it smaller. */
/* Animation shown when entering the page and after the hover animation. */
@keyframes rainbow-text-simple-animation-rev {
  0% {
    background-size: 650%;
  }
  40% {
    background-size: 650%;
  }
  100% {
    background-size: 100%;
  }
}

/* Move the background and make it larger. */
/* Animation shown when hovering over the text. */
@keyframes rainbow-text-simple-animation {
  0% {
    background-size: 100%;
  }
  80% {
    background-size: 650%;
  }
  100% {
    background-size: 650%;
  }
}
</style>
