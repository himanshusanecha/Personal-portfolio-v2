<template>
  <div class="card">
    <div class="card-body">
      <h2 class="card-title gradient-text" align="center"><strong>Social Website Design</strong></h2>
      <img src="./../../assets/Social.png" class="card-img" />
      <div class="card-text pt-4" align="center">
          <h5><strong>Tech Stack</strong></h5>
        <span><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" class="label"/></span>
        <span><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" class="label" /></span>
        <span><img src="https://img.shields.io/badge/-Bootstrap-05122A?style=flat&logo=bootstrap&logoColor=563D7C" class="label" /></span>
      <div class="mt-3 container">
          <h5>Social Page Design<br />
          A single page website designed from scratch just to practice CSS and Bootstrap.
          </h5>
          <vs-button
       default
        size="large"
        href="https://github.com/himanshusanecha/Social-Theme"
      >
        <strong>View On Github</strong>
      </vs-button>
      <vs-button
       dark
        size="large"
        href="https://himanshusanecha.github.io/Social-Theme/"
      >
        <strong>Live View</strong>
      </vs-button>
      </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "SocialProject",
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
  background-color: #CA4246;
  
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
        #0051ff 83.333%);
  
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

.gradient-text:hover{
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
