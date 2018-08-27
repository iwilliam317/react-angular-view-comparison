<template>
  <div class="faq">
    <h1>{{msg}}</h1>


  </div>
</template>

<script>
export default {
  name: 'Faq',
  data () {
    return {
      msg: 'My FAQ page'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
  @import '../mq'
</style>
