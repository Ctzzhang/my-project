<template>
  <div class="info">
</header>
    <h1>{{ msg }}</h1>
    <h3>{{ msg1 }}</h3>
    <hr/>
    <h2>{{ msg2 }}</h2>
    <h2>{{ msg3 }}</h2>
    <h2>{{ msg4 }}</h2>
  </div>
</template>

<script>
export default {
  name: 'info',
  data () {
    return {
      msg: 'Welcome to My Resume',
      msg1: '念念不忘 必有回响',
      msg2: '张统治',
      msg3: '一名后端研发工程师',
      msg4: 'tzzhang_021@163.com'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
