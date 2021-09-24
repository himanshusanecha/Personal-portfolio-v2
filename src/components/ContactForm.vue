<template>
<div class="mt-5" align="center">
    <h1 align="center">Contact Me!</h1>
<div class="container">
  <form method="POST" action="https://formspree.io/f/xbjqwelb">
    <div class="row">
      <div class="col-25">
        <label for="fname">Name</label>
      </div>
      <div class="col-75">
        <input type="text" id="fname" name="name" placeholder="Your name..">
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="lname">Email</label>
      </div>
      <div class="col-75">
        <input type="text" id="lname" name="email" placeholder="Your Email..">
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="subject">Message</label>
      </div>
      <div class="col-75">
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
      </div>
    </div>
    <div class="row">
        <div class="col" align="center">
      <vs-button danger size="large" to="https://formspree.io/f/xbjqwelb">
          <strong>Send Message</strong>
        </vs-button>
        </div>
    </div>
  </form>
</div>
</div>
</template>
<script>
export default {
  name: "Scripture",
};
</script>
<style scoped>
input[type=text], select, textarea {
  width: 90%;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
  font-size: 1rem;
}

label {
  padding: 8px 8px 8px 0;
  display: inline-block;
}

.container {
  border-radius: 5px;
  padding: 10px;
}

.col-25 {
  float: left;
  width: 25%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
