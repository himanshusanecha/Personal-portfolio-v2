<template>
      <div class="card">
    <div class="card-body">
      <h1 class="card-title gradient-text" align="center"><strong>Tikaj</strong></h1>
      <div align="center">
      <img src="./../../assets/tikaj3.svg" class="card-img image">
      </div>
      <div class="card-text pt-4" align="center">
          <h5><strong>Full Stack Developer Intern</strong></h5>
      <div class="mt-3 container">
        <h5>TIKAJ is a technology company that, at its core, aims to make technology sync with people, as protecting and securing data ought to never be a choice but rather be a necessity.</h5>
          <h6><strong>As a full stack developer intern i am responsible for some modules, UI/UX elements, API's and their integration and much more.....</strong></h6>
      </div>
      <vs-button
       default
        size="large"
        href=""
        danger
      >
        <strong>Tikaj LinkedIn</strong>
      </vs-button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name: 'WorkExperience'
}
</script>
<style scoped>
.image {
  width: 100%;
  max-width: 550px;
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
        #e90008 16.666%, 
        #ff0000 16.666%, 
        #fa0000 33.333%, 
        red 33.333%, 
        #ff0000 50%, 
        black 50%, 
        #6d8f00 66.666%, 
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