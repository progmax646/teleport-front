<template>
  <div>
    <div class="d-flex flex-column page">
      <FolderComponent/>
    </div>
  </div>
</template>

<script>
import FolderComponent from "../components/dashboard/FolderComponent";
export default {
  name: 'IndexPage',
  layout: 'default',
  components: {
    FolderComponent
  }
}
</script>
