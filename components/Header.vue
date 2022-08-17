<template>
<div class="header">
  <div class="header__location">
    <el-dropdown>
      <span class="el-dropdown-link">
        <i>
          <svg width="24" height="14" viewBox="0 0 24 14" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M2 0.862183H22.0002V4.95518H2V0.862183Z" fill="white"/>
<path d="M2 9.0448H22.0002V13.1378H2V9.0448Z" fill="#D52B1E"/>
<path d="M2 4.9552H22.0002V9.0482H2V4.9552Z" fill="#0057FF"/>
</svg>

        </i>
        RU<i class="el-icon-arrow-down el-icon--right"></i>
      </span>
      <el-dropdown-menu slot="dropdown">
        <el-dropdown-item>Action 1</el-dropdown-item>
        <el-dropdown-item>Action 2</el-dropdown-item>
        <el-dropdown-item>Action 3</el-dropdown-item>
        <el-dropdown-item disabled>Action 4</el-dropdown-item>
        <el-dropdown-item divided>Action 5</el-dropdown-item>
      </el-dropdown-menu>
    </el-dropdown>
  </div>
  <div class="header__avatar">
    <span>Александр Нистеренко</span>
    <div class="ava">
      <img src="@/static/img/ava.png" alt="">
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>