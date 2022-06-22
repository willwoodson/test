# 前端/后端框架相关

# 1 前端

目前没学到框架





# 2 后端

## 2.1 Maven

一款项目管理工具，将项目开发和管理过程抽象成一个项目对象模型(POM)

可以通过在POM文件中添加坐标的方式管理依赖

| 资源信息 |                          |
| -------- | ------------------------ |
| 资源类型 | 项目管理工具             |
| 链接     | http://maven.apache.org/ |
| 备注     |                          |
| 整理人   | 李志                     |
| 日期     | 2022-06-22               |

![image-20220622205508650](https://gallery-1302735062.cos.ap-beijing.myqcloud.com/typora/202206222120834.png)

![image-20220622205708747](https://gallery-1302735062.cos.ap-beijing.myqcloud.com/typora/202206222120835.png)

**相关资源**

1. [依赖坐标查询 mvnrepository](https://mvnrepository.com/)

---

## 2.2 SpringBoot

一款JavaWeb开发框架，约定大于配置，简化了Spring应用的初始搭建及开发过程，并且内嵌tomcat服务器，应用打包后可以直接通过java -jar运行

| 资源信息 |                                        |
| -------- | -------------------------------------- |
| 资源类型 | JavaWeb开发框架                        |
| 链接     | https://spring.io/projects/spring-boot |
| 备注     |                                        |
| 整理人   | 李志                                   |
| 日期     | 2022-06-22                             |

![image-20220622210542243](https://gallery-1302735062.cos.ap-beijing.myqcloud.com/typora/202206222120836.png)

---

## 2.3 MyBatis-Plus

一款DAO层快速开发框架，使得对MySQL数据库的CRUD操作更便捷。

| 资源信息 |                       |
| -------- | --------------------- |
| 资源类型 | DAO层快速开发框架     |
| 链接     | https://baomidou.com/ |
| 备注     |                       |
| 整理人   | 李志                  |
| 日期     | 2022-06-22            |

![image-20220622211049701](https://gallery-1302735062.cos.ap-beijing.myqcloud.com/typora/202206222120837.png)

## 2.4 Spring Cache

一款缓存快速开发框架，实现了基于注解的缓存功能，只需要简单地加一个注解，就能实现缓存功能。

| 资源信息 |                                                              |
| -------- | ------------------------------------------------------------ |
| 资源类型 | 缓存快速开发框架                                             |
| 链接     | [黑马教程瑞吉外卖章节](https://www.bilibili.com/video/BV13a411q753?p=163&vd_source=3f77123f4c4359b83bca0e12557bdf5c) |
| 备注     |                                                              |
| 整理人   | 李志                                                         |
| 日期     | 2022-06-22                                                   |

maven坐标

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-cache</artifactId>
</dependency>

<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-redis</artifactId>
</dependency>
```

