<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <!-- Navbar brand -->
    <a class="navbar-brand" href="#">My Portfolio</a>

    <!-- Collapse button -->
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <!-- Collapsible content -->
    <div class="collapse navbar-collapse" id="navbarNav">
      <!-- Links -->
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <!-- Use href instead of @click for navigation -->
          <a class="nav-link" href="#jumbotron">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#gallery">Gallery</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
/* Your styles go here */
</style>
