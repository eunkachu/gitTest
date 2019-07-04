<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <!-- <h2>Essential Links</h2>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Core Docs
        </a>
      </li>
      <li>
        <a
          href="https://forum.vuejs.org"
          target="_blank"
        >
          Forum
        </a>
      </li>
      <li>
        <a
          href="https://chat.vuejs.org"
          target="_blank"
        >
          Community Chat
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <br>
      <li>
        <a
          href="http://vuejs-templates.github.io/webpack/"
          target="_blank"
        >
          Docs for This Template
        </a>
      </li>
    </ul> -->
    <h2>공통</h2>
    <table class="tbl-common">
      <colgroup>
        <col style="width:30%">
      </colgroup>
      <thead>
        <td>서비스 영역</td>
        <td>Depth 1</td>
        <td>Depth 2</td>
        <td>Depth 3</td>
        <td>Depth 4</td>
        <td>Depth 5</td>
        <td>Depth 6</td>
        <td>화면 명</td>
        <td>화면 구분</td>
        <td>회원정보 노출</td>
        <td>네이티브</td>
        <td>담당자</td>
      </thead>
      <tbody>
        <tr>
          <th>공통</th>
        </tr>
        <tr>
          <th>메인(롯데ON)</th>
        </tr>
        <tr>
          <th>헤더</th>
        </tr>
        <tr>
          <th>액션바</th>
        </tr>
        <tr>
          <th>푸터</th>
        </tr>
        <tr>
          <th>상품상세</th>
        </tr>
      </tbody>
    </table>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
        >
          vue-router
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'LOTTE E-COMMERCE WORKSHEET'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.bi{
  display: none;
}
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

.tbl-common{
  text-align: left;
}
ul{
  li{border:1px solid red;
  }
}
</style>
