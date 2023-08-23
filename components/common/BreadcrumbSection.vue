<template>
  <div>
    <div class="container-fluid py-5 bg-primary hero-header mb-5">
      <div class="container my-5 py-5 px-lg-5">
        <div class="row g-5 py-5">
          <div class="col-12 text-center">
            <h1 class="text-white animated zoomIn">{{ pageTitle }}</h1>
            <hr class="bg-white mx-auto mt-0" style="width: 90px" />
            <nav aria-label="breadcrumb">
              <ol class="breadcrumb justify-content-center">
                <li class="breadcrumb-item">
                  <a class="text-white" href="#">Home</a>
                </li>
                <li
                  class="breadcrumb-item text-white active"
                  aria-current="page"
                >
                  {{pageTitle}}
                </li>
              </ol>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    pageTitle: {
      type: String,
      default: 'Index'
    }
  }
}
</script>

<style lang="scss" scoped></style>
