<template>
  <div class="d-flex">
    <Sidebar/>
    <div class="body-part">
      <Header/>
      <div class="body-inner">
        <Nuxt />
      </div>
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
