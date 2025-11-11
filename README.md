# 前言

基于微信小程序的药店管理系统是一个结合了SSM框架的现代化药店管理解决方案。它能够帮助药店实现药品库存管理、销售管理、员工管理等功能，提高药店的运营效率。本项目旨在为小型药店提供一套易用、高效、稳定的管理系统。

# 内容介绍

本项目分为前后端两个部分，前端基于微信小程序，为用户提供简洁明了的操作界面；后端采用SSM框架，保障了系统的高效性和稳定性。系统主要功能包括：

1. 药品信息管理：药品分类、药品详情、库存管理。
2. 销售管理：订单管理、销售记录、退货记录。
3. 员工管理：员工信息、权限分配、操作日志。
4. 统计分析：药品销售统计、库存预警、销售趋势图。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，MyBatis，微信小程序

## 前端技术：JS、Vue、CSS3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven：apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下是一段药品信息查询的MyBatis核心代码：

```java
<!-- Mapper.xml -->
<select id="selectDrugInfo" parameterType="Map" resultType="Drug">
    SELECT
        id,
        name,
        price,
        inventory
    FROM
        drug
    WHERE
        name LIKE CONCAT('%', #{name}, '%')
    LIMIT #{start}, #{pageSize}
</select>
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/330460/15/13069/86566/68c62d6aF06aced89/d7ae145abc6a97b2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/333229/31/13136/33806/68c62d42Fb9483f8a/afd52e07fc784dfb.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/335003/30/13095/19285/68c62d43F0fe00fb8/efeb4e5944bbe49e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/332304/17/13083/20871/68c62d43F79779c8b/c279b9550774cb7f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/337174/2/10465/9866/68c62d43Fefff138a/140cfd7bae60b5d0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/345949/25/3207/12978/68c62d44F0787630d/4dadc02e79949a88.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/332643/40/13217/15443/68c62d44Ffcbfcda9/6aade946b9de6ba3.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348154/11/3044/54560/68c62d44F3c2cd8b8/64decb85690739be.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/349808/18/3188/55134/68c62d45Fe2e00b72/511aff6880912577.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/349865/18/3204/51157/68c62d45F377f4ce8/a2879ca17370aac1.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
