<template>
  <div class="character">
    <h1>{{ name }}</h1>  
    <healthbar/>
  </div>
</template>

<script>
import healthbar from './healthBar.vue'

export default {
  name: 'character',
  components: {
    healthbar
    },
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.character{
    border:1px solid red;
    width:300px;
    display: inline-block;
}
</style>
