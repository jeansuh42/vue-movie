<template>
  <div>
    <Header />
    <router-view />
    <Footer />
  </div>
</template>

<script>
// import Hello from '~/components/Hello.vue'
// import heropy from 'npm-test'
import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
  components: {
    Header,
    Footer
  }
  // , mounted () {
  //   const u = heropy(['A', 'B', 'C', 'A', 'B'])
  //   console.log(u)
  // }
}
</script>


<style lang="scss" scoped>
</style>