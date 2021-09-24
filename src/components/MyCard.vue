<template>
  <div class="mycard">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Hello! Myself Himanshu Sanecha</h5>
        <p class="card-text">
          🙋 Hello myself Himanshu Sanecha.<br />
          🏠 Currently pursuing my undergraduate in IIIT Vadodara.<br />
          ✨ I love to solve problems involving data structures, algorithms and
          mathematics. <br />
          💁 I love to build Web applications starting from
          designing to writing efficient algorithms in the backend. 
        </p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.mycard {
  margin-top: 20%;
  border-radius: 20%;
  box-shadow: 0 0 15px rgba(237, 92, 241, 0.75);
    clip-path: inset(0px -15px 0px 0px);
}
.card {
  flex-direction: row;
  align-items: center;
  border: none;
  border-radius: 5%;
}
.card-title {
  font-weight: bold;
}
.card img {
  width: 50%;
  border-top-right-radius: 0;
  border-bottom-left-radius: calc(0.25rem - 1px);
}
@media only screen and (max-width: 768px) {
  a {
    display: none;
  }
  .card-body {
    padding: 0.5em 1.2em;
  }
  .card-body .card-text {
    margin: 0;
  }
  .card img {
    width: 50%;
  }
}
@media only screen and (max-width: 1200px) {
  .card img {
    width: 40%;
  }
}
</style>