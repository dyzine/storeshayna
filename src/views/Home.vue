<template>
  <div class="home">
    <ShaynaHeader />
    <ShaynaHero />
    <ShaynaProduct />
    <ShaynaInsta />
    <ShaynaPartner />
    <ShaynaFooter />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import ShaynaHeader from '@/components/ShaynaHeader.vue'
import ShaynaHero from '@/components/ShaynaHero.vue'
import ShaynaProduct from '@/components/ShaynaProduct.vue'
import ShaynaInsta from '@/components/ShaynaInsta.vue'
import ShaynaPartner from '@/components/ShaynaPartner.vue'
import ShaynaFooter from '@/components/ShaynaFooter.vue'

export default {
  name: 'Home',
  components: {
    ShaynaHeader,
    ShaynaHero,
    ShaynaProduct,
    ShaynaInsta,
    ShaynaPartner,
    ShaynaFooter
  }
}
</script>
