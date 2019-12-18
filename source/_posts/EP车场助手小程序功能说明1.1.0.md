# EP车场助手小程序功能说明1.1.0

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps218.jpg) 

深圳懿轩科技有限公司

2019年5月

内部参考，严禁外传

文档更新记录

| 版本  | 日期       | 修订内容           | 页码 | 修订人 | 审核人 |
| ----- | ---------- | ------------------ | ---- | ------ | ------ |
| 1.0.0 | 2019-01-24 | 新建               | 1-16 | 钟田亮 |        |
| 1.1.0 | 2019-05-16 | 增加“临停日报”功能 |      | 董俊秀 |        |
|       |            |                    |      |        |        |
|       |            |                    |      |        |        |
|       |            |                    |      |        |        |
|       |            |                    |      |        |        |
|       |            |                    |      |        |        |



## **1.** 产品概述

### **1.1** 概要

本文档介绍了EP车场助手小程序的各项功能，各模块定义及应用场景等，用于内部员工学习，帮助员工了解EP车场助手小程序，要求每个员工熟练使用所有功能，为客户快速解决问题。

### **1.2** 背景

EP车场助手小程序希望通过将原来需要线下硬件或人工处理的一些问题尽量通过该小程序在线处理，如车辆无法进出场，管理人员代缴等，从而降低线下的硬件设备成本，同时解决现金缴费漏单，记录繁琐，管理复杂等现象。

### **1.3** 使用用户

EP车场助手小程序用户，目前包括下面几类：

项目管理人员，主要指物业组织架构里的物业经理等等；

道闸管控人员，主要指物业组织架构里的保安人员，收费人员等等；

### **1.4** 产品定位

车场管理人员的微信移动岗亭。



## **2.** 功能使用说明

### **2.1** 项目管理人员登录

**使用场景：**项目管控人员进入小程序后进行登录操作

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps219.jpg) 

**功能描述：**

输入在EP停车后台的OA账号以及密码或者自有账号以及密码进行登录操作。

### **2.2** 个人中心-代缴记录

**使用场景：**项目管理人员或道闸管控人员在【个人中心】查看每个月的现金代缴（目前主要是微信临停代缴）情况以及金额统计

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps220.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps221.jpg) 

 

**功能描述：**

1. 顶部月份筛选项仅可选择有代缴记录的月份；

2. 顶部金额统计仅统计筛选月份的汇总金额；

3. 底部的代缴明细仅显示当前筛选月份的代缴明细数据（每条代缴数据展示车牌号，易停订单号，放行出口 ，缴费金额，缴费时间）；

4. 选择月份后自动刷新页面所有数据；

### **2.3** 个人中心-人员列表

**使用场景：**项目管理人员在小程序内对相关道闸管控人员进行一些简单的管理，点开【个人中心】，打开【人员列表】，选择所要管理的车场，对已注册的道闸管控人员进行上线审核，状态上下线控制，人员删除等操作。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps222.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps223.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps224.jpg) 

 

**功能描述：**

1. 点击顶部的车场筛选框，选择相应车场后，可管理已申请和已注册该车场的道闸管控人员；

2. 人员申请列表显示该人员的姓名以及手机号；

3. 人员管理里的状态开关主要控制该人员的上线以及下线，下线意味着该人员在小程序里没有任何操作权限；

4. 人员管理里的删除键主要用于删除该人员的注册信息以及操作权限，该人员的代缴数据不删除；删除后的人员可以重新注册；

 

### **2.4** 个人中心-人员注册

#### 2.4.1 车场二维码

**使用场景：**项目管控人员在小程序内为道闸管控人员提供小程序注册二维码，点开【个人中心】，打开【人员注册】，点击所要注册的车场二维码，让道闸管控人员使用微信扫一扫注册；

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps225.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps226.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps227.jpg) 

**功能描述：**

点击对应车场的二维码图标，弹出注册二维码

#### 2.4.2 道闸管控人员注册

**使用场景：**道闸管控人员打开微信扫一扫，扫描车场注册二维码进入注册页面

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps228.jpg) 

**功能描述：**注册页面包含姓名以及手机号，验证码三个字段

### **2.5** 个人中心-管控日报

**功能说明：**

EP运营停车场实行临停日报管控，项目收费人员每天上报前一天本项目的临停收入相关数据，由对应管控人员去核实和查看该车场临停收入。目前这部分工作是在微信群中上报和统计的，不方便EP管控。

本功能将管控工作线上化，提高工作效率，便于日后查证。

**使用场景：**

A. 项目收费员上报每日车场数据：车场助手小程序——个人中心——临停日报

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps229.png)     ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps230.png)

上报时间，默认为当前日期的前一天，可选择上报时间段。

本地应收、现金实收、异常金额、异常原因，请按照真实情况填写数据。

拍照上传：上传上报时间段内的照片，收费电脑截图、特殊证件照片等。可支持上传最多3张图片，jpg、jpeg、png等格式。

B. 管控人员审核，事业部/EP管控人员对收费员上报的数据进行审核：EP后台——报表——管控日报

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps231.jpg) 

 

### **2.6** 移动岗亭-进场

#### 2.5.1 车场/进场道闸口选择

**使用场景：**项目管理人员或道闸管控人员在此处选择所要解决问题的车场或道闸口，点开【进场】，选择顶部的相关选项，即可完成选择。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps232.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps233.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps234.jpg) 

**功能描述：**

点击相应选择框，弹出相应选项，选中需要选择的车场或道闸口；

#### 2.5.2 车牌获取

**使用场景：**项目管理人员或道闸管控人员在此处刷新当前道闸口的车牌识别信息，点击车牌获取后，会获取当前道闸的车牌识别数据

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps235.jpg) 

**功能描述：**

1. 默认状态下显示“当前道闸口暂无车牌识别信息”；

2. 会获取距离当前时间最近的车牌识别数据信息；

#### 2.5.3 确认进场

**使用场景：**车主在道闸口时无法进场，项目或道闸人员在小程序中点开进场，在主页中点击【车牌获取】获取车牌号，然后点击【确认进场】，查看车辆相关信息执行开闸或者其他操作，协助车主进场

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps236.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps237.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps238.jpg) 

**功能描述：**

点击【确认进场】后显示车辆当前的状态如下：

车辆状态为：月卡共享车位被占，月卡过期，临停；（一般会出现在不允许临停进场的车场）

同时当状态为月卡过期时，开闸按钮底部出现月卡续费码，可点击月卡续费码让车主使用微信扫码续费。

备注：点击【车牌获取】未获取到车牌号的情况下，点击【确认进场】会弹出该车场的无牌车进场码，如下

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps239.jpg) 

#### 2.5.4 异常进场

**使用场景：**项目或道闸人员通过小程序为相关特殊车辆，人员等等执行异常开闸操作，同时拍摄照片存储至后台；在主页中点击【车牌获取】获取车牌号，然后点击【异常进场】，然后选择异常开闸原因，拍摄照片，执行开闸操作

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps240.jpg) 

**功能描述：**

1. 异常开闸原因如下：特殊车辆，特殊人员，非机动车；

2. 拍摄照片的上限为三张，最少为一张；

3. 开闸原因与照片上传为开闸必要条件；

4. 照片必须直接拍摄，没有照片库选项。

### **2.7** 移动岗亭-出场

#### 2.6.1 车场/出厂道闸口选择

**使用场景：**项目管理人员或道闸管控人员在此处选择所要解决问题的车场或道闸口，点开【出场】，选择顶部的相关选项，即可完成选择。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps241.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps242.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps243.jpg) 

**功能描述：**

点击相应选择框，弹出相应选项，选中需要选择的车场或道闸口；

#### 2.6.2 车牌获取

**使用场景：**项目管理人员或道闸管控人员在此处刷新当前道闸口的车牌识别信息，点击车牌获取后，会获取当前道闸的车牌识别数据

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps244.jpg) 

**功能描述：**

1.默认状态下显示“当前道闸口暂无车牌识别信息”；

2.会获取距离当前时间最近的车牌识别数据信息；

#### 2.6.3 收费放行

**使用场景：**车主在道闸口时无法出场，项目或道闸人员在小程序中点开出场，在主页中点击【车牌获取】获取车牌号，然后点击【收费放行】，查看车辆相关信息执行开闸或者其他操作，协助车主出场

**功能描述：**

点击查询后各自对应的逻辑如下：

有进场记录：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps245.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps246.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps247.jpg) 

车辆状态为：月卡共享车位被占，月卡过期，临停

缴费状态：未缴费

月卡共享车位被占：显示临停缴费码以及临停代缴；

月卡过期：显示月卡续费码，临停缴费码以及临停代缴；

临停：显示临停缴费码以及临停代缴；

月卡续费码，临停缴费码点击后会弹出缴费二维码，可以出示给车主，让车主使用微信扫一扫缴费或者续费；

临停代缴：指的是项目或者道闸人员收取车主现金后，为车主在微信里代缴等额停车费；

无进场记录：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps248.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps249.jpg)![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps250.jpg) 

小程序根据车牌号搜索当前在车场的车牌号记录，筛选5个相近的车牌号对应的进场照片显示在页面里，点击【确认为该车辆】后根据进出场时间以及车辆类型状态算出需缴费费用，然后重复有进场记录的处理流程。后续追缴用于筛选了车辆照片后仍然未找到该车辆的情况下，给予项目或道闸人员录入车主信息的功能，方便后续线上客服根据录入的车辆信息寻找该车辆的进场记录，然后致电要求客户付费。

后续追缴里的手机号以及验证码均为必填。

备注：点击【车牌获取】未获取到车牌号的情况下，点击【收费放行】会弹出该车场的无牌车出场码，如下

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps251.jpg) 

#### 2.6.4 异常放行

**使用场景：**项目或道闸人员通过小程序为相关特殊车辆，人员等等执行异常开闸操作，同时拍摄照片存储至后台；在主页中点击【车牌获取】获取车牌号，然后点击【异常出场】，然后选择异常开闸原因，拍摄照片，执行开闸操作

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps252.jpg) 

**功能描述：**

1.异常开闸原因如下：特殊车辆，特殊人员，非机动车；

2.拍摄照片的上限为三张，最少为一张；

3.开闸原因与照片上传为开闸必要条件；

4.照片必须直接拍摄，没有照片库选项。

#### 2.6.5 开闸列表

EP后台——智能客服——开闸列表，筛选车场助手

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-assistant-description/wps253.jpg) 