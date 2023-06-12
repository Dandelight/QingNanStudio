---
title: Go Public
typora-root-url: Go Public
date: 2023-04-15 18:53:32
tags:
---

## 安卓

### 对应用本身的要求

这部分要求主要在[应用市场审核指南](https://developer.huawei.com/consumer/cn/doc/50104)。主要是一些合规的要求。

### 对应用的开发者的要求

我们以要求比较严格的某市场对【聊天、社区、通讯、婚恋】的[资质审核要求](https://developer.huawei.com/consumer/cn/doc/80301)为例：

1. 《安全评估报告》加盖公章
2. 《安全评估报告》在全国互联网安全服务管理平台的提交结果截图（如有疑问，请参考：[安全评估报告FAQ](https://developer.huawei.com/consumer/cn/doc/50108)）
3. ICP备案或《增值电信业务经营许可证》
4. 《计算机软件著作权证书》、《APP电子版权证书》或《软件著作权认证证书》（三者选一）

#### 安全评估报告

> 转自：<https://zhuanlan.zhihu.com/p/162909864>

（1）安全管理负责人、信息审核人员及安全管理机构设立情况。

公司设有编辑审核部门、运营管理部门、运维管理部门；编辑审核部门将对每日的新闻内容进行审核；运营部门对用户的帖子内容进行审核；运维管理部门负责日志留存记录、内容拦截等工作。

（2）用户真实身份核验及注册信息留存措施。

在用户注册时需要使用手机号注册，我们可以根据手机号对其身份信息进行核验，同时通过日志留存设备检查将该用户身份信息、终端IP地址、终端型号、MAC地址和上网所用账号进行有效绑定，并对应至相应数据表。

（3）对用户账号、操作时间、操作类型、网络源地址和目标地址、网络源端口、客户端硬件特征等日志信息，以及用户发布信息记录的留存措施。

通过日志留存设备记录用户账号、操作时间、操作类型、网络源地址和目标地址、网络源端口、客户端硬件特征等日志信息；同时日志留存设备提供基于时间、应用服务类型、IP地址、端口、账号为查询条件的查询功能；可以通过日志留存设备的查询模块，查找所对应的终端以及其使用人。

（4）对用户账号和通讯群组名称、昵称、简介、备注、标识，信息发布、转发、评论和通讯群组等服务功能中违法有害信息的防范处置和有关记录保存措施。

日志留存设备将对系统管理员日志备份数据的修改及删除操作进行记录，同时记录所有对重要服务器的访问记录；

1.提供黑名单功能，能够设置关键词、链接等；

2.提供拦截通知功能，对特定的网址和帖子进行拦截、邮件告知等；

3.能够记录所使用终端的相关信息和上网行为有关信息。

（5）个人信息保护以及防范违法有害信息传播扩散、社会动员功能失控风险的技术措施。

1.提供黑名单功能，能够设置关键词、链接等；

2.提供拦截通知功能，对特定的网址和帖子进行拦截、邮件告知等；

3.能够记录所使用终端的相关信息和上网行为有关信息

4.对个人信息进行3D加密存储，存储数据库以及服务器，每隔一个月进行密码更换。

（6）建立投诉、举报制度，公布投诉、举报方式等信息，及时受理并处理有关投诉和举报的情况。

提供网址和帖子举报机制，举报后将推送消息给运营人员；运营人员会及时受理并排查举报内容是否合法合规；

（7）建立为监管部门和执法部门依法履职提供技术、数据支持和协助的工作机制的情况。

1. 日志留存设备将提供应用会话记录和系统会话记录180天的记录；
2. 能够根据用户账号、终端设备、IP地址追溯用户真实身份信息；
3. 能够及时通过运营后台对所要拦截的内容进行拦截或者删除操作；

#### ICP 备案

ICP 备案首先你要有个域名，云服务商一般都对自己的云服务提供备案服务，如[阿里云](https://help.aliyun.com/document_detail/61819.htm)。

但增值电信业务经营许可证的备案会比较麻烦，因为代理价格都不便宜。自己申请的方式还不太清楚。

#### 软件著作权证书

这个很简单，去[国家版权局](https://www.ccopyright.com.cn/)申请，或者找个代理帮忙申请即可。