<template>
      <div class="card">
    <div class="card-body">
      <h1 class="card-title gradient-text" align="center"><strong>Cultural Committee IIITV</strong></h1>
      <div align="center">
      <img src="./../../assets/kreiva.jpg" class="card-img image">
      </div>
      <div class="card-text pt-4" align="center">
          <h5><strong>Vice President</strong></h5>
      <div class="mt-3 container">
        <h5>Cultural Committee of Indian Institute of Vadodara is responsible for conducting various cultural activities that happen around the year. </h5>
          <h6><strong>Being Vice President conducted our cultural fest in online mode and got more than 1170 enteries PAN India</strong></h6>
      </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name: 'VicePresident'
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
        #003d83 16.666%, 
        #ff0000 16.666%, 
        #2803f7 33.333%, 
        rgb(0, 47, 255) 33.333%, 
        #1100ff 50%, 
        black 50%, 
        #000000 66.666%, 
        #000000 66.666%, 
        #000000 83.333%, 
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