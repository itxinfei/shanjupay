![](Doc/sjzf.png)

<p align="center">
  <a href="https://gitee.com/itxinfei">
    <img alt="code style" src="https://img.shields.io/badge/心飞为你飞-https%3A%2F%2Fgitee.com%2Fitxinfei-green">
  </a> 
  <a href="https://qm.qq.com/cgi-bin/qm/qr?k=9yLlyD1dRBL97xmBKw43zRt0-6xg8ohb&jump_from=webapi">
    <img alt="code style" src="https://img.shields.io/badge/QQ群-863662849-red">
  </a> 
  <a href="http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=f0hLSE9OTkdHTT8ODlEcEBI">
    <img alt="code style" src="https://img.shields.io/badge/mail-747011882@qq.com-red">
  </a> 

  <a href=" ">
    <img alt="code style" src="https://img.shields.io/badge/JDK-1.8%2B-brightgreen">
  </a> 
  <a href=" ">
    <img alt="maven" src="https://img.shields.io/badge/maven-3.6.3%2B-yellowgreen">
  </a>
  <a href=" ">
    <img alt="code style" src="https://img.shields.io/badge/license-Apache-green">
  </a> 
</p>


### 后台演示地址：
http://shanjupay-admin-java.itheima.net/#/operationLogin

### 商家演示地址：
http://shanjupay-main-java.itheima.net/#/login?redirect=%2F

### 项目介绍
- 这里是列表文本闪聚支付是一个提供聚合支付的平台，聚合支付目前主要的做法就是线上聚合收银台(开放API)，线下C2B一码多付、线下B2C商家扫码。平台应以SaaS服务形式提供给各商户订单管理、门店管理、财务数据统计等基础服务，闪聚支付还以支付为入口，通过广告、营销、金融等服务，构建一个移动支付的全生态系统。平台主要包括三个模块，官网&开放平台、商户平台、运营平台。
- 这里是列表文本闪聚支付是以Spring Cloud Alibaba技术栈开发的聚合支付平台，它将目前主流的第三方支付进行整合，形成第三方支付的聚合通道。为线上商户提供聚合收银，为线下商户提供C2B一码多付、B2C商家扫码功能，并以SaaS服务形式提供给各商户订单管理等基础服务。

### 软件架构
软件架构说明
springCloudAibaba、 springBoot、 Dubbo、 Swager、 mybatisPlus、 sharding-jdbc、
log4j2、xxl-job

### 项目功能架构
![输入图片说明](https://images.gitee.com/uploads/images/2020/0706/152942_5b4c4381_800553.png "项目功能架构.png")

### 数据库
- shanjupay_merchant_service 用户中心数据
- shanjupay_transaction 交易服务数据库

### 项目工程
- 商户平台应用(shanjupay-merchant-application) 为前端提供商户管理功能
- 商户服务API(shanjupay-merchant-api) 定义商户服务提供的接口
- 商户服务(shanjupay-merchant-service) 实现商户服务的所有接口
