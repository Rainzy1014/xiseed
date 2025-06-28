<template>
  <div id="ContactUs">
    <div class="banner container-fuild text-center">联系我们</div>
    <div class="container">
      <div class="container-fuild ContactUs-container">
        <div class="row">
          <div class="col-xs-12 col-sm-12 col-md-6">
            <form class="form-horizontal" role="form">
              <div class="form-group">
                <label for="name" class="col-sm-2 control-label">姓名</label>
                <div class="col-sm-10 col-xs-12">
                  <input type="text" class="form-control" id="name" placeholder="请输入名字">
                </div>
              </div>
              <div class="form-group">
                <label for="email" class="col-sm-2 control-label">邮箱</label>
                <div class="col-sm-10">
                  <input type="text" class="form-control" id="email" placeholder="请输入邮箱">
                </div>
              </div>
              <div class="form-group">
                <label for="tel" class="col-sm-2 control-label">电话</label>
                <div class="col-sm-10">
                  <input type="text" class="form-control" id="tel" placeholder="请输入电话">
                </div>
              </div>
              <div class="form-group">
                <label for="content" class="col-sm-2 control-label">内容</label>
                <div class="col-sm-10">
                  <textarea class="form-control" id="content" rows="8" placeholder="请输入内容"></textarea>
                </div>
              </div>
              <div class="form-group">
                <div class="col-sm-offset-2 col-sm-10">
                  <button type="submit" class="btn btn-default btn-block">提交</button>
                </div>
              </div>
            </form>
          </div>
          <div class="col-xs-12 col-sm-12 col-md-6">
            <div class="contact-info wow zoomIn">
              <h3>联系方式</h3>
              <div class="info-item">
                <i class="glyphicon glyphicon-phone"></i>
                <span>电话：400-000-0000</span>
              </div>
              <div class="info-item">
                <i class="glyphicon glyphicon-envelope"></i>
                <span>邮箱：admin@xiseed.com</span>
              </div>
              <div class="info-item">
                <i class="glyphicon glyphicon-map-marker"></i>
                <span>地址：中国北京市海淀区</span>
              </div>
              <div class="info-item">
                <i class="glyphicon glyphicon-time"></i>
                <span>工作时间：周一至周五 9:00-18:00</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { WOW } from 'wowjs'
export default {
  name: "ContactUs",
  data() {
    return {};
  },
  mounted() {
    var wow = new WOW();
    wow.init();
  }
};
</script>
<style scoped>
.banner {
  color: #fff;
  font-size: 30px;
  height: 150px;
  line-height: 150px;
  background-image: url("../assets/landing/img/banner_1.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: scroll;
  background-position: center center;
}
.ContactUs-container {
  padding: 80px 0;
  transition: all ease 0.5s;
  box-sizing: border-box;
}
.contact-info {
  padding: 30px;
  background: #f8f9fa;
  border-radius: 8px;
  height: 365px;
}
.contact-info h3 {
  margin-bottom: 30px;
  color: #333;
  text-align: center;
}
.info-item {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}
.info-item i {
  margin-right: 15px;
  color: #007bff;
  font-size: 18px;
  width: 20px;
}
.info-item span {
  color: #666;
  font-size: 16px;
}
.row {
  margin-right: 0;
  margin-left: 0;
}
@media screen and (max-width: 997px) {
  .ContactUs-container {
    padding: 20px 0;
  }
  .contact-info {
    margin-top: 30px;
    height: auto;
  }
}
</style>

