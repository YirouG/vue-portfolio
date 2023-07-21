<template>
  <div id="contact" class="text-center" style="padding: 100px">
    <h1>Contact Me</h1>
    <h2>Email: gyr.work@outlook.com</h2>
  </div>
  <!-- <div class="form-container">
    <form class="container">
    
      <div class="form-outline mb-3">
        <input type="text" id="form4Example1" class="form-control" />
        <label class="form-label" for="form4Example1">Name</label>
      </div>

     
      <div class="form-outline mb-3">
        <input type="email" id="form4Example2" class="form-control" />
        <label class="form-label" for="form4Example2">Email address</label>
      </div>

      <div class="form-outline mb-3">
        <textarea class="form-control" id="form4Example3" rows="4"></textarea>
        <label class="form-label" for="form4Example3">Message</label>
      </div>

   
      <div class="form-check d-flex justify-content-center mb-3">
        <input
          class="form-check-input me-2"
          type="checkbox"
          value=""
          id="form4Example4"
          checked
        />
        <label class="form-check-label" for="form4Example4">
          Send me a copy of this message
        </label>
      </div>

   
      <button type="submit" class="btn btn-primary btn-block">Send</button>
    </form>
  </div> -->
</template>

<style scoped>
/* Outer container */
.form-container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

/* Masked form */
.masked-form {
  position: relative;
  background-color: rgba(
    255,
    255,
    255,
    0.7
  ); /* Adjust the alpha value for transparency */
  padding: 15px; /* Adjust the padding for a smaller form */
  border-radius: 10px;
  overflow: hidden;
  width: 50%; /* Adjust the width of the form */
}

/* Media query for responsiveness */
@media (max-width: 768px) {
  .masked-form {
    width: 90%;
  }
}
</style>
