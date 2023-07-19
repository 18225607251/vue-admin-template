<template>
  <div style="padding:30px;">
    <el-alert :closable="false" title="menu 2" />
    <div class="father">
      <div class="son" />
    </div>
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
     background: grey;
     display: flex;
     justify-content: center;
     align-items: center;
     .son{
      height: 100px;
      width: 100px;
      background-color: red;
      // align-self: flex-start;
     }
   }

</style>
