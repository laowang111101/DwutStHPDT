# 前言

随着新冠疫情的蔓延，小区物业管理工作面临着前所未有的挑战。为了更好地进行疫情防控，我们开发了“小区物业新冠疫情物资管理平台小程序+SpringBoot”。本文将详细介绍该项目的相关内容。

# 内容介绍

本项目旨在为小区物业提供一个便捷、高效的物资管理平台，以便更好地调配和利用疫情防护物资。平台主要包括以下功能模块：物资入库、物资出库、物资查询、库存预警等。通过微信小程序端和SpringBoot后台管理端，实现物资管理的实时更新和数据分析。

# 技术介绍

## 语言：Java

## 使用框架：Spring、SpringMVC，MyBatis，微信小程序

## 前端技术：JS、Vue、CSS3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpStudy/Navicat

## JDK版本：jdk1.8

## Maven：apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下代码片段展示了如何实现物资入库功能：

```java
// 注解方式实现接口
@RestController
@RequestMapping("/material")
public class MaterialController {

    @Autowired
    private MaterialService materialService;

    // 物资入库
    @PostMapping("/addMaterial")
    public Result addMaterial(@RequestBody Material material) {
        boolean flag = materialService.addMaterial(material);
        if (flag) {
            return new Result(true, "物资入库成功！");
        } else {
            return new Result(false, "物资入库失败！");
        }
    }
}
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
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/350797/34/3197/177547/68c63b31F4d753f60/a051463c97200c47.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/332255/16/13057/36006/68c63b08F3ebbb45b/2b4d11286a4bac14.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328951/36/19485/72557/68c63b09F85912b54/411255854ae93ee3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/338271/4/10589/83795/68c63b09F69c2e2b1/cfd382989737e7b6.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328606/14/19756/18314/68c63b09Ff3bb0523/a5cc117cfadd48dc.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/331995/8/13191/86388/68c63b09F9548774d/fa1f1eca1d4a7942.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/348165/38/3323/18186/68c63b09Fbf9d1e3e/abdf68719a8df30a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337172/15/8953/41369/68c63b0aF29f0f0ce/eb0b28e2ac55bea3.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328517/21/19775/112173/68c63b0aF8ccb6a21/fd09476afd539b7b.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328185/1/19868/31894/68c63b0aF0d8626e7/62e5da6a6d22b63b.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
