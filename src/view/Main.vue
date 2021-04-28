<template>
  <div class="main-container">
    <header class="header-container">
      <div></div>
      <img :src="icon" alt="">
      <div>
        <img src="" alt="">
      </div>
    </header>
  </div>
</template>
<script>
// import Header from '@/components/header'
export default {
  name: 'Main',
  components: {
    // Header
  },
  data () {
    return {
      icon: require('@/assets/logo/logo.svg')
    }
  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.main-container{
  height: 100%;
}
</style>
