<template lang="pug">
.box
  h1 {{ msg }}
</template>
<script>
export default {
  data () {
    return {
      msg: 'hello'
    }
  }
}
</script>
<style lang="scss" scoped>
.box{
  h1{
      font-size: 32px;
      color: lightcoral;
  }
}
</style>
