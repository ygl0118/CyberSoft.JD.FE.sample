<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      All you need to do is to try to finish following statements:
    </p>
    <div class="content-wrapper">
      <div>
        <input type="checkbox" id="todo1" name="todo1" value="todo1">
        <label for="todo1">Add some buttons that you can switch to other pages with at least two different contents</label>
      </div>
      <div>
        <input type="checkbox" id="todo2" name="todo2" value="todo2">
        <label for="todo2">Create new components for functional interactions, like exchange rate conversion between NTD and others</label>
      </div>
      <div>
        <input type="checkbox" id="todo3" name="todo3" value="todo3">
        <label for="todo3">What ever you want do to get more bonus</label>
      </div>
    </div>
    <h2>
      Reference
    </h2>
    <p>
      臺灣期貨交易所 OAS <a href="https://openapi.taifex.com.tw/" target="_blank">https://openapi.taifex.com.tw/</a>
    </p>
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
.content-wrapper {
  display: flex;
  justify-content: center;

  div {
    width: 30%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
