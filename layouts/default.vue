<template>
  <div class="d-flex">
    <Sidebar/>
    <div class="body-part">
      <Header/>
      <Nuxt />
    </div>
  </div>
</template>

<script>
import Sidebar from "../components/Sidebar";
import Header from "../components/Header";
export default {
  name: "default",
  components: {
    Sidebar,
    Header
  }
}
</script>

<style scoped>

</style>