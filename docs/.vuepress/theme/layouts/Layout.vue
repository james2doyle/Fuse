<template>
  <ParentLayout>
    <!-- <template #sidebar-top>
      <Version />
    </template> -->
    <template #sidebar-top>
      <CarbonAds />
    </template>
    <template #sidebar-bottom>
      <Donate />
    </template>
    <!-- <template #page-bottom>
      <BuySellAds />
    </template> -->
    <!-- <template #page-bottom>
      <Footer />
    </template> -->
  </ParentLayout>
</template>

<script>
import ParentLayout from '@parent-theme/layouts/Layout.vue'
import CarbonAds from '@theme/components/CarbonAds.vue'
import Donate from '@theme/components/Donate.vue'
// import Footer from '@theme/components/Footer.vue'
// import BuySellAds from '@theme/components/BuySellAds.vue'
// import Version from '@theme/components/Version.vue'

export default {
  name: 'Layout',
  components: {
    ParentLayout,
    // Version
    CarbonAds,
    Donate
    // Footer
    // BuySellAds
  }
}
</script>
