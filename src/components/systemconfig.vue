<template>
  <div class="sys-config">
      <iframe :src="`${configPath}/Configs/index.html`" frameborder="0"></iframe>
  </div>
</template>
<script>
    export  default{
        mounted(){
            this.$Spin.hide()
        }
    }
</script>
<style>
    .sys-config{
        height: 100%;
        width: 100%;
    }
    iframe{
        height: 100%;
        width: 100%;
    }
</style>
