<template>
  <div>
    <div class="d-flex flex-column page">
      <FolderComponent/>
      <MaterialComponent/>
    </div>
  </div>
</template>

<script>
import FolderComponent from "../components/dashboard/FolderComponent";
import MaterialComponent from "../components/dashboard/MaterialComponent";
export default {
  name: 'IndexPage',
  layout: 'default',
  components: {
    FolderComponent,
    MaterialComponent
  }
}
</script>
