<template>
  <div>
    <!-- Navbar & Hero Start -->
    <div class="container-fluid position-relative p-0">
      <NavbarSection />

      <BreadcrumbSection page-title="Solution" />
    </div>
    <!-- Navbar & Hero End -->

    <!-- About Start -->
    <AboutSection />
    <!-- About End -->

    <!-- Newsletter Start -->
    <NewsletterSection />
    <!-- Newsletter End -->

    <!-- Team Start -->
    <TeamSection />
    <!-- Team End -->
  </div>
</template>

<script>
import AboutSection from '../components/common/AboutSection'
import NewsletterSection from '../components/common/NewsletterSection'
import TeamSection from '../components/common/TeamSection'
import NavbarSection from '../components/common/NavbarSection'
import BreadcrumbSection from '../components/common/BreadcrumbSection'

export default {
  name: 'AboutUs',
  components: {
    AboutSection,
    NewsletterSection,
    TeamSection,
    NavbarSection,
    BreadcrumbSection,
  },
}
</script>
