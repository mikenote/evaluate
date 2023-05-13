
---

# 前言
`【毕业设计】大学生综测管理系统`

- 🥇**个人主页**：[@MIKE笔记](https://blog.csdn.net/m0_51607907?spm=1000.2115.3001.5343)
- 🥈**文章专栏**：[毕业设计源码合集](https://blog.csdn.net/m0_51607907/category_11901075.html)
- ⛄**联系博主：**    wx：`mikenote`
---
# 毕设目录
|项目名  | 地址 |
|:----------|--|
| 1、基于springboot的`大学生综合素质测评管理系统` | [http://t.csdn.cn/smVjL](http://t.csdn.cn/smVjL) |
| 2、基于springboot + vue`微信小程序文创平台商城` | [http://t.csdn.cn/rUQDg](http://t.csdn.cn/rUQDg) |
| 3、基于springboot+vue—`酒店客房管理系统` | [http://t.csdn.cn/4zBzE](http://t.csdn.cn/4zBzE) |
| 4、基于springboot+vue前后端分离-`考试报名管理系统` | [http://t.csdn.cn/TpHxC](http://t.csdn.cn/TpHxC) |
| 5、待补充-------------------------------------- | [http://t.csdn.cn/smVjL](http://t.csdn.cn/smVjL) |
| 6、待补充--------------------------------------| [http://t.csdn.cn/smVjL](http://t.csdn.cn/smVjL) |
# 1️⃣介绍
大学生综合素质测评系统是在web的基础上开发运行起来，使用MYSQL作为系统的数据库，采用了Ｂ/S模式，主要具有以下的几大功能模块：系统用户管理，管理员信息录入及删除模块，用户信息的管理，学院班级等信息，学生课程信息，测评管理，反馈信息管理，以及系统公告等模块模块，其中学生个人信息输入模块、课程成绩管理，测评管理、功能模块是本系统的重点设计模块。
## 特色功能
- 提前配置加分规则，减少繁琐的计分过程，提高科学性和效率
- 支持文件导入导出，覆盖常见功能
- 灵活构建评价指标体系，适合不同高校不同专业的培养目标
- [【大学生综合测评管理系统-1.0版本】视频演示 ▶️](https://www.bilibili.com/video/BV1YX4y127ep/?share_source=copy_web&vd_source=d764770ff4322f1a1111e85d452245c6)
# 2️⃣在线体验📈
## 1.0版本

网站：[http://8.130.36.187:2022](http://8.130.36.187:2022)
- 超级管理员：super/123456
- 管理员：admin/123456
- 学生：2022001/123456
- 辅导员：T0001/123456
- **`￥350`**——📲wx/qq：mikenote

>⚠️1.0版本除非重大bug，现有基础上不在更新。
## 2.0版本

网站：[http://8.130.36.187:2023](http://8.130.36.187:2023)
- 超级管理员：super/123456
- 辅导员：T2023/123456
- 管理员：admin/123456
- 学生：user/123456
- **`￥550`**——📲wx/qq：mikenote


>✅2.0版本更新说明：
- 1️⃣新增测评管理模块-德育成绩；
- 2️⃣更改综合成绩计算逻辑为；
**50%智育 + 30%德育 + 15%加分项 + 5%体育**；
- 3️⃣新增图片上传功能；
- 4️⃣新增（证明材料）审核功能——学生上传材料，辅导员审核
- 5️⃣新增GPA计算功能：根据学分、绩点计算出GPA / 平均学分绩点-得出课程成绩（智育成绩）
- 6️⃣删除用户注册功能：学校系统一般由管理员添加、仅本校学生可使用；



## 3.0版本
进展及下步开发计划(主要向可视化方面考虑)：
|⚙️功能 |🕗时间  |✅状态  |🪫进度  |
|:----------|--|--|--|
| 🔥课程批量导入功能 |2023.5.1-2023.12.1  |❎  | 30% |
|  🔥学生/课程/加分项等数量统计功能 |2023.5.1-2023.12.1  |❎  | 0% |
|  🔥个人成绩Echarts统计图功能 |2023.5.1-2023.12.1  |❎  | 0% |
| 🔥 班级成绩Echarts统计分布图功能 |2023.5.1-2023.12.1  |❎  | 0% |
|  🔥考虑是否适配手机页面h5(目前适应平板) |2024.1.1-2024.12.1  |❎  | 0% |
|  🔥动态修改综合测评各板块成绩占比 / 基础分|2024.1.1-2024.12.1  |❎  | 0% |
|  🔥根据pc端计算逻辑，开发一款专门计算综合成绩的微信小程序/pc网页/h5页面(主要面向学生个人成绩计算器，不涉及辅导员审核等功能)|2024.1.1-2024.12.1  |❎  | 0% |
`说明：`其他没有提及的功能，有同学想到的请评论区留言。
# 3️⃣综合素质测评表
- 本系统严格按照此测评表编写，包括每一部分的加分，扣分，计算审核逻辑；和真实的大学生每年综合测评一模一样；实用性超级高，作为毕设的不二之选。
- 当然你也可以自己使用，每年综合成绩计算岂不是省事很多，输入学分，绩点，2分钟即可计算出GPA。

![大学生综测表](https://github.com/mikenote/evaluate/assets/84774967/7b9a22cf-8592-470f-a62d-2fec956a941c)






综测成绩计算逻辑—平均学分绩点（GPA）
![GPA](https://github.com/mikenote/evaluate/assets/84774967/513e7a21-9e3e-465c-83a8-a7b1d9c9ec96)


```c

// 50%智育 + 30%德育 + 15%加分项 + 5%体育
Double totalScore = new BigDecimal(totalCourseScore * 0.5 + totalPlusesPoints * 0.15 + totalPhysicalScore * 0.05 + (deyuScore + 60) * 0.3).setScale(2, RoundingMode.HALF_UP).doubleValue();

```

# 4️⃣系统环境
**环境**     | **版本 / 下载**
-------- | -----
系统|   win 10 /win 11
JDK  | [1.8.0_144](https://downloads.mysql.com/archives/community/?spm=wolai.workspace.0.0.57f1767b9cfOd3)
Maven  | [3.6.3](https://maven.apache.org/download.cgi)
JDK  | [1.8.0_144](https://www.oracle.com/java/technologies/downloads/)
IDEA  | [2023](https://www.jetbrains.com.cn/idea/download/download-thanks.html?spm=wolai.workspace.0.0.57f1767b9cfOd3)
Node| [14.16.0 +](https://nodejs.org/zh-cn/download/releases)
npm|  [6.14.11 +](https://nodejs.org/zh-cn/download/releases)
MySQL| [5.6.42 / 5.7.x](https://secure-bigfile-danger.wostatic.cn/static/6S29HSH5fALi7REufaqc1M/jdk-8u151-windows-x64.exe?auth_key=1683710186-eh22BDS7iaSufeg6a3LAE4-0-618454474ab0ef18815b79f9685a4b00&download=jdk-8u151-windows-x64.exe)

`备注：`以上版本为博主电脑配置，可点击进入**官网**下载



# 关于我
`📢源码有偿获取，可联系我`
```c
wx/qq：mikenote
CSDN：https://blog.c1n.cn
码云：https://gitee.com/f_xz
个人博客：https://mikenote.asia
```
# 结语
[🔥项目本地部署教程——springboot项目通用](https://blog.csdn.net/m0_51607907/article/details/130641049)
以上便是本系统基本概览，本 [**专栏**](https://blog.csdn.net/m0_51607907/category_11901075.html)介绍源码均亲测运行可用。
