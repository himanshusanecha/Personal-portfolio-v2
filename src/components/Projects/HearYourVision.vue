<template>
  <div>
    <particles-bg type="lines" :num="5" />
    <div class="card">
      <div class="card-body" align="center">
        <h1 class="card-title gradient-text" align="center">
          <strong>Hear Your Vision</strong>
        </h1>
        <img src="./../../assets/smartglass.png" class="card-img image" />
        <div class="card-text pt-4" align="center">
          <h5><strong>Tech Stack</strong></h5>
          <span
            ><img
              src="https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white"
              class="label"
          /></span>
          <div class="mt-3 container">
            <h5>
              Canes for the blind were invented before the 1920s, its about time
              they get an upgrade.
            </h5>
            <br />
            <h6>
              <strong
                >A simple prototype to help blind people avoid obstacles like
                canes but smartly.<br />
                Detects object and makes a buzz sound to alert the user.<br />
                Secured 17th position out of 500+ teams all over world in
                Ideathon conducted by IIIT Pune.
              </strong>
            </h6>
          </div>
          <vs-button
            danger
            size="large"
            href="https://www.youtube.com/watch?v=rvQnkMxZOW8"
          >
            <strong>View on Youtube</strong>
          </vs-button>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "BlogCast",
};
</script>
<style scoped>
.image {
  max-width: 965px;
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
    rgb(2, 88, 2) 16.666%,
    #00860b 16.666%,
    #1ca301 33.333%,
    rgba(0, 168, 126, 0.596) 33.333%,
    #25b900 50%,
    rgb(0, 38, 255) 50%,
    #6d8f00 66.666%,
    #0051ff 66.666%,
    #004cf0 83.333%,
    #0e12f3 83.333%
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