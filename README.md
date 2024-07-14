# 快手开放平台第三方代小程序开发

https://mp.weixin.qq.com/s/MJIHnIOVC2EmthWBwaQ9ZQ

![Image text](https://pic1.zhimg.com/70/v2-c29e462ce5c714b23821baf8c4af823f_1440w.png)

#### 介绍
快手小程序第三方平台开发着力于解决快手生态体系内的小程序管理问题，一套模板，随处部署。能尽可能地减少服务商的开发成本，服务商只用开发一套小程序代码作为模板就可以快速批量的孵化出大量的商家小程序。

第三方平台是第三方服务商帮助小程序开发者进行开发、管理、运营等工作的综合平台。小程序开发者可一键授权给第三方平台，通过第三方平台完成业务。

![Image text](https://pic2.zhimg.com/80/v2-63ff81cc7e52aad9a6ea8bdf35b23435_720w.png)

比如餐饮类、社区团购类的小程序，大部分功能都相同，这时第三方平台只要通过模板开发，得到商家授权后，即可快速根据模板代码给商家快速实例化小程序。无需关心各个商家的小程序资料信息，繁琐操作那些开发配置信息。多个前端只需对应一个服务端后台。时间少，成本低。

模板代开发的优势就是可以代开发/管理商家小程序，若服务商优化了模板小程序中的一个逻辑，则可以调用平台提供的功能构建、提审、上架所有已授权商家小程序。

业务特点：

开发流程：服务商先开发小程序模板的代码，然后通过小程序模板的代码去构建商家小程序的代码。

快速开通：通过服务市场，商家完成订购小程序，通过模板快速构建商家小程序版本。

易于维护：服务商可代商家实现小程序的快速维护更新。

![Image text](https://pic1.zhimg.com/80/v2-7c022ef32d4758c64cc3d0d31de90f14_720w.png)

代商家管理小程序功能主要包括基础信息管理、开发管理、流量管理、权限管理。

基础信息管理

主要功能有商户授权、设置服务器域名、设置业务域名。

开发管理

主要功能有上传代码、提交审核、审核撤回、生成体验二维码、查看版本、发布小程序、版本回退。

运营管理

主要功能有申请短视频挂载能力、申请直播挂载能力、申请发快手能力。

权限管理

主要功能有申请获取手机号能力。

#### 1、商家授权

商家跳转到授权页面，商家确认第三方小程序应用信息，选择要授权的小程序，勾选授权权限集，点击确定即可完成授权。

![Image text](https://pic1.zhimg.com/80/v2-4fa68e6a85d5d7ad112b1838428f3f28_720w.png)

![Image text](https://pic1.zhimg.com/80/v2-5d1c412b76dc5952ef6f24b4216b21a0_720w.png)

![Image text](https://pic2.zhimg.com/80/v2-3eab2298682baf54f586f881fd84a8a1_720w.png)

#### 2、设置服务器域名

为授权小程序修改服务器域名（request、socket、upload、download 域名）。授权给第三方的小程序，其服务器域名只可以为第三方的服务器。服务器域名需要在第三方小程序应用的服务器域名列表内或者是第三方小程序应用服务器域名的子域名。例如第三方登记的服务器域名如为http://kuaishou.com，则可以直接将http://kuaishou.com及其子域名（如http://xxx.kuaishou.com）也配置到授权的小程序中。
 
![Image text](https://pic4.zhimg.com/80/v2-7ea94430e692d041325acf841b08a5d3_720w.png)

支持添加、覆盖、删除、获取操作。

![Image text](https://pic4.zhimg.com/80/v2-e105c48b2c7e8b12f9615abb2a746d63_720w.png)

#### 3、设置业务域名

为授权小程序修改业务域名（webview 域名）。授权给第三方的小程序，其业务域名只可以为第三方的服务器。域名需要在第三方小程序应用的 webview 域名列表内或者是第三方小程序应用 webview 域名的子域名。例如第三方登记的业务域名如为http://kuaishou.com，则可以直接将http://kuaishou.com 及其子域名（如 http://xxx.kuaishou.com）也配置到授权的小程序中。

![Image text](https://pic1.zhimg.com/80/v2-acabb977f93d24b67ca6a19077071d2c_720w.png)

支持添加、覆盖、删除、获取操作。

![Image text](https://pic4.zhimg.com/80/v2-6ef68013b2687aaef62ad2a04128759b_720w.png)

最重要的就是代小程序上传代码、提交审核、撤回审核、发布小程序、版本回退等功能。

#### 4、上传代码

为授权小程序提交代码。提交成功后，授权小程序具有体验版。

![Image text](https://pic4.zhimg.com/80/v2-1bad7ca82cc7dc633c9953e41df5f4bf_720w.png)

![Image text](https://pic3.zhimg.com/80/v2-5e9e7318e2e83d620bcb2d4837b3186e_720w.png)

#### 5、提交审核

为授权小程序提审代码。当上传代码成功后，在这里提交审核，审核成功后，授权小程序具有审核版本。

![Image text](https://pic4.zhimg.com/80/v2-c0bab66219df4f6ad51738826dc676b7_720w.png)

#### 6、审核撤回

为授权小程序撤回版本审核队列的待审版本。如果提交审核版本后发现问题，又不想等待审核被拒，可以使用该功能进行撤回。

![Image text](https://pic2.zhimg.com/80/v2-2037c6f6d53fdc656f4b125c111ffd8d_720w.png)

#### 7、生成体验二维码

为授权小程序获取小程序体验二维码。在审核发布之前可以生成体验二维码进行体验。

![Image text](https://pic4.zhimg.com/80/v2-06acb4296cb020801fa483519363a56f_720w.png)

![Image text](https://pic2.zhimg.com/80/v2-1ecdff496179f9e54ac75182f4b96f61_720w.png)

#### 8、查看版本

为授权小程序获取小程序版本列表信息。包括线上版本、审核版本、开发版本三种版本信息。

![Image text](https://pic2.zhimg.com/80/v2-6cac9ae48a3047e85189cba568394bdd_720w.png)

#### 9、发布小程序

为授权小程序发布代码。审核通过之后，可以将版本发布。发布成功后，授权小程序具有线上版本。

![Image text](https://pic4.zhimg.com/80/v2-96c3a513afdb3e23eaa3faacfb9a9807_720w.png)

#### 10、版本回退

为授权小程序回退代码版本。如果发现小程序上线后有问题，修复时间又比较长，可以先使用该功能将小程序代码包回退到上一个线上版本。

![Image text](https://pic3.zhimg.com/80/v2-41b05c646934671c30455e5321547c6e_720w.png)

#### 11、申请短视频挂载

为授权小程序申请「短视频挂载」能力，查询「短视频挂载」能力申请状态。

![Image text](https://pic2.zhimg.com/80/v2-44d463387af9aa2ffd76b6808f0e3f71_720w.png)

#### 12、申请直播挂载

为授权小程序申请「直播挂载」能力，查询「直播挂载」能力申请状态。

![Image text](https://pic3.zhimg.com/80/v2-8d96f617a16fa10e0caac65489c95cfa_720w.png)

#### 13、申请发快手

为授权小程序申请「发快手」能力，查询「发快手」能力申请状态。

![Image text](https://pic3.zhimg.com/80/v2-8f4dabba4d6a6ddf1695ee495dfbf9e2_720w.png)

#### 14、申请获取手机号

为授权小程序申请「获取手机号」能力，查询「获取手机号」能力申请状态。

![Image text](https://pic4.zhimg.com/80/v2-0d3820b09d1d53257bc52f579a3f84af_720w.png)

这就是快手开放平台第三方代小程序开发，一整套流程。

![Image text](https://pic1.zhimg.com/80/v2-fc64ca6384d51bffb28eb6e100c1185c_720w.png)

山水有相逢，来日皆可期，谢谢阅读，我们再会

我手中的金箍棒，上能通天，下能探海
