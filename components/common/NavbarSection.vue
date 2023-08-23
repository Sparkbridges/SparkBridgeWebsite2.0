<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light px-4 px-lg-5 py-3 py-lg-0">
      <a href="" class="navbar-brand p-0">
        <h1 class="m-0">
          <i class="fa fa-search me-2"></i>SparkBridges<span
            class="fs-5"
          ></span>
        </h1>
        <!-- <img src="@/assets/img/logo.png" alt="Logo"> -->
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarCollapse"
      >
        <span class="fa fa-bars"></span>
      </button>
      <div id="navbarCollapse" class="collapse navbar-collapse">
        <div class="navbar-nav ms-auto py-0">
          <a href="/" class="nav-item nav-link active">Home</a>
          <a href="/about-us" class="nav-item nav-link">About</a>
          <a href="/solution" class="nav-item nav-link">Solution</a>
          <a href="/project" class="nav-item nav-link">Project</a>
          <a href="/contact-us" class="nav-item nav-link">Contact</a>
        </div>
        <butaton
          type="button"
          class="btn text-secondary ms-3"
          data-bs-toggle="modal"
          data-bs-target="#searchModal"
          ><i class="fa fa-search"></i
        ></butaton>
        <a
          href="/contact-us"
          class="btn btn-secondary text-light rounded-pill py-2 px-4 ms-3"
          >Reach Out</a
        >
      </div>
    </nav>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
