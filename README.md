#  mall-micro 基于单体应用重构更新中...
#  申明: 个人作品 仅供学习
```
 1.基于go-micro微服务实战 
 2.配套mall-app Android iOSAPP  代码: https://github.com/TorettoLong/mall-app
 3.基于Vue 和springboot 构建的后台管理系统  
   3.1 前端代码: https://github.com/TorettoLong/mall-admin
   3.2 接口代码: https://github.com/TorettoLong/mall-admin-java
 
```

# 运行步骤
```
 1. make build
 2. docker-compose build
 3. docker-compose up

```
# 前端部分页面展示 
```
 功能点:
   登陆: 短信 微信 facebook 
   视频：视频播放
   新闻: 新闻
   发布广告
   上传图片七牛
   支付宝支付
   银联支付....
```
##视频详情
<img src="https://image.showm.xin//test/01.png" width="375px">

<img src="https://image.showm.xin//test/02.png" width="375px">

##广告
<img src="https://image.showm.xin//test/03.png" width="375px">

<img src="https://image.showm.xin//test/04.png" width="375px">

##govendor命令	功能

```
init	初始化 vendor 目录
list	列出所有的依赖包
add	添加包到 vendor 目录，如 govendor add +external 添加所有外部包
add PKG_PATH	添加指定的依赖包到 vendor 目录
update	从 $GOPATH 更新依赖包到 vendor 目录
remove	从 vendor 管理中删除依赖
status	列出所有缺失、过期和修改过的包
fetch	添加或更新包到本地 vendor 目录
sync	本地存在 vendor.json 时候拉去依赖包，匹配所记录的版本
get	类似 go get 目录，拉取依赖包到 vendor 目录

```

##组件
```$xslt
gin web         github.com/gin-gonic/gin
gorm msyql      github.com/jinzhu/gorm
redis           github.com/go-redis/redis
file setting    github.com/BurntSushi/toml
uuid            github.com/HaroldHoo/id_generator
gin pprof       github.com/DeanThompson/ginpprof
auth            gopkg.in/dgrijalva/jwt-go.v3
tail            github.com/hpcloud/tail
logs            github.com/astaxie/beego/logs
kafka           github.com/Shopify/sarama
elasticSearch   github.com/olivere/elastic
json            github.com/json-iterator/go
go-torch        github.com/uber/go-torch
```
