# eoLinker AMS(API接口管理系统开源版-For Java)

![](http://data.eolinker.com/course/nwXBJxFdc30c033b1e96469d94e1840ec2bc85271b328be)

## 简介

**eoLinker是国内最大的在线API接口管理平台，提供自动生成API文档、API自动化测试、Mock测试、团队协作等功能，旨在解决由于前后端分离导致的开发效率低下问题。**

目前eoLinker为来自全球的超过2万家企业提供快速、专业、稳定的API管理服务。eoLinker是Google谷歌开发者联盟的合作产品与企业，不定期举办线下交流分享活动促进国内API管理领域的发展。

eoLinker专为10人以下的小型团队设计该开源版本，接近线上免费版本的功能，其良好的安装以及使用体验更是为您带来API管理新体验，同时产品会不定时更新，不断满足你的需求。

![](http://data.eolinker.com/course/XvkVdSWf53b2b7c37361531304ea5154e640ac40bd31ebb)

## 特性

1. 免费且开源，eoLinker拥有强大的免费产品，在过去的一年里面eoLinker已迭代超过300个版本，优化近千功能点，同时秉承开源精神，提供国际化的开源产品（支持中文简体、繁体以及英语），为广大的开发、测试以及管理人员提供专业的产品。

2. 同类产品中最强大的API文档管理系统，支持目前HTTP/HTTPS协议以及所有主流请求方式，并且提供了强大的版本管理功能，可以随时随地回滚API信息。同时支持数据库管理、状态码管理、项目文档管理等常用管理功能。

3. API接口测试，支持文件、在线、跨域、自动化测试等功能。同时拥有参数构造器，可以对请求参数进行自动构造，加密、分割、随机字符串等功能一应俱全。配合测试用例可以非常方便地对比请求结果与模型，找出API可能出现的问题。

4. API自动化测试，eoLinker是目前全球唯一一款支持界面与代码双模式的自动化测试工具。在UI界面模式下，你不需要编写任何代码即可创建数据相互关联的API测试用例（比如注册-登录-检查登陆状况-退出登录）；同时你也可以通过编写Javascript代码来构造复杂的自动化测试场景。这些都极大地简化了开发测试人员的API测试工作，每次开发完成只需要一个键即可自动测试所有API并且生成测试报告，帮助了解项目API的健康状况。

5. API Mock测试，提供最强的Mock功能，支持MockJS，支持自动刷新返回结果以及多种返回的结果。同时还支持对API进行请求校验，当参数或值不符合预设的模板时能够及时找出问题所在。

6. 支持文档分享和导出，你可以通过eoLinker在线生成接口文档，也可以导出成为HTML、PDF以及Word等，快速分享或发布API信息。

7. 支持Postman、RAP、RestClint等数据导入，无需重新录入API信息，一键导入即可切换平台。

8. 强大的团队协作功能，你可以通过URL快速邀请成员或者加入某个项目，eoLinker提供了全面的日志追踪以及权限管理功能。

9. 拥有最全面的产品线，eoLinker除了拥有免费开源版本之外，还提供了线上版本、私有云版本、浏览器插件、PC端桌面程序等，可以满足企业所有的API管理需求。

## 图片介绍

![](http://data.eolinker.com/course/UKqa58Lb051cf1085b22bf4d1e24c52022c981dc32166bd)
![](http://data.eolinker.com/course/nNmSD28e4ef5c7339c5449cb4f8c5904be7f025d0d6ae72)
![](http://data.eolinker.com/course/Rgz8DcQ4f21471cb1172573fdb595a1c165148f6bcfdb22)
![](http://data.eolinker.com/course/JPGkitw9d6f38f7fc541d9202850c3dffe82d1e575c2a6c)

## 部署要求

* Java 5.5+
* mysql  5.5+
* Tomcat

## 快速入门

1. [安装指南](http://help.eolinker.com/?target=/md/%E5%BC%80%E6%BA%90%E7%89%88%E6%9C%AC/%E9%83%A8%E7%BD%B2%E6%8C%87%E5%8D%97)

2. [使用指南](http://help.eolinker.com)

3. [视频使用指南](http://blog.eolinker.com/#/course/)

4. 官方交流Q群：

[用户讨论1群(已满，暂停加入)](https://jq.qq.com/?_wv=1027&k=5ieOtY7)

[用户讨论2群(已满，暂停加入)](https://jq.qq.com/?_wv=1027&k=5eVxKs3)

[用户讨论3群(已满，暂停加入)](https://jq.qq.com/?_wv=1027&k=5X2GVFf)

[用户讨论4群(已满，暂停加入)](https://jq.qq.com/?_wv=1027&k=51Kk8Lz)

[用户讨论5群(开放)：707530721](https://jq.qq.com/?_wv=1027&k=5lDoleL)

## 注意事项

1. 3.x版本与2.x版本并不兼容，因此无法直接由2.x升级到3.x，也无法通过覆盖代码的方式进行升级，切勿随意尝试以防数据丢失。
2. 如果需要进行数据的迁移，可以使用eoLinker接口管理系统中的【导出项目】功能：将项目导出为eoLinker专用格式（.export），然后在3.x版本中导入。
3. 为了防止数据丢失，请在执行任何关键操作之前妥善备份数据库。

## 相关链接

> 中文官网：www.eolinker.com

> 开源支持：https://www.eolinker.com/#/os/download

> Github：https://github.com/eolinker

> 码云：https://gitee.com/eoLinker-API-Management

> Coding：https://coding.net/u/eolinker/project

> Blog：http://blog.eolinker.com

> 视频教程：http://blog.eolinker.com/#/course/

## 更新日志


#### V1.0.0(2018/4/13)
Java版本正式发布
