<template>
<div>
  <particles-bg type="lines" :num="5" />
      <div class="card">
    <div class="card-body" align="center">
      <h1 class="card-title gradient-text" align="center"><strong>BlogCast</strong></h1>
      <img src="./../../assets/blogcast.png" class="card-img image" />
      <div class="card-text pt-4" align="center">
          <h5><strong>Tech Stack</strong></h5>
        <span><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" class="label"/></span>
        <span><img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" class="label"/></span>
        <span><img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase" class="label"/></span>
      <div class="mt-3 container">
          <h5> A place to write, read blogs and listen and post podcasts as well.</h5> 
          <br />
          <h6><strong>Trying to implement a detailed UI/UX experience<br />
          Based on component architecture to effeciently divide web app into web pages and web pages to reusable components capable of change tolerance.<br />
        </strong></h6>
      </div>
      </div>
    </div>
  </div>
</div>
</template>
<script>
export default {
    name: 'BlogCast',
}
</script>
<style scoped>
.image {
    max-width: 400px;
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
        rgb(2, 88, 2) 16.666%, 
        #00860b 16.666%, 
        #1ca301 33.333%, 
        rgba(0, 168, 126, 0.596) 33.333%, 
        #25b900 50%, 
        rgb(0, 38, 255) 50%, 
        #6d8f00 66.666%, 
        #0051ff 66.666%, 
        #004cf0 83.333%, 
        #0e12f3 83.333%);
  
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