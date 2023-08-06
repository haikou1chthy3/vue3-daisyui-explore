<script setup lang="ts">
import SelectExample from './components/SelectInput/SelectExample.vue'
import SelectInput from './components/SelectInput/Index.vue'
import Layout from './layout/Index.vue'
import SideBar from './layout/SideBar/Index.vue'
import HeaderNav from './layout/HeaderNav/Index.vue'
import Container from './layout/Container/Index.vue'
import Footer from './layout/Footer/Index.vue'
</script>

<template>
  <div>
    <!-- Layout布局组件 -->
    <Layout class="flex">
      <SideBar />
      <div class="w-full">
        <HeaderNav />
        <Container />
        <Footer />
      </div>
    </Layout>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
