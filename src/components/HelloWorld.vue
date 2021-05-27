<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      All you need to do is to try to finish following statements:
    </p>
    <ol>
      <li>Add some buttons that you can switch to other pages with at least two different contents</li>
      <li>Create new components for functional interactions, like exchange rate conversion between NTD and others</li>
      <li>What ever you want do to get more bonus</li>
    </ol>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>

</style>
