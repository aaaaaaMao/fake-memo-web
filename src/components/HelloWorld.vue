<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Download App to memorize vocabulary<br>
      click the
      <a href="https://www.maimemo.com" target="_blank" rel="noopener">Maimemo</a>.
    </p>
    <h3>Installed App</h3>
    <ul>
      <li><a href="https://apps.apple.com/cn/app/id888483369" target="_blank" rel="noopener">iOS</a></li>
      <li><a href="https://cdn.maimemo.com/apk/maimemo_v3.8.41_1607756087.apk" target="_blank" rel="noopener">Android</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://www.maimemo.com/home/voc_test" target="_blank" rel="noopener">词汇量测试</a></li>
      <li><a href="https://www.maimemo.com/shop" target="_blank" rel="noopener">增加上限</a></li>
      <li><a href="https://www.maimemo.com/custom/show/phrase" target="_blank" rel="noopener">我的例句</a></li>
      <li><a href="https://www.maimemo.com/custom/show/note" target="_blank" rel="noopener">我的助记</a></li>
      <li><a href="https://www.maimemo.com/home/login" target="_blank" rel="noopener">登录</a></li>
    </ul>
    <h3>Ecosystem</h3>
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
h3 {
  margin: 40px 0 0;
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
