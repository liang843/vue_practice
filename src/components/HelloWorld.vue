<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <div :style="{ background: 'rgb(190, 200, 200)', padding: '26px 16px 16px' }">
    <a-button type="primary" ghost disabled>
      失效
    </a-button>
    <a-button ghost shape="circle">
     形状 
    </a-button>
    <a-button type="danger" ghost >
      类型
    </a-button>
    <a-button type="primary" ghost>
      Danger
    </a-button>
    <a-button type="link" ghost>
      Link
    </a-button>
  </div>
  
    
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
<style scoped>
a {
  color: #42b983;
}
</style>
