<template>
  <div class="card">
    <div class="card-body">
      <h1 class="card-title gradient-text" align="center"><strong>Scripture</strong></h1>
      <img src="./../../assets/Scripture.png" class="card-img" />
      <div class="card-text pt-4" align="center">
          <h5><strong>Tech Stack</strong></h5>
        <span><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" class="label"/></span>
        <span><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" class="label" /></span>
        <span><img src="https://img.shields.io/badge/-Bootstrap-05122A?style=flat&logo=bootstrap&logoColor=563D7C" class="label" /></span>
        <span><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" class="label" /></span>
        <span><img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" class="label" /></span>
        <span><img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" class="label" /></span>
      <div class="mt-3 container">
          <h5>Tired of writing in pen and paper all day ? <br />
          Here is a full fledged web application for creating and storing personal notes<br />
          </h5>
          <br />
          <h6><strong>Designed the workflow of the web application and developed endpoints for CRUD operation</strong></h6>
      </div>
      <span>
      <vs-button
       default
        size="large"
        href="https://github.com/himanshusanecha/scripture"
      >
        <strong>View On Github</strong>
      </vs-button>
      <vs-button
       dark
        size="large"
        href="http://scripture.host20.uk/"
      >
        <strong>Live View</strong>
      </vs-button>
      </span>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Scripture",
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
  border-radius: 20%;
  background: transparent;
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
        #00ff37 16.666%, 
        #5ae200 16.666%, 
        #2afa00 33.333%, 
        rgb(43, 255, 0) 33.333%, 
        #63cc00ce 50%, 
        black 50%, 
        #6e8f00da 66.666%, 
        #476098 66.666%, 
        #2861da 83.333%, 
        #f53fdd 83.333%);
  
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
