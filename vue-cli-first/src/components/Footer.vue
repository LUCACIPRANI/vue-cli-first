<template>
  <div class="hello">
    <h1>{{ message }}</h1>
    
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    message: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  margin: 40px 0 0;
}
a {
  color: red;
}
</style>
