<script>
export default {
  name: "Navbar",
};
</script>

<template>
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Bootstrap 5 Responsive Image Gallery Example</title>
      <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
        rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
        crossorigin="anonymous"
      />
    </head>

    <body>
      <div id="gallery" class="container-fluid">
        <div class="row" style="margin: 0 padding: 0">
          <div class="col-md-4 mt-3 col-lg-4">
            <img
              src="./img/PXL_20230103_235455971.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-4">
            <img
              src="./img/PXL_20221009_170658515.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-4">
            <img
              src="./img/PXL_20221008_220509397.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-6">
            <img
              src="./img/PXL_20230419_035227024.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-6">
            <img
              src="./img/PXL_20221008_223450471.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-3">
            <img
              src="./img/PXL_20221008_213617344.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-3">
            <img
              src="./img/PXL_20221010_184018897.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-3">
            <img
              src="./img/PXL_20221007_191232259.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
          <div class="col-md-4 mt-3 col-lg-3">
            <img
              src="./img/PXL_20221008_225230970.jpg"
              class="img-fluid"
              alt="image"
            />
          </div>
        </div>
      </div>
    </body>
  </html>
</template>

<style scoped></style>
