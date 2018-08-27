<template>
  <div class="home">
    <h1>{{ msg }}</h1>


  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to My Vue Project :)'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
  @import '../mq'

</style>
