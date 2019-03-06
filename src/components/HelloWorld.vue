<template>
  <div class="wrap">
    <img src="../assets/img/aoc.jpg" alt>
    <ul>
      <li>2019년 3월 15일 이후로 운영자들의 졸업으로 후계자(?)를 찾지 못해 광클의 다른 서비스는 잠정 중단됩니다.</li>
      <li>그래도 AOC만큼은 최대한 끝까지 제공해드리고자 합니다. (정보통신처에서 유캠에 넣어주시면 아주 좋을듯..)</li>
      <li>
        우리대학 학생 및 교직원을 위한 혜택이니 주소가 외부로 노출되지 않도록 주의해 주세요.
        <strong>(졸업생 불가)</strong>
      </li>
      <li>Apple On Campus에 접속할 수 있는 URL은 AOC 정책 상 @kw.ac.kr 이메일로 보내드립니다.</li>
    </ul>

    <form action="method" class="form">
      <input type="text" name="userId" id="userId" placeholder="아이디">
      <span>@kw.ac.kr</span>
      <p class="mt5">
        <input type="submit" value="Apple On Campus 주소 받기">
      </p>
    </form>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  text-align: center;
  height: calc(100vh - 420px);
}
ul {
  max-width: 680px;
  margin: 0 auto;
}
li {
  list-style: circle;
  margin-bottom: 10px;
  text-align: left;
  color: #e64a3a;
}
strong {
  font-weight: bold;
}
.form {
  margin-top: 50px;
}
input[type="text"] {
  font-size: 30px;
}
form span {
  font-size: 30px;
}
form p {
  margin-top: 10px;
}
form input[type="submit"] {
  padding: 8px 20px;
  border-radius: 5px;
  background: none;
  font-size: 20px;
  border: 2px solid #e64a3a;
  color: #e64a3a;
  font-weight: bold;
}
form input[type="submit"]:hover {
  background-color: #e64a3a;
  color: #fff;
}
</style>
