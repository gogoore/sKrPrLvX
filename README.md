## 前言

微信外卖小程序+SSM项目是一个基于Java语言和微信小程序的前后端分离的外卖系统。本项目结合了Spring、SpringMVC、MyBatis等主流框架，旨在为用户提供便捷的外卖服务。以下是本项目的详细介绍。

## 内容介绍

本项目主要包括以下几个模块：用户模块、商家模块、商品模块、订单模块、支付模块等。用户可以通过微信小程序浏览附近商家、查看商品信息、下单购买、在线支付等。商家可以发布商品、处理订单、查看营业额等。系统后台管理员可以管理用户、商家、订单等。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于用户登录的核心代码：

```java
// UserController.java
@RequestMapping(value = "/login", method = RequestMethod.POST)
public String login(String username, String password, Model model) {
    User user = userService.findByUsername(username);
    if (user != null && user.getPassword().equals(password)) {
        model.addAttribute("user", user);
        return "success";
    }
    return "error";
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
