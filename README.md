# datacase
现场数据管理平台

## 一、	用户管理
>1.	用户注册；
>2.	用户登陆；
>3.	访客浏览；

## 二、	权限管理
>1.	管理员用户，增删查改；
>2.	普通访客，有限查询；

## 三、	用户设置管理
>1.	报警设置；
>2.	特别关注；

## 四、	用户行为管理
>1.	添加现场系统；
>2.	删除现场系统；
>3.	修改现场系统；
>4.	查询现有系统；

## 五、	现场系统管理
暂无设计；

## 六、	现场系统管数据管理
>1.	实时数据显示，web页面列出实时状态现场状态；
>2.	实时报警，web页面列出实时报警数据；
>3.	报警信息推送，微信、邮件、短信等；

## 七、	历史数据管理
>1.	现场系统历史数据查询；
>2.	现场系统历史数据统计；

---

目前初步设想是用php实现一个样板网站，前端用boostrap框架，数据采集部分用C++写一个服务器，把现场通过socket传回来的数据解包存入数据库。

