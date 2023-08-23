<template>
  <div>
    <!-- Navbar & Hero Start -->
    <div class="container-fluid position-relative p-0">
      <NavbarSection />

      <BreadcrumbSection page-title="Contact Us" />
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
import ContactSection from '../components/common/ContactSection'

export default {
  name: 'AboutUs',
  components: {
    NavbarSection,
    BreadcrumbSection,
    ContactSection
  },
}
</script>
