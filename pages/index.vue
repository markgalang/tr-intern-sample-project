<template lang="pug">
    section
      home
      aboutUs
      conv
      howItWorks
      contactUs
      foot

</template>

<script>
import home from '~/components/home.vue'
import aboutUs from '~/components/about.vue'
import conv from '~/components/conv.vue'
import howItWorks from "~/components/howItWorks.vue"
import contactUs from "~/components/contactUs.vue"
import foot from "~/components/foot.vue"
export default {
  components: {
    home,
    aboutUs,
    conv,
    howItWorks,
    contactUs,
    foot

  }
}
</script>

<style>

</style>
