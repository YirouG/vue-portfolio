<script>
export default {
  name: "Jumbotron",
};
</script>

<template>
  <div id="jumbotron" class="position-relative">
    <div
      class="p-5 text-center bg-image"
      style="
        background-image: url('https://github.com/YirouG/portfolio/blob/main/images/titlebg.jpg?raw=true);
        height: 800px;
        background-size: cover;
        background-repeat: no-repeat;
      "
    >
      <div class="d-flex justify-content-center align-items-center h-100">
        <div class="text-white">
          <h1 class="mb-3">Roxy Guo Yirou</h1>
          <h4 class="mb-3">with a moving camera</h4>
          <a class="btn btn-outline-light btn-lg" href="#!" role="button"
            >Contact Me</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
