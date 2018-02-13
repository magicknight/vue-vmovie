### 项目介绍

   1. 此项目基于Vue+Webpack+Gulp-ssh,主要使用webpack构建项目,gulp-ssh用于自动发布文件包到服务器。
   2. 服务器使用的阿里云的centos服务器,后台服务调用的是V电影App的后台服务,使用nginx的反向代理来解决页面跨域问题
   3. 目前只开通了视频查询和观看功能,我怀疑V电影服务其实通过的user-agent来判断终端的,如果不是app的user-agent就不会将推荐视频和评论列表返回给我。
   4. 【因为是调用别人的服务用于学习和自己使用，因为V电影的h5页面太不完善了,本人重度依赖微信,所以不太想使用APP，所以自己开发了一个简易的H5站点
   5. 为了防止被指侵权,我在我的站点首页和视频详情页均有配置官方APP的下载banner链接,点击图片即可下载官方APP

### 指令介绍

* 安装依赖包：npm install 
* 本地运行: npm run start
* 部署到服务器: npm run d_prd(因为个人项目,没有测试环境,我也只内置了dev和prd两个环境)
* /buld/deploy.conf.prd 文件的ssh里面配置服务器的ip地址和账号密码,如果有多台服务器可以在里面配置多个

### 有问题反馈

  在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流。

* email: zc_smile@outlook.com
* 博客园: [@我有一颗四叶草](http://www.cnblogs.com/FourLeafCloverZc/)


### 商业合作

  本人目前就职于成都某海淘公司,业余时间可接前端项目,也可以去公司进行前端项目指导,或者帮忙定制前端框架。
  
