<template>
  <div>
    <!-- component -->
    <div class="w-full h-screen">
      <div class="relative">
        <TopNav/>
      </div>
      
      <slot></slot>

      <Footer/>
    </div>
  </div>
</template>

<script>
import TopNav from './TopNav.vue'
import Footer from './Footer.vue'
  export default {
    name : "LayoutView",
    components: {
      TopNav,Footer
    }
  }
</script>

