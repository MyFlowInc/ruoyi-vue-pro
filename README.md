Downloads Downloads

严肃声明：现在、未来都不会有商业版本，所有代码全部开源!！

「我喜欢写代码，乐此不疲」
「我喜欢做开源，以此为乐」

我 🐶 在上海艰苦奋斗，早中晚在 top3 大厂认真搬砖，夜里为开源做贡献。

如果这个项目让你有所收获，记得 Star 关注哦，这对我是非常不错的鼓励与支持。

🐶 新手必读
演示地址【Vue3 + element-plus】：http://dashboard-vue3.yudao.iocoder.cn
演示地址【Vue3 + vben(ant-design-vue)】：http://dashboard-vben.yudao.iocoder.cn
演示地址【Vue2 + element-ui】：http://dashboard.yudao.iocoder.cn
启动文档：https://doc.iocoder.cn/quick-start/
视频教程：https://doc.iocoder.cn/video/
🐰 版本说明
版本	JDK 8 + Spring Boot 2.7	JDK 17/21 + Spring Boot 3.2
【完整版】ruoyi-vue-pro	master 分支	master-jdk17 分支
【精简版】yudao-boot-mini	master 分支	master-jdk17 分支
【完整版】：包括系统功能、基础设施、会员中心、数据报表、工作流程、商城系统、微信公众号、CRM、ERP 等功能
【精简版】：只包括系统功能、基础设施功能，不包括会员中心、数据报表、工作流程、商城系统、微信公众号、CRM、ERP 等功能
可参考 《迁移文档》 ，只需要 5-10 分钟，即可将【完整版】按需迁移到【精简版】

🐯 平台简介
芋道，以开发者为中心，打造中国第一流的快速开发平台，全部开源，个人与企业可 100% 免费使用。

有任何问题，或者想要的功能，可以在 Issues 中提给艿艿。

😜 给项目点点 Star 吧，这对我们真的很重要！

架构图

Java 后端：master 分支为 JDK 8 + Spring Boot 2.7，master-jdk17 分支为 JDK 17/21 + Spring Boot 3.2
管理后台的电脑端：Vue3 提供 element-plus、vben(ant-design-vue) 两个版本，Vue2 提供 element-ui 版本
管理后台的移动端：采用 uni-app 方案，一份代码多终端适配，同时支持 APP、小程序、H5！
后端采用 Spring Boot 多模块架构、MySQL + MyBatis Plus、Redis + Redisson
数据库可使用 MySQL、Oracle、PostgreSQL、SQL Server、MariaDB、国产达梦 DM、TiDB 等
消息队列可使用 Event、Redis、RabbitMQ、Kafka、RocketMQ 等
权限认证使用 Spring Security & Token & Redis，支持多终端、多种用户的认证系统，支持 SSO 单点登录
支持加载动态权限菜单，按钮级别权限控制，Redis 缓存提升性能
支持 SaaS 多租户，可自定义每个租户的权限，提供透明化的多租户底层封装
工作流使用 Flowable，支持动态表单、在线设计流程、会签 / 或签、多种任务分配方式
高效率开发，使用代码生成器可以一键生成 Java、Vue 前后端代码、SQL 脚本、接口文档，支持单表、树表、主子表
实时通信，采用 Spring WebSocket 实现，内置 Token 身份校验，支持 WebSocket 集群
集成微信小程序、微信公众号、企业微信、钉钉等三方登陆，集成支付宝、微信等支付与退款
集成阿里云、腾讯云等短信渠道，集成 MinIO、阿里云、腾讯云、七牛云等云存储服务
集成报表设计器、大屏设计器，通过拖拽即可生成酷炫的报表与大屏
🐳 项目关系
架构演进

三个项目的功能对比，可见社区共同整理的 国产开源项目对比 表格。

后端项目
项目	Star	简介
ruoyi-vue-pro	Gitee star GitHub stars	基于 Spring Boot 多模块架构
yudao-cloud	Gitee star GitHub stars	基于 Spring Cloud 微服务架构
Spring-Boot-Labs	Gitee star GitHub stars	系统学习 Spring Boot & Cloud 专栏
前端项目
项目	Star	简介
yudao-ui-admin-vue3	Gitee star GitHub stars	基于 Vue3 + element-plus 实现的管理后台
yudao-ui-admin-vben	Gitee star GitHub stars	基于 Vue3 + vben(ant-design-vue) 实现的管理后台
yudao-mall-uniapp	Gitee star GitHub stars	基于 uni-app 实现的商城小程序
yudao-ui-admin-vue2	Gitee star GitHub stars	基于 Vue2 + element-ui 实现的管理后台
yudao-ui-admin-uniapp	Gitee star GitHub stars	基于 Vue2 + element-ui 实现的管理后台
yudao-ui-go-view	Gitee star GitHub stars	基于 Vue3 + naive-ui 实现的大屏报表
😎 开源协议
为什么推荐使用本项目？

① 本项目采用比 Apache 2.0 更宽松的 MIT License 开源协议，个人与企业可 100% 免费使用，不用保留类作者、Copyright 信息。

② 代码全部开源，不会像其他项目一样，只开源部分代码，让你无法了解整个项目的架构设计。国产开源项目对比

开源项目对比

③ 代码整洁、架构整洁，遵循《阿里巴巴 Java 开发手册》规范，代码注释详细，113770 行 Java 代码，42462 行代码注释。

🤝 项目外包
我们也是接外包滴，如果你有项目想要外包，可以微信联系【Aix9975】。

团队包含专业的项目经理、架构师、前端工程师、后端工程师、测试工程师、运维工程师，可以提供全流程的外包服务。

项目可以是商城、SCRM 系统、OA 系统、物流系统、ERP 系统、CMS 系统、HIS 系统、支付系统、IM 聊天、微信公众号、微信小程序等等。

🐼 内置功能
系统内置多种多种业务功能，可以用于快速你的业务系统：

功能分层

通用模块（必选）：系统功能、基础设施
通用模块（可选）：工作流程、支付系统、数据报表、会员中心
业务系统（按需）：ERP 系统、CRM 系统、商城系统、微信公众号、AI 大模型
友情提示：本项目基于 RuoYi-Vue 修改，重构优化后端的代码，美化前端的界面。

额外新增的功能，我们使用 🚀 标记。
重新实现的功能，我们使用 ⭐️ 标记。
🙂 所有功能，都通过 单元测试 保证高质量。

系统功能
功能	描述
用户管理	用户是系统操作者，该功能主要完成系统用户配置
⭐️	在线用户	当前系统中活跃用户状态监控，支持手动踢下线
角色管理	角色菜单权限分配、设置角色按机构进行数据范围权限划分
菜单管理	配置系统菜单、操作权限、按钮权限标识等，本地缓存提供性能
部门管理	配置系统组织机构（公司、部门、小组），树结构展现支持数据权限
岗位管理	配置系统用户所属担任职务
🚀	租户管理	配置系统租户，支持 SaaS 场景下的多租户功能
🚀	租户套餐	配置租户套餐，自定每个租户的菜单、操作、按钮的权限
字典管理	对系统中经常使用的一些较为固定的数据进行维护
🚀	短信管理	短信渠道、短息模板、短信日志，对接阿里云、腾讯云等主流短信平台
🚀	邮件管理	邮箱账号、邮件模版、邮件发送日志，支持所有邮件平台
🚀	站内信	系统内的消息通知，提供站内信模版、站内信消息
🚀	操作日志	系统正常操作日志记录和查询，集成 Swagger 生成日志内容
⭐️	登录日志	系统登录日志记录查询，包含登录异常
🚀	错误码管理	系统所有错误码的管理，可在线修改错误提示，无需重启服务
通知公告	系统通知公告信息发布维护
🚀	敏感词	配置系统敏感词，支持标签分组
🚀	应用管理	管理 SSO 单点登录的应用，支持多种 OAuth2 授权方式
🚀	地区管理	展示省份、城市、区镇等城市信息，支持 IP 对应城市
功能图

工作流程
功能	描述
🚀	流程模型	配置工作流的流程模型，支持文件导入与在线设计流程图，提供 7 种任务分配规则
🚀	流程表单	拖动表单元素生成相应的工作流表单，覆盖 Element UI 所有的表单组件
🚀	用户分组	自定义用户分组，可用于工作流的审批分组
🚀	我的流程	查看我发起的工作流程，支持新建、取消流程等操作，高亮流程图、审批时间线
🚀	待办任务	查看自己【未】审批的工作任务，支持通过、不通过、转发、委派、退回等操作
🚀	已办任务	查看自己【已】审批的工作任务，未来会支持回退操作
🚀	OA 请假	作为业务自定义接入工作流的使用示例，只需创建请求对应的工作流程，即可进行审批
功能图

支付系统
功能	描述
🚀	应用信息	配置商户的应用信息，对接支付宝、微信等多个支付渠道
🚀	支付订单	查看用户发起的支付宝、微信等的【支付】订单
🚀	退款订单	查看用户发起的支付宝、微信等的【退款】订单
🚀	回调通知	查看支付回调业务的【支付】【退款】的通知结果
🚀	接入示例	提供接入支付系统的【支付】【退款】的功能实战
基础设施
功能	描述
🚀	代码生成	前后端代码的生成（Java、Vue、SQL、单元测试），支持 CRUD 下载
🚀	系统接口	基于 Swagger 自动生成相关的 RESTful API 接口文档
🚀	数据库文档	基于 Screw 自动生成数据库文档，支持导出 Word、HTML、MD 格式
表单构建	拖动表单元素生成相应的 HTML 代码，支持导出 JSON、Vue 文件
🚀	配置管理	对系统动态配置常用参数，支持 SpringBoot 加载
⭐️	定时任务	在线（添加、修改、删除)任务调度包含执行结果日志
🚀	文件服务	支持将文件存储到 S3（MinIO、阿里云、腾讯云、七牛云）、本地、FTP、数据库等
🚀	WebSocket	提供 WebSocket 接入示例，支持一对一、一对多发送方式
🚀	API 日志	包括 RESTful API 访问日志、异常日志两部分，方便排查 API 相关的问题
MySQL 监控	监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈
Redis 监控	监控 Redis 数据库的使用情况，使用的 Redis Key 管理
🚀	消息队列	基于 Redis 实现消息队列，Stream 提供集群消费，Pub/Sub 提供广播消费
🚀	Java 监控	基于 Spring Boot Admin 实现 Java 应用的监控
🚀	链路追踪	接入 SkyWalking 组件，实现链路追踪
🚀	日志中心	接入 SkyWalking 组件，实现日志中心
🚀	服务保障	基于 Redis 实现分布式锁、幂等、限流功能，满足高并发场景
🚀	日志服务	轻量级日志中心，查看远程服务器的日志
🚀	单元测试	基于 JUnit + Mockito 实现单元测试，保证功能的正确性、代码的质量等
功能图

数据报表
功能	描述
🚀	报表设计器	支持数据报表、图形报表、打印设计等
🚀	大屏设计器	拖拽生成数据大屏，内置几十种图表组件
微信公众号
功能	描述
🚀	账号管理	配置接入的微信公众号，可支持多个公众号
🚀	数据统计	统计公众号的用户增减、累计用户、消息概况、接口分析等数据
🚀	粉丝管理	查看已关注、取关的粉丝列表，可对粉丝进行同步、打标签等操作
🚀	消息管理	查看粉丝发送的消息列表，可主动回复粉丝消息
🚀	自动回复	自动回复粉丝发送的消息，支持关注回复、消息回复、关键字回复
🚀	标签管理	对公众号的标签进行创建、查询、修改、删除等操作
🚀	菜单管理	自定义公众号的菜单，也可以从公众号同步菜单
🚀	素材管理	管理公众号的图片、语音、视频等素材，支持在线播放语音、视频
🚀	图文草稿箱	新增常用的图文素材到草稿箱，可发布到公众号
🚀	图文发表记录	查看已发布成功的图文素材，支持删除操作
商城系统
功能图

功能图

演示地址：https://doc.iocoder.cn/mall-preview/

会员中心
功能	描述
🚀	会员管理	会员是 C 端的消费者，该功能用于会员的搜索与管理
🚀	会员标签	对会员的标签进行创建、查询、修改、删除等操作
🚀	会员等级	对会员的等级、成长值进行管理，可用于订单折扣等会员权益
🚀	会员分组	对会员进行分组，用于用户画像、内容推送等运营手段
🚀	积分签到	回馈给签到、消费等行为的积分，会员可订单抵现、积分兑换等途径消耗
ERP 系统
功能图

演示地址：https://doc.iocoder.cn/erp-preview/

CRM 系统
功能图

演示地址：https://doc.iocoder.cn/crm-preview/

AI 大模型
功能图

演示地址：https://doc.iocoder.cn/ai-preview/

🐨 技术栈
模块
项目	说明
yudao-dependencies	Maven 依赖版本管理
yudao-framework	Java 框架拓展
yudao-server	管理后台 + 用户 APP 的服务端
yudao-module-system	系统功能的 Module 模块
yudao-module-member	会员中心的 Module 模块
yudao-module-infra	基础设施的 Module 模块
yudao-module-bpm	工作流程的 Module 模块
yudao-module-pay	支付系统的 Module 模块
yudao-module-mall	商城系统的 Module 模块
yudao-module-erp	ERP 系统的 Module 模块
yudao-module-crm	CRM 系统的 Module 模块
yudao-module-ai	AI 大模型的 Module 模块
yudao-module-mp	微信公众号的 Module 模块
yudao-module-report	大屏报表 Module 模块
框架
框架	说明	版本	学习指南
Spring Boot	应用开发框架	2.7.18	文档
MySQL	数据库服务器	5.7 / 8.0+
Druid	JDBC 连接池、监控组件	1.2.19	文档
MyBatis Plus	MyBatis 增强工具包	3.5.3.2	文档
Dynamic Datasource	动态数据源	3.6.1	文档
Redis	key-value 数据库	5.0 / 6.0 /7.0
Redisson	Redis 客户端	3.18.0	文档
Spring MVC	MVC 框架	5.3.24	文档
Spring Security	Spring 安全框架	5.7.11	文档
Hibernate Validator	参数校验组件	6.2.5	文档
Flowable	工作流引擎	6.8.0	文档
Quartz	任务调度组件	2.3.2	文档
Springdoc	Swagger 文档	1.6.15	文档
SkyWalking	分布式应用追踪系统	8.12.0	文档
Spring Boot Admin	Spring Boot 监控平台	2.7.10	文档
Jackson	JSON 工具库	2.13.3
MapStruct	Java Bean 转换	1.5.5.Final	文档
Lombok	消除冗长的 Java 代码	1.18.30	文档
JUnit	Java 单元测试框架	5.8.2	-
Mockito	Java Mock 框架	4.8.0	-
🐷 演示图
系统功能
模块	biu	biu	biu
登录 & 首页	登录	首页	个人中心
用户 & 应用	用户管理	令牌管理	应用管理
租户 & 套餐	租户管理	租户套餐	-
部门 & 岗位	部门管理	岗位管理	-
菜单 & 角色	菜单管理	角色管理	-
审计日志	操作日志	登录日志	-
短信	短信渠道	短信模板	短信日志
字典 & 敏感词	字典类型	字典数据	敏感词
错误码 & 通知	错误码管理	通知公告	-
工作流程
模块	biu	biu	biu
流程模型	流程模型-列表	流程模型-设计	流程模型-定义
表单 & 分组	流程表单	用户分组	-
我的流程	我的流程-列表	我的流程-发起	我的流程-详情
待办 & 已办	任务列表-审批	任务列表-待办	任务列表-已办
OA 请假	OA请假-列表	OA请假-发起	OA请假-详情
基础设施
模块	biu	biu	biu
代码生成	代码生成	生成效果	-
文档	系统接口	数据库文档	-
文件 & 配置	文件配置	文件管理	配置管理
定时任务	定时任务	任务日志	-
API 日志	访问日志	错误日志	-
MySQL & Redis	MySQL	Redis	-
监控平台	Java监控	链路追踪	日志中心
支付系统
模块	biu	biu	biu
商家 & 应用	商户信息	应用信息-列表	应用信息-编辑
支付 & 退款	支付订单	退款订单	---
数据报表
模块	biu	biu	biu
报表设计器	数据报表	图形报表	报表设计器-打印设计
大屏设计器	大屏列表	大屏预览	大屏编辑
移动端（管理后台）
biu	biu	biu



目前已经实现登录、我的、工作台、编辑资料、头像修改、密码修改、常见问题、关于我们等基础功能。
