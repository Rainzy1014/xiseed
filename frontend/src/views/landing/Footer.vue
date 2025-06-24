<template>
  <div id="footer" class="container-fuild">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-sm-4 col-md-4">
          <h4>关于我们</h4>
          <p>这是一个基于 Vue 3 和 Vite 构建的企业网站，集成了来自旧版网站模板的设计。旨在提供一个现代化、高性能的用户体验。</p>
        </div>
        <div class="col-xs-12 col-sm-4 col-md-4">
          <h4>联系方式</h4>
          <p><i class="glyphicon glyphicon-phone"></i> 400-000-0000</p>
          <p><i class="glyphicon glyphicon-envelope"></i> admin@xiseed.com</p>
          <p><i class="glyphicon glyphicon-map-marker"></i> 中国北京市海淀区</p>
        </div>
        <div class.col-xs-12 col-sm-4 col-md-4>
          <h4>关注我们</h4>
          <img class="img-responsive" src="../../assets/landing/img/weixin.png" alt="WeChat QR Code">
        </div>
      </div>
      <div class="row footer-bottom">
        <div class="col-xs-12 col-sm-12 col-md-12">
          <p>Copyright &copy; 2024 xiseed. All Rights Reserved.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
/* Scoped styles from the original file */
#footer {
  background: #262626;
  color: #fff;
  padding: 50px 0;
  transition: all ease 0.5s;
}
#footer h4 {
  font-size: 18px;
  margin-bottom: 20px;
}
#footer p {
  line-height: 2;
  color: #ccc;
}
#footer .footer-bottom {
  margin-top: 30px;
  border-top: 1px solid #333;
  padding-top: 20px;
  text-align: center;
}
</style>

