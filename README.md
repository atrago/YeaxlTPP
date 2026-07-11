# 前言

随着信息技术的不断发展，医疗行业对信息管理的需求日益增强。基于SSM（Spring、SpringMVC、MyBatis）的医护管理系统应运而生，本项目旨在帮助医疗机构提高工作效率，实现信息化管理。以下是本项目的详细介绍。

## 内容介绍

本项目是一款基于SSM框架的医护管理系统，主要功能包括：患者信息管理、医生信息管理、科室信息管理、就诊记录管理等。系统采用前后端分离的开发模式，前端使用Vue框架，后端采用Java语言开发，具有良好的用户体验和较高的稳定性。

## 技术介绍

### 语言：Java

### 使用框架：
- Spring：轻量级Java开发框架，用于构建企业级应用程序。
- SpringMVC：Spring框架的一部分，用于实现Web应用。
- MyBatis：一款优秀的持久层框架，支持自定义SQL、存储过程等。

### 前端技术：
- JS：JavaScript脚本语言，实现前端功能。
- Vue：前端框架，用于构建用户界面。
- CSS3：层叠样式表，用于美化页面。

### 开发工具：
- IDEA/Eclipse：Java集成开发环境。

### 数据库：
- MySQL 5.7/8.0：关系型数据库管理系统。

### 数据库管理工具：
- phpstudy/Navicat：数据库管理软件。

### JDK版本：jdk1.8

### Maven: apache-maven 3.8.1-bin

### 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于患者信息查询的核心代码：

```java
// 患者信息查询接口
@RequestMapping(value = "/queryPatients", method = RequestMethod.GET)
@ResponseBody
public List<Patient> queryPatients(String keyword) {
    if (StringUtils.isEmpty(keyword)) {
        return patientService.queryAll();
    } else {
        return patientService.queryByKeyword(keyword);
    }
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

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/325660/34/18897/103893/68c28d55F7d03119f/d800ed927180d61a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327277/16/18905/29094/68c28d2dF3a02b160/1658493c961329c0.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327091/35/18861/42493/68c28d2dFd37e0322/7369a4611dbefd4b.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328521/31/18871/74065/68c28d2dFb2ccdc1e/5b7364f298d02cff.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/347771/5/2113/30016/68c28d2eF94460075/b711a50b7b071cdd.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/343464/4/2190/38751/68c28d2eF4218f05f/6a8bfa1fa82d02a1.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327568/14/18617/60406/68c28d2eF1ce222ca/3af2920af466d566.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326700/39/18781/47112/68c28d2fFc5371b4a/93eaf9e07affb103.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/299949/35/18950/32368/68c28d2fF0671a711/92934d5a0a2e0242.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344582/23/2156/47745/68c28d2fF1e653160/115852431dd222c2.jpg)
