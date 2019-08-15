## marry_server - 服务端 spring boot + mybatis重构版本

### 项目介绍 
项目为重构marry-server项目。将开发架构改为了spring boot + mybatis开发模式。
原作者项目连接：https://github.com/pengMaster/marry
##### 20190815更新
 - 增加了图片上传功能，对于上传图片的权限控制需要后续优化
##### 2019-08-05 更新记录
 - 增加了查询地图信息的接口。地图导航功能完成

##### 2019-08-02 更新记录
 - 更改了项目编译方式，现在在打包可直接执行mvn clean package命令，无需注入dev配置了，运行则不再需要预先编译
 - 彻底重构了后端代码，之前的代码基本删除了。
 - 小程序改为了单用户模式，关闭了原版注册后可定制化的功能
 - 接口逻辑改变。从原版的单接口接入改为了多接口API
 - 数据库应用了新的表结构，并且sql文件添加到了项目中。在script文件夹中
 - 这次重构优化完成了小程序内部的基本逻辑，单并不彻底，并没有将分层思想贯彻到底。日后会持续优化
 - 本次重构有一个遗留项：本次没有对地图导航功能进行开发，因为删除了之前的逻辑所以目前不再支持地图导航功能。
 - 关于地图导航功能的开发，放到了下一次更新中。这个内容不会永久删除
 - 与现在服务对应的前端代码地址：https://github.com/HowToRun/wxdemo.git
 - 同步更新了README的内容
 
#### 之后可能的重构方向
代码性能优化
代码可读性优化
数据库表结构优化

#### 项目说明
 - 项目架构：spring boot 1.5.4.RELEASE + mybatis 1.3.2
 - 环境：jdk1.8.0_121
 - 项目中引用的网络资源若有侵权，请通知及时删除。该小程序为个人开发，一切解释权归作者所有，图片禁止传播。
- 功能简介：
    - 新郎新娘图片展示
    - 婚礼现场导航
    - 点赞祝福，分享好友
    - 身份切换，制作属于自己的请柬


  
#### 个人说明

 - 目前是一名刚毕业的初级码农，代码以及逻辑方面还有很多不足之处，各位大佬，请多多指教。
 - QQ群：830556582
 - QQ邮箱：951319774@qq.com



#### 参与贡献
 建议使用gitFlow分支模型命名
   - feature/branchName
   - bugfix/branchName
   - release/branchName
   - hotfix/branchName




