<template>
  <div>
    <!-- Navbar & Hero Start -->
    <div class="container-fluid position-relative p-0">
      <NavbarSection />

      <HomeSection />
    </div>
    <!-- Navbar & Hero End -->

    <!-- About Start -->
    <AboutSection />
    <!-- About End -->

    <!-- Newsletter Start -->
    <NewsletterSection />
    <!-- Newsletter End -->

    <!-- Service Start -->
    <SolutionSection />
    <!-- Service End -->

    <!-- Portfolio Start -->
    <PortfolioSection />
    <!-- Portfolio End -->

    <!-- Testimonial Start -->
    <TestimonialSection />
    <!-- Testimonial End -->

    <!-- Team Start -->
    <TeamSection />
    <!-- Team End -->
  </div>
</template>

<script>
import AboutSection from '../components/common/AboutSection'
import NewsletterSection from '../components/common/NewsletterSection'
import SolutionSection from '../components/common/SolutionSection'
import PortfolioSection from '../components/common/PortfolioSection'
import TestimonialSection from '../components/common/TestimonialSection'
import TeamSection from '../components/common/TeamSection'
import NavbarSection from '../components/common/NavbarSection'
import HomeSection from '../components/common/HomeSection'

export default {
  name: 'IndexPage',
  components: {
    AboutSection,
    NewsletterSection,
    SolutionSection,
    PortfolioSection,
    TestimonialSection,
    TeamSection,
    NavbarSection,
    HomeSection,
  },
}
</script>
