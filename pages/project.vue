<template>
    <div>
      <!-- Navbar & Hero Start -->
      <div class="container-fluid position-relative p-0">
        <NavbarSection />
  
        <BreadcrumbSection page-title="Project" />
      </div>
      <!-- Navbar & Hero End -->
  
      <!-- Project Start -->
      <PortfolioSection />
      <!-- Project End -->
  
      
    </div>
  </template>
  
  <script>
  import NavbarSection from '../components/common/NavbarSection'
  import BreadcrumbSection from '../components/common/BreadcrumbSection'
  import PortfolioSection from '../components/common/PortfolioSection'

  export default {
    name: 'AboutUs',
    components: {
      NavbarSection,
      BreadcrumbSection,
      PortfolioSection
    },
  }
  </script>
  