## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

---

# 基于SpringBoot+Vue的校园跑腿系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

CampusErrand 是一款面向高校校园互助跑腿场景的服务平台，支持需求发布、接单广场抢单、履约轨迹、四位核验码结算、钱包预扣与退款、跑腿员认证审核与运营数据大屏，普通学生、校园跑腿员与管理员三类角色协同，适合毕设、课设与学习参考。

## 主要功能模块

- **用户认证模块**：支持普通学生、跑腿员、管理员三类角色登录，JWT 鉴权并按角色跳转服务大厅/工作台/后台
- **需求发单模块**：快递代取、食堂带饭等分类发单，悬赏小费垫付预扣钱包并生成核验码
- **接单履约模块**：接单广场抢单、取件配送状态推进、轨迹记录与四位核验码结单划转
- **跑腿员模块**：认证申请审核、工作台订单处理与收入流水查看
- **资金账户模块**：钱包充值、发单预扣、取消退款、结单赏金划转与流水追溯
- **后台运营模块**：运营数据大屏、订单监管、分类与用户管理、跑腿员审核

## 技术架构

- **后端**：Spring Boot 2.7.18 + MyBatis-Plus 3.5.3 + JWT + Lombok
- **前端**：Vue 3 + Vue Router + Pinia + Element Plus + Vite 5 + ECharts
- **数据库**：MySQL 8.0

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E5%8F%91%E5%B8%83%E8%B7%91%E8%85%BF%E9%9C%80%E6%B1%82.png" alt="发布跑腿需求" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E6%88%91%E7%9A%84%E8%B7%91%E8%85%BF%E9%9C%80%E6%B1%82.png" alt="我的跑腿需求" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E8%B7%91%E8%85%BF%E5%91%98%E5%B7%A5%E4%BD%9C%E5%8F%B0.png" alt="跑腿员工作台" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E8%B7%91%E8%85%BF%E6%8E%A5%E5%8D%95%E5%B9%BF%E5%9C%BA.png" alt="跑腿接单广场" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E8%B7%91%E8%85%BF%E8%AE%A2%E5%8D%95%E7%9B%91%E7%AE%A1.png" alt="跑腿订单监管" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/campuserrand/%E8%BF%90%E8%90%A5%E6%95%B0%E6%8D%AE%E5%A4%A7%E5%B1%8F.png" alt="运营数据大屏" width="600" />

<!-- screenshots-end -->
