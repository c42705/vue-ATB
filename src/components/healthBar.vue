<template>
  <div class="healthbar">
    <span>100%</span>
  </div>
</template>

<script>
export default {
  name: 'healthbar',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.healthbar{
    border:1px solid greenyellow;
    width:200px;
    height: 50px;
    display: inline-block;
}
</style>
