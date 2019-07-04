<template>
  <div class="hello">
    <h1 class="heading-message">{{ msg }}</h1>
    <section class="common">
      <h2 class="section-title">공통</h2>
      <table class="tbl-common">
        <colgroup>
          <col style="width:18%">
        </colgroup>
        <thead>
          <td>서비스 영역</td>
          <td>{{ mess }}</td>
          <td>Depth 2</td>
          <td>Depth 3</td>
          <td>Depth 4</td>
          <td>Depth 5</td>
          <td>Depth 6</td>
          <td>화면 명</td>
          <td>화면 구분</td>
          <td>회원정보 노출</td>
          <td>네이티브</td>
          <td>기획 담당자</td>
          <td>개발 담당자</td>
        </thead>
        <tbody>
          <tr>
            <th rawspan="3">공통</th>
            <td class="depth1" rawspan="3">오류 페이지</td>
            <td>시스템 점검</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>시스템 점검</td>
            <td>Page</td>
            <td></td>
            <td></td>
            <td>박지유</td>
            <td></td>
          </tr>
          <tr>
            <th></th>
            <td></td>
            <td>네트워크 오류</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>네트워크 오류</td>
            <td>Page</td>
            <td></td>
            <td></td>
            <td>박지유</td>
            <td></td>
          </tr>
          <tr>
            <th></th>
            <td></td>
            <td>페이지 오류</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>페이지 오류</td>
            <td>Page</td>
            <td></td>
            <td></td>
            <td>박지유</td>
            <td></td>
          </tr>
          <tr>
            <th></th>
            <td class="depth1" rawspan="3">로딩 화면</td>
            <td>전체 페이지 로딩</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>전체 페이지 로딩</td>
            <td>Page</td>
            <td></td>
            <td>0</td>
            <td>박지유</td>
            <td></td>
          </tr>
          <tr>
            <th></th>
            <td></td>
            <td>쓸어내림 로딩</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>쓸어내림 로딩</td>
            <td>Page</td>
            <td></td>
            <td>0</td>
            <td>박지유</td>
            <td></td>
          </tr>
          <tr>
            <th></th>
            <td></td>
            <td>계열사 이동형 로딩</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>계열사 이동형 로딩</td>
            <td>Page</td>
            <td></td>
            <td>0</td>
            <td>박지유</td>
            <td></td>
          </tr>

        </tbody>
      </table>
    </section>

    <!-- //table common -->
    <section class="common">
      <h2 class="section-title">메인 (롯데 ON)</h2>
      <table class="tbl-common">
        <colgroup>
          <col style="width:18%">
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
          <td>기획 담당자</td>
          <td>개발 담당자</td>
        </thead>
        <tbody>
          <tr>
            <th>메인 (롯데 ON)</th>
            <td>오류 페이지</td>
            <td>시스템 점검</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>시스템 점검</td>
            <td>Page</td>
            <td></td>
            <td></td>
            <td>박지유</td>
            <td>박화주</td>
          </tr>
        </tbody>
      </table>
    </section>
    <!-- //table common -->
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
.hello{
  max-width: 1920px;
  margin: 0 auto;
}
.heading-message{
  font-size: 24px;
}
.section-title{
  // text-align: left;
  padding-top: 40px;
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
section{
  margin-top: 50px;
}

.tbl-common{
  text-align: left;
  padding: 50px 0;
  margin: 0 auto;
  // border-bottom:  1px solid #ccc;
  thead{
    background-color: #ccc;
    td{
      padding: 10px 20px;
    }
  }
  tbody{
    th{
      padding: 10px 20px;
    }
    td{
      padding: 10px 20px;
    }
    .depth1{
      font-weight: bold;
    }
  }
}
ul{
  li{border:1px solid red;
  }
}
</style>
