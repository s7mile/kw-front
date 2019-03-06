<template>
  <footer>
    <button type="button" class="btn_top">
      <i class="fa fa-arrow-up"></i>
      <span class="screen_out">Top</span>
    </button>
    <ul>
      <li>
        <a href="https://bit.ly/2ToXEzu" title="광운대학교 공식 사이트" target="_blank">
          <i class="fa fa-school"></i>
          <span class="screen_out">광운대학교 공식 사이트</span>
        </a>
      </li>
      <li>
        <a href="https://bit.ly/2EPcKVG" title="유캠퍼스" target="_blank">
          <i class="fa fa-user-graduate"></i>
          <span class="screen_out">광운대학교 유캠퍼스</span>
        </a>
      </li>
      <li>
        <a href="https://bit.ly/2SLo7BX" title="총학생회 Facebook" target="_blank">
          <i class="fa fa-facebook"></i>
          <span class="screen_out">광운대학교 총학생회 페이스북</span>
        </a>
      </li>
      <li>
        <a href="http://www.apple.com" title="애플 공식 사이트" target="_blank">
          <i class="fa fa-apple"></i>
          <span class="screen_out">애플 공식 사이트</span>
        </a>
      </li>
    </ul>
    <p class="copyright">
      kwangCl
      <span>©2019</span>
    </p>
  </footer>
</template>

<script>
export default {
  name: "AppFooter"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* --------------------------------------------------
[S] Footer
-------------------------------------------------- */
footer {
  position: relative;
  margin-top: 50px;
  padding: 70px 0 50px 0;
  background: #e64a3a;
}
footer ul {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
footer li a {
  display: block;
  cursor: pointer;
  position: relative;
  width: 55px;
  height: 55px;
  line-height: 57px;
  margin: 0 15px;
  text-align: center;
  background: rgba(0, 0, 0, 0.2);
  color: #fff;
  font-size: 18pt;
  transition: all 0.3s;
}
footer li a:hover,
footer li a:focus {
  background: rgba(0, 0, 0, 0.4);
}
footer .btn_top {
  z-index: 1;
  position: absolute;
  left: 0;
  right: 0;
  top: -25px;
  width: 47px;
  height: 50px;
  line-height: 40px;
  margin: 0 auto;
  font-size: 30px;
  background: #f19687;
  border: 0;
  color: #fff;
}
footer .copyright {
  margin-top: 35px;
  color: #fff;
  text-align: center;
  font-size: 10pt;
}
footer .copyright span {
  color: #ffcae0;
}
/* [E] footer */
</style>
