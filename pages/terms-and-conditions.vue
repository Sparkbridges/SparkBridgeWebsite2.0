<template>
  <div>
    <!-- Navbar & Hero Start -->
    <div class="container-fluid position-relative p-0">
      <NavbarSection />

      <BreadcrumbSection page-title="Terms and Conditions" />
    </div>
    <!-- Navbar & Hero End -->

    <!-- Contact Start -->
    <ContactSection />
    <!-- Contact End -->

    
  </div>
</template>

<script>
import NavbarSection from '../components/common/NavbarSection'
import BreadcrumbSection from '../components/common/BreadcrumbSection'

export default {
  name: 'AboutUs',
  components: {
    NavbarSection,
    BreadcrumbSection,
  },
}
</script>
