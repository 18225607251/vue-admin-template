<template>
  <div style="padding:30px;">
    <el-alert :closable="false" title="menu 1-1" type="success">
      <router-view />
    </el-alert>
    <div class="father" />
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
   .father{
     height: 300px;
     width: 300px;
     background-color: grey;
   }

</style>
