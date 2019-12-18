 

 

 

#  EP停车系统功能说明 V 1.1

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps1.jpg) 

 

深圳懿轩科技有限公司

2018年10月

内部参考，严禁外传

文档更新记录

| 版本  | 日期       | 修订内容   | 页码 | 修订人 | 审核人 |
| ----- | ---------- | ---------- | ---- | ------ | ------ |
| V 1.0 | 2018-10-15 | 初版       | 1-   | 董俊秀 |        |
| V1.1  | 2019-07-05 | 第一次修订 |      |        |        |
|       |            |            |      |        |        |
|       |            |            |      |        |        |
|       |            |            |      |        |        |
|       |            |            |      |        |        |
|       |            |            |      |        |        |

 

## **1.** 概述

### **1.1** 概要

本文档介绍了EP停车系统功能，各模块定义及应用场景等，用于内部员工学习，帮助员工了解系统架构，要求每个员工熟练使用所有功能，为客户快速解决问题。

### **1.2** 系统架构及简介

EP停车系统，目前产品主要有APP、微信公众号、微信小程序、彩管家、ipos、商户后台、以及停车场管理平台等应用。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps2.jpg) 

图1.1  EP停车产品架构图

不同角色的用户，使用的产品会有差异。EP停车产品架构，如上图1.1所示。产品分布如图1.2所示。

EP停车目前的手机客户端搭建在“彩之云”App里面，所以请在手机应用市场先下载安装“彩之云”软件，并注册使用。后文的APP，都是指彩之云APP里面的“停车”模块。

微信公众号，目前有“EP车管家”（微信号：eptc_service）、 “彩之云”(微信号：hk01778)和“EP车场助手” （微信号：eptc_manager）等。

微信小程序，目前有运维人员使用的“易停项目进度”、车场道闸口使用的“EP车场助手”和车主用户使用的“EP停车用户端”。小程序开发还现处于起步阶段，开发完善中。

彩管家，彩生活集团内部软件，用户移动端办公，目前有续费申请和ipos功能，后期功能会逐渐完善。

Ipos主要用于停车场管理处收费，目前用于车场月卡缴费，支持刷卡、微信、支付宝等支付方式；彩管家里面也有ipos模块，支持、微信、支付宝支付。

商户后台，目前只有商户优惠券功能，后期会根据需求进行完善。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps3.png)

图1.2  EP停车产品分布

停车场管理平台，也叫作云平台、易停平台、新平台。不同身份授权后可登录使用不同权限。停车场管理平台连接停车场本地服务器、各种客户端和终端设备， 是我们最常用的工作平台，大家各自的所有功能模块都请熟练使用。

### **1.3** 系统用户

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps4.jpg) 

图1.3  EP停车系统用户

EP停车系统用户，目前包括下面几类：

C端用户，包括我们的车主和车场商户；

B端用户，主要指我们服务的停车场、物业公司等；

供应商，停车场硬件设备供应商以及服务供应商等；

为客户创造价值！

### **1.4** 运营模式

智慧停车场，基于SAAS云平台和智能硬件，全面线上缴费，实现停车场无人值守；基于停车大数据，提高调度能录，锁定强粘性、高复购的社区车主，开展定制化的车后服务。下图1.4所示，为EP停车运营模式。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps5.jpg) 

图1.4  EP停车运营模式

## **2.** 系统功能使用说明

### **2.1** 停车场

#### 2.1.1 停车场架构

EP停车系统的停车场管理是根据区域架构进行四级划分的：公司、大区、事业部、停车场，如下下图2.1.1所示。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps6.jpg) 

图2.1.1  停车场区域架构

#### 2.1.2架构添加/修改

当我们的区域架构有变动时，需要添加/修改，请核实后找后台超级管理员（董俊秀、谢勇峰、吴续兴等）添加，流程如下图2.2所示

添加车场时，请注意：

1）在后台查找是否已有该车场，查找关键字，名称可能多/少字，或者·

2）若没有，找超管添加，告知所属大区事业部，省市区等。

3）添加成功后，请注意修改停车场详细信息：供应商、道闸数，月卡数，大区事业部、详细地址、高德经纬度、EAS等

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps7.jpg) 

图2.1.2  EP停车系统架构添加/修改流程图

#### 2.1.3 易停区域架构

目前按照易停运营区域划为8个区域：华北区域、华东区域、华中区域、西北区域、西南区域、东南区域、广西区域、广东区域。如：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps8.jpg) 

运营同学需要根据各自所属区域的车场变化，及时更新各自区域的车场。

位置：车场架构——易停区域架构

操作：添加/编辑——易停区域名称——选择对应车场。

A. 车场选择可以根据对应的架构选择，比如选择深圳事业部，则选择了深圳事业部下面的所有车场。

B. 取消某个车场时，直接取消车场前的勾选，确定即可。

C. 每个车场只能属于一个易停区域，已经被别的区域选择后，请与对应区域沟通后修改。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps9.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps10.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps11.jpg) 

#### 2.1.3 停车场常见操作

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps12.jpg) 

（1）名词解释

ID：每个车场对应一个唯一停车场ID。

在线：停车场即时在线状态，红星![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps13.jpg)为在线，空星☆为掉线。

名称：EP停车后台停车场名称，添加车场时候注意尽量和集团、EAS保持一致。

供应商：分为云平台设备商（慧泽纯云）和本地设备商（慧泽、艾科、汉王等），有车场二者可能不一致根据实际的使用情况设置。

状态：根据停车场建设进度，分为四个阶段，计划中、建设中、运营中、已退场。

计划中：车场加入系统后，未改造的车场状态，此时其对应的供应商一般为人工通道；建设中，确认项目开始勘察后，需要根据前期的资料进行完善车场信息，并将车场状态从计划中改为建设中；运营中，车场验收通过，车场信息准确且完整，正式开始运行；已退场，车场退出运营后，将停车场状态改为已退场。

小区uuid、商户uuid：uuid是其他平台（目前只有彩之云）之间的通用唯一识别码（Universally Unique Identifier）

（2）常见操作

添加：新增停车场。新增集团内部车场时，尽量跟ICE里的车场名称一致。

编辑：新增/编辑停车场的基本信息，包括供应商、改造年月、设备套数、车位数、最大月卡数、管理员和维修员OA、地址信息、所属架构，UUID（集团车场）、高德经纬度、EAS编码（集团车场）、是否允许跨月续费、类型、临停缴费方式、当前状态、是否允许扫码支付、支持的支付方式等。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps14.jpg) 

是否允许跨月续费：是，代表该车场月卡为跨月缴费；否，代表为自然月缴费。例如某月卡到期时间为2018-09-26 00:00:00，月卡规则为30元/月，缴费2个月。若跨月，则应付费60元，购买有效期为2018-09-26 00:00:00 ~ 2018-11-25 23:59:59；若自然月，则应付费35元（第一次缴费，不满一个月按天数计算：9月26日到30日，5天，计费5元），购买有效期为2018-09-26 00:00:00 ~ 2018-10-31 23:59:59。

收费方式，即临停计费方式，目前有四种模型，需要去临停规则（详见后文）里面配置。

是否支持扫码支付：是，表示支持他人扫码代付功能（详见后文），否，不支持。

支付方式：根据车场实际需求进行配置，具体配置规则详见后文。

页面跳转：点击月卡、进场、出场、异常、设备、规则、云平台（暂未开通）、天眼查看、车场4G查看 等按钮，能直接跳转到该车场的对应页面。

月卡导出：下拉车场信息的左下角有月卡导出按钮，根据需求导出对应格式，导出的月卡为当前车场的有效月卡（已创建和使用中）。

厂家上报月卡、月卡比对：将厂家本地月卡和后台的月卡进行比对，可以查看有效期不一致的月卡。类似全场查看本地功能，有需要删除、重发的月卡，可直接重发。

月卡推送消息：设置月卡推送消息条件。

过期选择：即将过期、已经过期

过期时间：一周内、半月内、一月内

是否短信推送彩之云广告：开启时，广告推送模板为：“您在阳光商务大厦、车牌为沪A2Z337的月卡于9月30日已过期,开通彩之云-彩钱包-我的银行卡,用彩钱包支付每月享5次98折”；关闭时，广告推送模板为：“您在阳光商务大厦、车牌为沪A2Z337的月卡于9月30日已过期”；

推送渠道配置：彩之云、新版彩之云、短信、微信等

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps15.jpg) 

停车场CASE：查看停车场修改操作记录。

是否允许线上缴费：停车场当前月卡线上缴费状态查看，整体设置是否允许线上缴费。

停车场锁车设置：强制锁车，车辆进场强制锁车；立刻全场解锁，全场车辆强制解锁。

物料下载：查看和下载停车场物料二维码，可以根据需求下载使用相应的物料。

1) 快速出场临停缴费二维码：贴在停车场出口道闸旁边，每个出口有唯一的二维码。车主扫码确认车牌号后直接支付出场。编码规则：https://w.aparcar.cn/p/qr/出口道闸ID

2) 车场专用临停缴费二维码：贴在停车场内，每个车场车主出场前提前扫码输入车牌号支付后出场。编码规则：彩生活集团https://c.aparcar.cn/p/q/车场ID  非彩生活集团https://w.aparcar.cn/p/q/车场ID

3）车场通用临停缴费二维码：贴在停车场内，所有车场通用。编码规则：彩生活集团[https://c.aparcar.cn/p/q](https://c.aparcar.cn/p/q/) 非彩生活集团[https://w.aparcar.cn/p/q](https://w.aparcar.cn/p/q/)

4）无牌车进场专用二维码：贴在停车场入口道闸旁边，每个道闸有专用二维码。无牌车扫码验证后入场。需要配合快速出场二维码使用。编码规则：https://w.aparcar.cn/p/qr/进口道闸ID

下载二维码图片，保存图片，图片名称为 xx车场-xxx二维码-xx道口

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps16.jpg) 

停车场备注：停车场有特殊情况，可以添加、查看备注信息，文字+附件。

附件限制：上传附件总数不超过3个，单个附件不超过5M，允许上传文件类型jpg/png/pdf格式。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps17.jpg) 

#### 2.1.4 停车场设备管理

设备管理

停车场改造完成后，上线前，需要在设备管理里面添加车场设备，设备编码由厂家提供。

当前设备有六种：道闸、收费电脑、识别摄像头、收费平板、普通摄像头、地感。

普通摄像头，即车场天眼，在线的情况下能直接实时播放视频。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps18.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps19.jpg) 

萤石摄像头

停车场安装萤石摄像头后，需要将设备添加到公司萤石账号下(账号：18681501726)，再同步到EP停车场管理平台。

1） 添加设备。登录萤石开发平台（https://open.ys7.com/），添加设备编码和序列号、命名统一为“停车场名称-摄像头名称”

2） EP后台——萤石摄像头列表，同步萤石账号数据，同时同步到设备管理列表里面。

3） 萤石摄像头列表，能查看设备状态和播放视频

4） 设备管理列表中的萤石摄像头也支持播放

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps20.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps21.jpg) 

#### 2.1.5 停车场资料管理

用于存放停车场合同、验收单等电子版资料，便于线上及时查阅。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps22.jpg) 

资料类型：易停合同、商户合同（暂无）、验收单等

(租金)金额：合同中若存在金额

资料编码：根据实际编码填写

资料上传：只能上传PDF资料且小于5M，纸质文件签章扫描后上传

状态: 标记当前合同的状态，有生效、过期、续签、废除四种状态

资料上传人：输入资料上传人姓名

资料有效期：几年，有效期开始时间、有效期结束时间。

备注说明：可以填写相关备注说明情况

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps23.jpg) 

### **2.2** 通行管理

#### 2.2.1 进场记录

进场记录数据来自厂家上报。厂家需要实时上报每一辆车的进出场数据：停车场、车牌号、入口、车辆类型（月卡、临停）进场时间，以及上传进场图片。

当出现漏传、图片无法查看等问题，需要找厂家进行解决。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps24.jpg) 

#### 2.2.2 出场记录

出场记录数据来自厂家上报。厂家需要实时上报每一辆车的出场数据：停车场、车牌号、出口、车辆类型（月卡、临停）进场时间、出场时间，本次临停应收金额、实收金额以及上传进场图片。

当出现漏传、图片无法查看、应实收数据不准等问题，需要找厂家进行解决。

出场记录中，标黄的记录，表示有临停金额且为非线上缴费的记录；标绿的记录，表示有临停金额且为线上缴费的记录，能查看跳转筛选到该订单的交易订单页面

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps25.jpg) 

#### 2.2.3 异常开闸

异常开闸数据来自厂家上报。厂家需要实时上报每次非自动开闸的数据：停车场、车牌号、出入口、类型（遥控器、系统）、异常时间、异常原因、异常图片。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps26.jpg) 

每次异常开闸意味着车场收入的漏洞，异常开闸需要运营重点管控。杜绝遥控器开闸，降低系统开闸。

#### 2.2.4 无牌车进出场

无牌车，主要是一些无法正常自动识别的车辆，比如临时车牌等；

针对这部分车辆，在无人值守的停车场，进出无忧。

车主使用步骤：

进场前，在道闸口扫描进场二维码（https://w.aparcar.cn/p/qr/进口道闸ID

）→验证手机号→开闸进场

出场前，在道闸口扫码（https://w.aparcar.cn/p/qr/出口道闸ID

）→缴费→支付完成出场

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps27.png)

说明：

1.贴无牌车进场二维码的车场，需联系厂家取消未识别车牌压地感进场设置；

2.进场是直接下发开闸命令的，所以需要验证手机号，操作后有记录；

进场扫码获取用户微信ID，开始计费；出场扫码查询微信ID的订单，缴费出场；

3.出场的二维码必须为快速出场二维码；

4.当用户在免费时间内出场时，也需要扫码确认出场；

5.无牌车功能使用了微信临停云端计费，后台需要已经配置相应临停收费规则；

6.请项目人员引导车主扫码出场，异常出场会导致下次无法进场。

无牌车领取优惠券

扫码进场的无牌车可以领取商家提供的停车电子优惠券领券时输入车牌号：

EP+手机号后5位。

\1. 发券时会查车辆在场状态，如果不是扫码进场的会查不到信息，导致无法发券/领券。

\2. 优惠券出场扫码时自动抵扣使用。

\3. 发券手机号和扫码手机号必须一致，才能领券。

无牌车进出场记录

可以在后台查看无牌车进出场记录和状态。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps28.jpg) 

进场时间：用户扫码验证后开闸的时间。

出场时间：

当用户进场扫码后，出场时间跟进场时间相同，状态为场内。

当用户出场扫码后，未支付成功前，出场时间为出场扫码时间，状态为场内。

当用户出场扫码后，未支付成功后，出场时间为支付成功时间，状态为离场。

#### **2.2.5** 黑白名单

1）功能说明

黑名单：加入黑名单的车辆，不能进入车场，表现为进场时，不会自动抬杆放行。

白名单：加入白名单的车辆，能正常进出车场，主要针对某些需要临停放行的停车场（一般临停车辆禁止进场）。

2）位置

位置：导航栏——通用——黑白名单

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps29.jpg) 

3）操作步骤

添加黑/白名单

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps30.jpg) 

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps31.jpg) 

输入停车场名称、车牌号、和时间限制后，选择加入黑名单或者白名单。当时间失效后，自动恢复到加入前的状态。

时间也可以手动输入，格式为：2017-11-28 - 2017-12-31，输入后点回车键。

状态

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps32.jpg) 

已在黑名单：车辆加入黑名单后的状态

已在白名单：车辆加入白名单后的状态

不在白名单：车辆解除白名单后的状态

不在黑名单：车辆解除黑名单后的状态

操作

单击操作按钮，"result": 0 ,表示下发成功。

| 操作           | 说明                                   | 操作成功后的状态        |
| -------------- | -------------------------------------- | ----------------------- |
| 下发加入黑名单 | 把该黑名单车辆下发到本地，不让车辆进入 | 已在黑名单              |
| 下发解除黑名单 | 在本地黑名单中删除该车辆               | 不在黑名单              |
| 下发加入白名单 | 把该白名单车辆下发到本地，允许车辆进入 | 已在白名单              |
| 下发解除白名单 | 在本地白名单中删除该车辆               | 不在白名单              |
| 修改时间       | 修改黑白名单时间限制                   | 黑/白名单车辆有效期更改 |

注意

（1）预约进场等功能，实际用到的就是黑白名单功能。

（2）当某辆车既是月卡又是黑名单车辆时，厂家判断月卡优先。可取消掉月卡后再下发黑名单处理。

（3）车辆设置黑白名单后，实际是否有效，需要本地确认。若无效，需要找厂家对接处理。

#### **2.2.6** 免费预约进场

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps33.jpg) 

 

A. 后台——停车场——编辑，设置停车场预约进场属性设置：人工审核、系统审核。

默认为系统审核（上面流程中的自动审核，即为系统审核）

系统审核，只有月卡车主能帮忙给其他车辆预约。预约后，系统自动同意并下发。人工审核，所有车主都能预约，且预约后需要管理员同意或拒绝。

B. 用户APP预约

个人中心→预约进场→输入自己的预约信息：车牌、停车场、预约时间→确认

提交预约后，可以点击“预约进度”，查看本次进度和预约记录

a) 若该车场是自动审核车场

只能是业主帮亲戚朋友预约，即在该车场有月卡。

若非业主，则会提示无预约权限。

b) 若该车场是人工审核车场

业主和非业主都能预约。提交预约后，为待审核状态。车场管理员审核同意后，才是审核通过。若被拒绝，则审核不通过。

c) 取消预约

当预约结束时间大于当前时间时，用户可以取消预约，取消后状态变为已取消。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps34.png)

C. 后台——预约进场列表，查看/审核停车场预约记录

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps35.jpg) 

 

支持预约进场列表，支持停车场、车牌号、审核方式（人工审核、系统审核）状态（待审核、已通过、已拒绝、已取消）等筛选查看。

申请时间：提交预约申请的时间

预约开始时间~预约结束时间：预约进场的时间段

操作及状态说明：

通过/拒绝，需要确认一下。

同意——确认，审核通过，将待审核状态改为已通过；

拒绝——确认，审核不通过，将待审核状态改为已拒绝；

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps36.jpg) ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps37.jpg)

确定，改变状态；取消，不改变状态，只是关闭弹框，可以继续审核。

取消，关闭弹框，状态不变，可以继续审核。

重发，已通过的预约，如果之前下发失败了，可以重发白名单到本地

恢复，已拒绝或已通过的状态，可以恢复到待审核状态

取消，APP里未过期的待审核预约可以取消，后台已同意的预约可以取消。取消后变为待审核状态。

详情见下表：

| 当前状态 | 操作按钮               | 操作逻辑                                                     | 之后状态                    |
| -------- | ---------------------- | ------------------------------------------------------------ | --------------------------- |
| 待审核   | 同意 拒绝  APP取消     | 下发白名单到厂家，并变状态 只变状态  只变状态                | 已通过 已拒绝  已取消       |
| 已通过   | 重发 恢复取消  APP取消 | 重发到厂家 变状态，取消白名单 变状态，取消白名单 APP，取消白名单 | 已通过 待审核已取消  已取消 |
| 已拒绝   | 恢复                   | 只变状态                                                     | 待审核                      |
| 已取消   | 恢复                   | 只变状态                                                     | 待审核                      |

 

### **2.3** 缴费

#### **2.3.1** 月卡新增

目前有三种方式新增月卡：月卡导入、月卡申请、添加月卡。

月卡导入：停车场新建后，如果有历史数据，第一次可以通过月卡导入的方式加入系统；免费车走邮件审批后可以进行导入延期。

月卡申请：需要项目人员引导用户使用月卡申请。

添加月卡：特殊情况下，比如测试时，可以直接在添加月卡，其他时候不允许直接添加。

#### **2.3.2** 月卡规则

确认改造车场后，运营需要将该车场的月卡收费规则录入系统。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps38.jpg) 

添加/编辑月卡规则

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps39.jpg) 

名称：该条月卡规则名称，例如地库100等

类型：月卡

车型：小型车、中型车、大型车、超型车。目前全部默认为小型车。

设备：根据进出通道权限选设备（道闸），不选默认为全部

规则类型：当前月卡，年卡有效。

缴费渠道：线上缴费（彩之云/懿轩微信，具体看停车场支付方式配置）、ipos、停车宝、车位宝、e费通（该通道已关闭）。默认为全部开通，关闭某项时去掉勾选。

最小缴费数：填数字，比如3（月/年）

缴费截止时间：车场由于价格上调等原因需要限制缴费时间，即用户购买的最大有效期。不填，默认为不限制。

价格N1：填数字，比如100（元/(月/年）)

状态：激活，表示该规则能正常使用；禁止：该规则禁止使用，规则下的月卡禁止缴费。

规则ID：保存后，月卡规则里面的第一列为规则ID，月卡导入时会用到。

月卡规则下发

保存后，点击“下发”按钮，下发月卡规则到厂家。

返回结果为 "result": 0，表示下发成功。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps40.jpg) 

#### **2.3.3** 月卡导入

项目改造过程中，需要收集月卡资料并按模板填好。运营再将整理好的月卡一次性导入到EP系统。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps41.jpg) 

说明：月卡导入功能只适用于新建月卡和免费车导入

操作步骤：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps42.jpg) 

按模板填写

导入页面，左上角，有月卡导入模板下载按钮，请根据月卡模板填写月卡资料。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps43.jpg) 

月卡模板注意事项：

文件命名和表格标题，为停车场名称，需要和EP停车场后台里面的停车场名称一致。

客户，车主姓名；手机，11位真实手机号码；车牌，普通车牌直接填写主卡车牌列，一卡多车和子母车，主副卡分开，主卡一张车牌，副卡可以是多张车牌，每张副卡之间用英文逗号“,”。

规则必须跟车场匹配，金额必须和规则匹配。

有效期格式：2018/5/1-2018/5/31，或者2018/05/01-2018/05/31

类型，只有一卡多车、子母车。

多位多车，填写车位数，例如三位四车，填3。

上传导入文件

一步一步进行，每进行一步，下面会有提示，有错改错。

整表检测——行检测——入库——下发

 

注意：

（1）每次导入，限量2000行

（2）人工通道，只到“入库”这一步，就完成了

（3）某些特殊情况需要二次导入的，通过邮件审批后，找有覆盖权限的运营同学帮忙导入处理。

#### **2.3.4** 月卡申请及审批

车主在APP 上申请月卡后，告诉项目管理员，项目管理员审核通过后，月卡申请成功。

车主月卡申请

线上申请月卡，停车月卡出入省时更方便。

操作步骤：输入车牌号→选择停车场→验证手机号→输入地址信息→上传证件照→完成

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps44.png) 

车主能查看月卡申请进度：

待审核：可以联系项目人员进行审核

审核通过：月卡申请成功，可以去缴费后使用月卡进出权限了

审核不通过：被拒绝了，联系项目人员了解情况，是否重新发起申请。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps45.png) 

项目人员月卡申请审批

项目人员在月卡申请页面，审核车主证件是否有效，根据车场月卡情况判断是否予以通过。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps46.jpg) 

同意：审批通过，则选择对应月卡规则及开始使用时间。开始使用时间选了哪天，业主就从当天开始缴费。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps47.jpg) 

拒绝，审核不通过，输入拒绝理由。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps48.jpg) 

 

 

#### **2.3.5** 月卡操作

月卡基本信息：停车场、车牌号、有效期、月卡规则、车位数等。

状态：已创建，添加到系统后，还未操作过，为有效月卡；使用中，月卡使用中，为有效月卡；已禁用，暂停该月卡，车辆进出按临停计算，启用时恢复；已取消，取消该月卡，删除厂家本地信息，平台只保留查看功能。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps49.jpg) 

添加/编辑月卡

停车场：选择所属停车场

主卡车牌：第一个车牌号，缴费等都根据主车牌计算

类型：一卡多车，普通的一位一车、多位多车、多为多种，统称为一卡多车；子母车：有子母车位的车。

收费规则：对应月卡规则

月卡手机号：月卡使用人的手机号，务必填准确

开始时间、结束时间：即月卡有效期，会根据月卡续费改变。

车位名称：有车位的月卡填写车位号

车位数：根据实际填写车位数

内场车位数：有内场限制的填写内场车位数，默认为0，便是没有

房号/楼栋号：月卡车主信息

状态:使用中/已取消

是否允许线上缴费：单张月卡限制线上缴费（彩之云/懿轩微信）

是否紧急开闸：紧急开闸权限控制，是代表有权限，否则无。

提交：表示保存信息在EP平台，未下发到厂家；

提交后发送厂家：有效期、规则等变动时需要提交后下发厂家。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps50.jpg) 

 

基本信息

项目人员可以点击“基本信息”按钮对月卡基本信息进行编辑。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps51.jpg) 

月卡换规则

规则低→高：项目人员能直接在基本信息里面把月卡规则由低价换位高价，且会自动缩短有效期。

比如某用户之前是地面月卡100元/月，还有20天有效期。他现在想停地库，规则为200元/月。那么现在由地面规则换位地库规则后，其有效期会缩短至10天。

规则低→高：这种一般发生在买车位等情况下，需要项目人员先发起“换规则申请”上传车主车位产权证明等凭证；再由运营同学审核处理。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps52.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps53.jpg) 

换规则申请审批同意时，若车主有需求就更改（延长）有效期，无需求则不改变有效期。

重发本地、清空本地和查看本地，都是跟厂家平台月卡数据对接。

重发本地：当发现我们平台续费成功而本地有效期为更新时，重发月卡一下，返回"result": 0 ,表示下发成功。

清空本地：偶尔出现重发失败，可以先清空本地数据后再重发，一般就会成功。

查看本地：查看厂家平台该月卡情况，发现有效异常的，需要删除重发处理。

全场重发：某些车场数据出现大量数据不同步的情况，可以反馈给开发同学，进行全场重发操作。

清空车场本地月卡数据：特殊情况下（例如本地有回收权限前的月卡数据等），跟项目人员确认好，本地没有非机动车数据后，反馈开发反馈给开发同学，进行清空车场本地数据操作。

清空车场平台月卡数据：特殊情况（例如月卡导错了），做好月卡备份，反馈开发反馈给开发同学，进行清空我们平台月卡数据操作。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps54.jpg) 

换车牌：

换车牌，实际是交换新旧车牌有效期。

条件：新旧车牌都是同一车场规则相同的月卡

操作：输入新车牌，确认更换

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps55.jpg) 

换车牌日志：可以查看该辆车的所有换车牌记录。发现某些车频繁更换车牌，需要关注一下原因。

CASE日志：查看该月卡的所有操作历史记录。

到期提醒：若月卡在7天内过期，可以点击“到期提醒”推送短信消息给业主。

月卡报停：

使用背景：用户车辆长时间不在本地使用，比如长期出差、车辆暂停使用等情况，为方便用户，开发月卡报停功能。用户需要上报暂停天数，对应有效期后延。在报停期内，车辆进出按临停收费。

 

使用条件：月卡有效期≥1个月，报停时间≥15天

后台设置：月卡里面，月卡暂停按钮，选择暂停时间。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps56.jpg) 

报停成功：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps57.jpg) 

报停状态：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps58.jpg) 

 

小于15天时，提示“暂停时间需要≥15天”。

选好暂停起始时间后，月卡处于禁用状态。

到期后，月卡有效期自动后延。

若想恢复月卡，也需要判断之前暂停时间是否≥15天。是，自动延期；否，不延期。

目前月卡报停只是我们运营人员操作，车主有需求报给项目，项目上报，运营再处理。

锁车

为增强车主在停车场中的车辆安全性，EP停车推出了锁车功能。即车辆进入停车场后可点击“锁车”，车辆会锁定，未解锁前车辆欲驶出车场，不会自动开闸。只有在解锁后，才能开闸放行。

解锁/锁车，车主能在月卡卡片页面进行解锁/锁车操作。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps59.jpg) 

 

后台也能设置和查看锁车状态：

解锁/锁车操作：帮车主进行解锁/上锁

跟随停车场锁车/不想被锁车：跟停车场锁车状态一致或不锁车

读取状态：查看当前车辆的锁车状态及锁车记录

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps60.jpg) 

收费房间绑定

对接收费系统的小区、房间、楼栋信息进行物业费绑定和银行代扣房间绑定。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps61.jpg) 

多位多车的绑定和解绑

1）多位多车绑定：

（1）新车牌

在平台上有主卡的信息，但是搜索不到副卡的，可以在月卡编辑里面添加车牌信息，添加新车牌需要提供手机号，添加新车牌以后再操作绑定。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps62.jpg) 

（2）绑定一张月卡

在平台上有月卡信息的做多位多车的绑定，如果规则不一样的，绑定的时候系统会自动的把副车牌更改为与主车牌一致的收费规则。

（3）绑定两张以上的月卡（包含两张）

在平台上有月卡信息的做多位多车，如果规则不一样的，绑定的时候系统会有提示规则不一样，之后需要手动更改为与主车牌一致的规则后才能继续操作绑定。

2）多位多车解绑：

（1）无法解绑

平台上的多位多车绑定在原先的基础上做了改进。由于改进之前存在规则不一致绑定后删除不了的情况，请先点击编辑，保存月卡后，再重新解绑。

（2）删除

多位多车的删除可以在月卡，点击月卡最前面的小箭头，在下拉框的车牌后面的”X”可以删除。同时也可以在月卡编辑里面的”删除副卡”里面删除。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps63.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps64.jpg) 

3）	更换主车牌

多位多车绑定后，可以在平台上进行主车牌跟副车牌的调换。操作如下：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps65.jpg) 

4）多位多车删除后，副车牌的有效期系统自动修改为解绑的当天。  

##### 紧急开闸功能

使用场景：在月卡中配置紧急开闸功能后，该月卡若在有效期内，出现识别错误不开闸的情况，能通过紧急开闸进出场。

流程：

a) 运营人员在后台给月卡开通紧急开闸功能：月卡——编辑——紧急开闸：是

b) 车主APP页面进行操作：

APP——个人中心——我的尊享——紧急开闸

选择车牌号→选择停车场→申请紧急开闸→输入道闸显示屏上的开闸码→开闸成功

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps66.png)

##### 绑定物业费

背景：由于某些小区的某些业主长期物业费欠费，想通过停车月卡绑定房间号的方式，促使业主交物业费。业主在彩之云交停车月卡时，若物业费欠费，则跳转E费通物业费缴费页面，缴清物业费后才能交停车费。

目的：停车费和物业费联动，促进物业费缴费。

操作步骤：

a) 收费房间绑定，将该户的停车月卡和物业收费房间绑定在一起：

EP停车车辆管理后台——月卡——（下拉展开）收费房间——选定楼栋、房间号——物业费——保存

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps67.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps68.jpg) 

 

b) 业主缴费：

彩之云APP——停车——月卡缴费

绑定房间号后，若该户物业费已缴清，则可以直接交月卡费用；

若物业费有欠费，则点支付时会提醒 “您的物业费尚未缴清，无法支付月卡费用……”，自动跳转到E费通页面缴清物业费后再交月卡。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps69.png)

说明：

a)物业费是由E费通计算的，直接在E费通页面确认信息后提交订单支付就行。若费用计算有误，请咨询E费通相关工作人员。

b)缴清物业费后，可以从E费通首页右下角“缴停车费”跳到E停首页去缴停车费。

c)绑定错误的，在EP停车车辆管理后台重新绑定即可。

##### 一卡通

一卡通是一项特殊权限，车主月卡有效的情况下，在一卡通区域车场临停免费进出。

开通流程：

a) 用户发起审批2.0——车辆管理审批——一号通审批——写明详细情况：姓名、手机号、车牌号、月卡缴费停车场、需开通一号通的区域等。

例如，张三，手机号138000000000，车牌号粤BXXXXX，

月卡缴费停车场：彩悦大厦。

需要开通一号通区域：七星商业广场、彩悦酒店地下停车场。

b) 审批通过后，运营人员在后台开通

i. 查看是否已经有该一卡通区域，若没有，需要先添加一卡通区域：

新后台——导航栏——一卡通区域——添加

弹框，如下图所示，填好内容：

名称：统一为“XX（区域）一卡通”，例如 武汉事业部一卡通

区域选择：选择需要开通的区域，可以是多个车场、事业部、大区等。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps70.jpg) 

注意：一卡通区域添加后，也可进行编辑，删除/恢复操作。

ii. 添加一卡通车牌

车辆设置一卡通的前提：该车辆是月卡。

新后台——导航栏——一卡通列表——添加——提交

先输入车牌，再选择缴费停车场和一卡通区域：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps71.jpg) 

c) 一卡通使用

i. 场内付费0.01元，15分钟内出场。

ii. 道口有预出场，直接出场；没有，支付0.01出场。

说明

1）月卡需要是有效的，过期前请缴费

2）在月卡停车场，正常月卡进出

3）去其他非月卡停车场，临停进出，出场时需要缴费0.01元。

4）若进场时，车场设置临停确认放行，请岗亭确认放行即可。

#### **2.3.6** 月卡缴费

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps72.jpg) 

费用计算：

A 通用月卡计费：缴费金额=月卡规则*车位数*缴费数

B 月卡折扣：

背景：项目想用优惠活动的方式鼓励业主缴费，经各方批准后，可设置月卡折扣。

例如，100/月的月卡，涨价为160/月，若一次性缴费12个月的，只收1600（相当于优惠了2个月的费用）。

设置方法：月卡折扣，需要进行审批，哪些车场做活动，活动内容等。审批通过后，由易停运营人员设置收费优惠。

EP停车场管理平台——月卡——月卡折扣——添加

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps73.jpg) 

填写停车场名称，选择活动的月卡规则

选择折扣方式：一口价或者固定优惠

一口价是每月固定金额；固定优惠是每单减固定值

每月限购次数：每月能享受几次优惠

活动状态：启用/禁用

需要紧急关闭月卡折扣时，可以手动禁用。

活动金额，优惠活动计算后的每月月卡费用

缴纳月数，至少交多少个月的费用能享有该优惠活动

优惠开始时间，缴纳改时间点后的费用享有优惠

购买开始时间，即活动开始时间

购买结束时间，即活动结束时间

优惠说明：提醒用户该活动说明

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps74.jpg) 

上面优惠活动详情为：

假如业主现在的车辆月卡收费为100/月，有效期到2017-12-31，满足条件“有效期超过2017-12-30”。那么他现在给月卡续费12个月，原本应交12×100=1200元，现在优惠只用交1000元了，相当于优惠了两个月的停车费！

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps75.jpg) 

上面优惠活动详情为：

假如今天2018-08-1业主的车辆月卡收费为200元/月，有效期到2018-6-30，购买有效期2018-06-30~2018-07-30，这一个月费用不享受优惠，想要享受优惠就需要缴费13个月以上，若缴费13个月则应交13×200-400=2200元。

##### 月卡续费

1） 有月卡后，车主能在APP端进行线上自主缴费，并查看缴费记录

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps76.png)

 

2） 车主到物业管理处去找项目人员通过ipos缴费

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps77.png)

实际操作演示图如下：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps78.png)

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps79.png)

 

常见问题及解决方法：

A. 停车场，需要输入正确，选择正确

B. 如右图所示的车牌输入框的使用方法：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps80.jpg) 

a) 选择正确的车牌号码

b) 选错时可以点到错误的位置直接重新输入，或者清除后输入

c) 输入完成后，点关闭

 

C. 输入车牌后，提示“车牌不存在”或“该场没有这个月卡”，如下图所示

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps81.jpg)    ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps82.jpg)

车牌不存在：输入车牌号码错误，请重新输入车牌号

该场没有这个月卡：易停系统中有该月卡，但不属于该车场。请确认车场是否正确，车牌号是否正确后，重新输入。

D.点支付时提示“请完善手机号” ，如右图所示

 ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps83.jpg)

请修改填写完整的手机号。

E. 若使用中有其他可反馈至开发群！

 

3） 通过停车宝缴费

停车宝是由彩富人生主导的一款金融产品，是通过投资返停车费的方式跟EP系统对接。例如某车主在一小区的月卡是100元/月，那么一年停车费为1200元，若他对应购买停车宝2万元一年期，那么他们本年不用自己交停车费（停车费由彩富出）且能得到本金+部分彩饭票。（大概是这样，细节需要彩富那边帮助）

对接：停车宝对接了EP的月卡查询接口，获取月卡信息。

车主购买停车宝成功后，彩富下单，生成对应半年期/一年期的订单。

交易订单里包含了前三种订单，筛选条件：类型（月卡）来源（双乾、懿轩微信、ipos、易停POS、停车宝）

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps84.jpg) 

4） 通过其他方式（现金、刷卡、代扣、支票、转账等）线下缴费

A. 银行代扣

背景：某些小区的某些业主，月卡停车费可能通过银行代扣的方式进行缴费。针对这一部分订单，曾经是走续费申请的方式进行月卡续费。现在，我们连接收费系统，通过绑定收费户，获取业主代扣订单，自动月卡续费。

目的：银行代扣的业主，月卡自动续费。

说明：

a) 订单取自收费系统银行代扣里面有停车费的订单。收费系统若没有订单，则无法自动续费。

b) 当银行代扣订单的停车费=月卡金额的N(整数)倍时，自动续费N月；

例如：月卡为100元/月，取到的银行代扣订单里面有停车费300元，则给该月卡自动续费3个月。

c) 如果一户业主家有多辆车，即多张月卡绑定同一收费房间时，且银行代扣订单的停车费=月卡金额A+月卡金额B+……，会同时给这几张月卡续费。

例如：月卡A 250元/月，月卡B 300元/月，而取到的银行代扣订单里面停车费为550，则自动给月卡A和B一起续费一个月。

d) 续费不成功，请用原来的方式续费。

操作步骤：

EP停车  车辆管理后台（https://new.aparcar.cn）

a) 收费房间绑定：

月卡——（下拉展开）收费房间——选定楼栋、房间号——银行代扣——保存

注意：请务必保证收费房间绑定正确，否则会出现续费错误或失败的情况。

绑定错误，请及时修改：收费房间——重新编辑/解绑。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps85.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps86.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps87.jpg) 

b) 已续费订单查看：

订单——银行代扣订单——筛选 “成功”订单查看。

这些成功的订单，已经自动给月卡续费，不需要再走续费申请。

失败的，查看房间是否绑定正确，月卡金额是否对应上。

B. 续费申请——续费申请审核——续费订单

步骤1：其他线下缴费的月卡，项目人员需要通过续费申请来进行月卡续费。

**a)** EP停车场管理平台：订单——续费申请——添加续费申请

**b)** 彩管家APP：微服务——e停车——续费申请

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps88.jpg) 

输入车牌和停车场→确认月卡规则和缴费月数→选择付款方式→上传清晰有效缴费凭证，如收据、银行付款单等→提交

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps89.jpg) 

步骤2：易停运营人员在续费申请里审核：

查看凭证→凭证是否有效→同意/拒绝审批

同意表示续费申请审批通过，则自动生成该月卡的续费订单，同时给月卡续费。拒绝表示续费申请审批不通过，不会生成续费订单，不会月卡续费，需要重新发起申请，上传有效凭证。

步骤3：查看续费订单

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps90.jpg) 

#### **2.3.7** 临停缴费

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps91.jpg) 

##### 费用计算

**A.** 厂家本地计费

目前我们车场临停采用的都是厂家本地计费

当车场改造完成后，会在本地服务器上配置临停规则，车辆进场后自动计时，出场前进入输入车牌号，直接查询厂家此时计费，再缴费出场

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps92.png)

线上缴费的订单，能在交易订单里查询。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps93.jpg) 

**B.** 云端计费

背景： 便于云端计算临停费用，减少车场收入漏洞

计费规则：每个临停收费停车场都需要在后台录入临停收费规则，各区域负责自己所辖车场。无牌车计费使用的是云端计费，请提前配置。

l 按次收费

l 按时收费

l 按时段收费

l 按梯次收费

 \>按次收费：免费时长（分钟）、收费周期、单次收费金额

收费周期：24小时表示今天晚上8点到明天晚上8点；24点，表示过零点重新计费。

例如：一小时内免费，2小时以上24小时以内5元每次！

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps94.jpg) 

\>按时收费：免费时长（分钟）、起始时间、最低收费金额、最高收费金额、车型、免费时长、收费周期、收费金额

收费方式：不重复收费，收费周期内多次进出如果交过最大金额了，再次进出不收费；重复收费：每次进出重新计费。

例如：30分钟内免费，超过30分钟到3小时费用为5元，每增加1小时加1元。全天24小时以收费不超过10元。

如果不重复收费：如果第一次停了7小时，缴费9元。隔了一小时后再次进来，第二次停了2小时，则第二次只需缴费1元。之后进出，只要在24小时内，不用再缴费。

如果重复收费：如果第一次停了7小时，缴费9元。隔了一小时后再次进来，第二次停了2小时，则第二次还要缴费5元。之后每次进出，都重新计费。 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps95.jpg) 

\>按时段收费：免费时长（分钟）、时间分段、每段金额、最高收费

例如：2小时内免费，超过2小时且8小时内收费5元，白天6点到晚上零点收费5元。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps96.jpg) 

\>按梯次收费：免费时长（分钟）、时长收费、最高收费

例如：2小时内免费，超过2小时且8小时内收费5元，超过8小时且23小时内收费10元，超过23小时且24小时内收费15元。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps97.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps98.jpg) 

**C.** 现金临停

车场安保人员在岗亭处收到的现金临停，一般会在交接班的时候上缴给车场收费员。再由收费员统一以日报上缴的方式上缴到平台。

APP——个人中心——我是管家——车场日报

输入停车场→选择收费时间段→输入上缴金额→上缴收费

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps99.png)

日报订单

后台——订单——日报订单

日报订单里面可以查看各车场日报上缴详情。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps100.jpg) 

**D.** 无感支付

目前已经对接了银联和建行的无感支付，建行的还未正式使用。

银联无感支付，支持银联信用卡和民生银行借记卡，深圳区域89个停车场已上线。在“智车会”微信公众号（微信号:gh_c440d553ff65）上绑定车辆。

车辆进出已上线车场，微信缴费时会提示：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps101.png) 

在场内支付候，不会再从银行卡扣款。

出口道闸处，会自动放行，出场后再从银行卡自动扣款。

#### **2.3.8** 支付设置

**A.** 缴费来源

| 缴费方式           | 来源-交易订单 | 费用类型             | 适用车场   | 对账/查单    |
| ------------------ | ------------- | -------------------- | ---------- | ------------ |
| 彩之云APP          | 双乾          | 月卡、临停、优惠券等 | 彩生活车场 | 彩之云       |
| 彩之云公众号       | 彩之云微信    | 临停                 | 彩生活车场 | 彩之云       |
| 懿轩公众号EP车管家 | 懿轩微信      | 月卡、临停、优惠券等 | 所有车场   | 彩钱包/微信  |
| ipos               | Ipos          | 月卡                 | 彩生活车场 | Ipos后台     |
| 易停POS            | 易停pos       | 月卡                 | 外部车场   | Ipos后台     |
| EP停车客户端小程序 | 微信小程序    | 月卡、临停           | 外部车场   | 小程序商户端 |
| 无感支付-银联      | UNIONPAY      | 临停                 | 所有车场   | 银联         |
| 停车宝             | 停车宝        | 月卡                 | 所有车场   | 彩富         |
| 支付宝             | 懿轩支付宝    | 月卡、临停           | 所有车场   | 支付宝       |
| 智轩微信           | 智轩微信      | 测试                 | 测试       | 微信         |

B. 支付方式限制

a) 停车场——编辑——支付方式配置

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps102.jpg) 

b) 停车场——是否允许线上缴费

c) 月卡规则限制，月卡规则，支付方式限制

d) 月卡限制，月卡，是否允许APP续费

C. 查单

a) 交易订单——未支付订单检测，目前支持双乾、彩之云微信、ipos，易停POS

b) 支付检测不了或是未成功的，需要查单

| 查单                  | 地址                                                         | 登录   |
| --------------------- | ------------------------------------------------------------ | ------ |
| 彩之云-彩之云运营平台 | [http://check.account.colourlife.com/#/login](http://check.account.colourlife.com/) | eptche |
| Ipos-ipos后台         | http://ipos.backyard.colourlife.com/                         | eptche |
| 微信、车位宝等其它    | 找对应微信群查单                                             | /      |

 

 

| 渠道            | 彩之云单号   | 查单                 | 易停单号       |
| --------------- | ------------ | -------------------- | -------------- |
| 彩之云-月卡     | 201801_xxxxx | 易停单号或预付单号   | 彩之云对接群   |
| 彩之云-临停     | 9035xxxx     | 易停单号或第三方单号 | 彩之云对接群   |
| 微信            | 42000000xxxx | 第三方单号           | 彩之云对接群   |
| 停车宝-彩富人生 | 103xxxx      | 第三方单号           | 彩富人生对接群 |
| 车位宝-彩车位   | 105xxxx      | 第三方单号           | 车位宝对接群   |
| Ipos-E停车      | 18xxxx       | 第三方单号           | Ipos协作群     |

 

#### **2.3.9** 电子发票

1) 车场电子发票需求统计

A. 普通纸质发票，如下图两种，物业公司名称、费用名称，税率等

B. 费用拆分

| 编码        | 合并编码            | 分类编码简称 | 名称         | 税率 | 优惠政策内容 |
| ----------- | ------------------- | ------------ | ------------ | ---- | ------------ |
| 30405020202 | 3040502020200000000 | 经营租赁     | 车辆停放服务 | 5%   | 按5%简易征收 |
| 304080101   | 3040801010000000000 | 企业管理服务 | 物业管理服务 | 6%   |              |

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps103.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps104.png) 

2) 发票费用配置

电子发票——发票费用

根据实际发票，配置对应费用、费率。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps105.jpg) 

3) 纳税人列表添加

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps106.jpg) 

4) 开票规则配置

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps107.jpg) 

5) 交易订单开票

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps108.jpg) 

6) 查看开票记录

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps109.jpg) 

7) 用户开票

缴费车场支持开电子发票时，用户可以在自己的订单页面，自主开票。

我的订单→开发票→填入开票信息→发送到邮箱

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps110.jpg)    ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps111.png)

#### **2.3.10** 我的订单

#### **2.3.11** 彩惠抵扣金缴停车费

EP停车跟彩惠人生合作，支持在彩之云APP里面缴停车费时，使用彩惠抵扣金缴停车费。

**A.** 后台车场配置

停车场-编辑，彩惠人生抵扣金使用：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps112.jpg) 

默认为不选择，即该车场不支持使用彩惠抵扣金缴停车费。需要开通时请勾选。

当前月卡和临停都支持使用抵扣金。

**B.** 用户使用说明

**a)** 使用说明

彩之云APP用户，且有彩惠抵扣金。

当用户的抵扣金金额≥停车费用时，用户进行月卡/临停缴费时，能选择彩惠抵扣金进行全额抵扣停车费。

**b)** 使用步骤

彩之云APP→停车→月卡/临停缴费→选择彩惠抵扣金→确认抵扣→支付成功

支付成功后，月卡自动续费，临停请在10分钟内出场。

点击“彩惠抵扣金”后面的感叹号，能弹出抵扣说明。

用户的抵扣金足够时，才能出现抵扣选项。不选择，即不使用抵扣金，走普通支付流程。选择时，即使用抵扣金下单，对应彩惠抵扣金账户将会支出相应金额。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps113.jpg)   ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps114.png)

也能从彩惠抵扣金页面跳转到停车缴费页面：

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps115.jpg)   ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps116.jpg)

**C.** 账单查看

后台-订单-交易订单，筛选来源“全额抵扣”，即为彩惠抵扣金使用订单。

请财务同学线下和彩惠相关负责人进行结算。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps117.jpg) 

 

### **2.4** 优惠券

优惠券的实质是临停费用。

商户给客户发放优惠券，相当于帮客户付临停费用。

目前支持两种优惠券：定额券和不定额券。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps118.jpg) 

#### **2.4.1** 定额券

定额券，目前都为金额减免券。

有需求的商户和项目人员沟通好→发起审批（优惠类型（例金额减免5元）、购买条件（以多少钱的价格买面值多少钱的优惠券）、限制条件（购买限制、发放限制）、管理优惠券的人员和手机号码等信息）→审批通过→运营人员在后台配置商户信息。

1） 添加商家

后台——优惠券——商家——添加商家——填写商家信息——提交

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps119.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps120.jpg) 

商家名称：填写商家名称

手机号：商家管理员的手机号

地址：几栋几楼几号商铺，尽量写详细

停车场：商户所在的停车场

是否限制领取数量：是，表示限制，每辆车只能有一张未使用的优惠券；否，表示不限制

券额类型：定额券

领券后失效时间：XX小时，领券后XX小时内不使用会变为过期状态

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps121.jpg) 

2） 添加授权

同一商户可以有多个发券人，第一个手机号的人为超级管理员，其余为普通管理员。

超级管理员有授权和关闭授权的权限，普通管理员没有。其他功能相同。

后台——优惠券——商家授权——增加授权——填写授权信息

同一手机号只能绑定一个商户，再绑定时会提示“该手机号已绑定别的商户”，需要换商户时，请先删除之前的授权，再添加授权

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps122.jpg) 

3） 配置优惠券

查看是否已经有需要的优惠券类型，若没有，请先添加。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps123.jpg) 

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps124.jpg) 

 

如果已经有了，可以直接购买设置，操作如下：

点击平台：优惠券——待购买——购买生成——添加商户所购买优惠券详情——提交

设置完成后，商家就能自行购买发放优惠券了。

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps125.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps126.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps127.jpg) 

4） 查看记录

优惠券订单：商家购买优惠券后的购买记录。

支持停车场、订单号、下单时间等筛选，也支持筛选结果导出。

查看批次，查看该购买批次里，商户给车主的发券记录

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps128.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps129.jpg) 

优惠列表：查看所有车辆的发券用券情况

筛选结果支持导出。

状态有三种：未领取，优惠券还在商户手上；已领取：优惠券发给车主了，还未使用；已使用，车主使用优惠券后。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps130.jpg) 

5） 优惠券创建方式

上面购买的优惠券，创建方式为商户购买；

因为一些特殊原因（比如车位租赁合约等），需要直接从后台给商户发券，则创建方式为：后台分配。

操作流程：优惠券列表——批量生成

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps131.jpg) 

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps132.jpg) 

6） 优惠券限制

购买限制：某些商户的购买价格比较低，需要限制每月购买数量。

发券限制：某些商户有需求，每天限制使用多少张券，用完后就不发了。

优惠券——优惠券限制——增加限制———购买/发券限制——确定

时间周期：日、周、月

数量：填写限制的张数

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps133.jpg) 

#### **2.4.2** 不定额券

1） 添加商户

优惠券——商家——添加商家——填写商家信息——不定额券——提交

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps134.jpg) 

A. 商户有需要，可以限制最大面值，即最大发券金额。比如，设置为10元，那么当车辆临停费用≥10元时，只发10元的券；

B. 设置好不定额商户后，使用的优惠券类型固定为“放行券”，发券后车主15分钟内出场，超时可能需要支付剩余费用才能出场；

C. 不定额券商户，不涉及到买券行为。如果需要购买，可以让项目管理员走线下/日报上缴等途径进行；

D. 优惠券授权，支持同一个商家有多个发券人。

2） 优惠券限制

不定额商户，没有限制时，可以一直发券。需要限制时，可以限制日/周/月的发放总额。当额度用完时，不能继续发券。

优惠券——优惠券限制——增加限制——填写商家限制信息——确认

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps135.jpg) 

#### **2.4.3** 优惠券预出场配置

1) 停车场优惠券用券逻辑：

| 商家   | 默认/禁用预出场         | 启用预出场                       |
| ------ | ----------------------- | -------------------------------- |
| 定额   | 发券时用券              | 预出场时用券，多张定额券自动叠加 |
| 不定额 | 发券时用券（0元无意义） | 预出场时用券，0元也使用          |

2) 配置：后台——优惠券——优惠券预出场配置——添加/编辑

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps136.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps137.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps138.jpg) 

开启预出场

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps139.jpg) 

禁用预出场

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps140.jpg) 

#### **2.4.4** 商户端

**1）** APP端-定额券

位置：APP新界面，右上角，个人中心，角色切换到“我是商家”![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps141.png)

**A.** 发券

优惠券领券类型三种：商户发券、用户扫码、活动扫码等。

商户发券：

商户选择优惠券类型→输入车牌号→发券

输入车牌号后，会查询车辆是否在场，在场的车辆才能领券；

查到并显示车辆进场时间及当前计费；

已发券提示：提醒该用户已经有该商户的券额，避免多发；

当商户有多种券时，优惠券类型会自动匹配一个优惠券面额≥临停费用；只有一种券就默认为该券类型；

商户发券成功后会提示“发券成功”。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps142.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps143.png)

用户扫码：

车主微信扫描下方商户页面的二维码，进入优惠券领取页面领取

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps144.png)

 

**B.** 购买

选择需要购买的优惠券类型→购买→确认是否为该停车场→输入购买张数→确认金额→支付

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps145.png)

 

**C.** 历史

购买历史记录：查看历史买券情况和当前用券情况。数量为购买数量；已用为发券数量。

使用历史记录：可以查看给哪些车发了优惠券

后台分配历史记录：可以查看后台分配批次的用券情况

**2）** 


![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps146.png)

 

**D.** APP端优惠券授权

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps147.png)

商户超级管理员有授权和关闭授权的权限，普通管理员没有。

输入被授权人手机号——授权

**E.** APP端发券限制

发券限制：商户自己设置每日/周/月的发券张数。

限制列表：查看已设置发券限制情况，可以修改或删除限制

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps148.png)

**3）** APP端-不定额券

**A.** 发券

同样支持商户输入手机号发券和车主扫码领券两种方式。

APP——我是商家——优惠券——发券

a) 输入车牌号后，自动查询车辆当前临停信息；

b) 根据当前临停计费，直接发券；

c) 如果设置了总额限制，可以看到当前使用情况：总额、余额。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps149.jpg) 

**B.** 查看发券历史记录

APP——我是商家——优惠券——历史

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps150.png) 

**C.** 优惠券授权（同定额券一样）

放行券不用设置发券限制。

**4）** 商户后台

商户可以使用PC或pad登录优惠券商户后台进行操作。

登录地址：https://biz.aparcar.cn/

登录方式：可以用OA账号或私有账号+密码，或者用手机号+短信验证码登录。

**A.** 发券

商户选择优惠券类型→输入车牌号→发券

输入车牌号后，会查询车辆是否在场，在场的车辆才能领券

查到并显示车辆进场时间及当前计费

定额券的可以选优惠券类型，不定额券优惠券类型为放行券（有总额限制的提示了总额和余额）

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps151.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps152.jpg) 

**B.** 我的优惠券

筛选查看所有车辆的发券用券情况，能查看优惠券已发券面额总计。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps153.jpg) 

**C.** 优惠券购买和订单列表

查看优惠券类型及详细情况，能直接购买。

购买→输入购买数量→生成付款码→扫码付款→支付成功

订单列表，查看购买历史记录。

不定额优惠券商户不需要购买，查看订单数据也没数据。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps154.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps155.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps156.jpg) 

**D.** 优惠券授权

商户超级管理员有授权和关闭授权的权限，普通管理员没有。

增加授权——输入被授权人手机号——授权

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps157.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps158.jpg) 

**E.** 优惠券限制

定额优惠券商户能查看优惠券购买限制，设置发券限制。

增加限制———购买/发券限制——确定·

不定额优惠券商户能查看总额限制及使用情况。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps159.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps160.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps161.jpg) 

**F.** 优惠券活动

定额券商户能查看优惠券购买限制，设置发券限制。

商家做活动，需要在活动海报上面放固定领券二维码时，可使用优惠券活动功能。

商户后台——活动页面——创建活动——活动二维码——下载

车主扫码领券，对应领券方式为：活动扫码。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps162.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps163.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps164.jpg) 

**G.** 优惠券图表

优惠券图表，能筛选查看时间及使用情况。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps165.jpg) 

 

### **2.5** 车位锁

车位锁是一种安装在地面车位上的机械装置，也叫地锁，能防止别人抢占车位。

车位锁安装后，配置到系统中，用户能操作车位锁。

车位锁共享，目前尝试了免费共享、付费共享等。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps166.jpg) 

#### **2.5.1** 车位锁配置

目的：运营人员在后台配置车位锁相关信息，调通，为用户授权。

准备：安装车位锁后，

1） 收集好改车位锁的详细信息，包括停车场、厂商、硬件编码、易停编码、蓝牙广播编码、车位等。

2） 收集好用户信息，手机号等。

操作：

**A.** 添加车位锁

导航栏——车位锁列表——添加——填入车位锁信息——生成

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps167.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps168.jpg) 

**B.** 用户授权

车位锁列表——授权——填入使用人手机号——生成

角色：管理员，停车场管理员，在该车场任意车位锁后授权，能操作所有车位锁；产权人，购买该车位的车主，能操作该车位对应车位锁升起/下降权限；共享人，车位锁非产权人使用者，能操作该车位对应车位锁升起/下降权限。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps169.jpg) 

 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps170.jpg) 

**C.** 测试

添加车位锁，用户授权完成后，请车场管理员或产权人现场测试一下车位锁，升降操作是有效。 

**D.** 车位锁授权列表查看

车位锁→车位锁授权，可以查看或修改授权记录：更改身份或禁用/状态。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps171.jpg) 

**E.** 车位锁操作记录查看

车位锁→车位锁记录，可以查看车位锁操作记录。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps172.jpg) 

#### **2.5.2** 车位锁用户使用

车位锁配置好后，用户就能控制车位锁了。

方法一：彩之云首页底部，扫一扫车位锁上的二维码→点击车位锁图标

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps173.png)

方法二：车位锁卡片，降下/升起

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps174.png)

方法三：个人中心——车位锁——输入车位锁编码——升起/降下

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps175.png)

说明：

车位锁上面标明了车位编号，如“00190014”。

当别人在使用该车位锁时，（车位锁为降下状态，且不是你降下的），你将不能操作该车位锁。

停车前，彩之云操作降下车位锁，停在车位上。

驶出车位后，请及时升起车位锁，以防车位被占。

### **2.6** 车位锁共享

#### **2.6.1** 免费共享

车位锁产权人能免费共享给同车场月卡车辆。

APP——车位锁共享——授权

选择车位锁→输入月卡车牌号→选择授权时间段→共享

共享成功后，能查看授权列表。

共享人（被授权人）能扫码控制车位锁。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps176.png)

 

后台能查看免费共享记录。

后台——车位锁——免费共享

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps177.jpg) 

#### **2.6.2** 付费共享

使用场景：

车辆进入车场后，看到有空车位上装有共享的车位锁 ，且处于未使用（升起）状态。

扫面旁边柱子上的预约二维码，输入选定的车位号，确认预约，交50元押金。

付款成功后，车位锁降下，车主停车在对应车位上。

车主驶离车位，进入车位锁界面，点击车位锁“停止使用”，升起车位锁，原路退回押金。

车主正常临停/月卡出场。

用户操作：

停车：用户扫码→输入车位号→降锁付押金→停车

出场：升锁→自动退押金→出场

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps178.png) ![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps179.jpg)

车位锁——预约共享订单，能在后台能查看订单情况

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps180.jpg) 

#### **2.6.3** 付费预约进场	

背景：某些车场，不允许外来车辆入内，需要预约后才能停车。

操作步骤：

扫描停车场预约进场二维码，进入预约界面→确认车场、车牌号、预约时间段、付费→预约成功

付费=预约固定金额（5元）+预付临停费用

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps181.png)

查看记录：

车位锁——虚拟共享订单

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps182.jpg) 

车位锁——虚拟共享列表

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps183.jpg) 

### **2.7** 审批功能

EP停车审批功能，用于EP停车后台相关审批。

功能包括：新建审批流程、发起审批、批阅审批等。

操作步骤:

#### **2.7.1** 审批流程

位置：后台——导航栏——审批——审批流程

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps184.jpg) 

**1)** 查看审批进度

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps185.jpg) 

查看已经发起的审批进度。状态包括，未发起，审批中，已通过，已拒绝。

未发起，新建审批后，没点发布时，相当于保存，还没到审批人那里；

审批中，发起后，一级一级往下审批，最后一级审批同意之前都为审批中；

已通过，最后一级审批通过后，审批流程走完，状态变为已通过；

已拒绝，任一级审批拒绝后，不能向下进行，状态变为已拒绝。

**2)** 新建审批流程

管理人员可以新建审批流程。

位置：右上角——添加

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps186.jpg) 

审批名称：可根据审批功能等命名；

审批人：取自管理员列表，请填写审批人OA或私有账号名称，支持模糊搜索。多级审批时，多次添加审批人即可，可直接删除某级审批人。

执行人：有需要执行人的流程，填写此项。没有的，可不填。

附件：支持各类型文件上传，文件大小限制在5M内，总数不超过5个。

备注说明：可以说明一下该审批流程使用的范围和要求等。

#### **2.7.2** 发起审批

位置：后台——导航栏——审批——创建审批

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps187.jpg) 

**1)** 查看审批流程

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps188.jpg) 

查看已有的审批流程信息，包括审批名称，审批人（多级审批为多人），执行人，状态（禁用、启用）、备注、附件（下拉查看）等。

管理员可以在操作中删除审批流程或修改流程状态。

**2)** 发起审批

使用人员可以发起审批。

位置：右上角——添加

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps189.jpg) 

审批主题：可根据目的等命名；

流程：选择已有的审批流程；

附件：支持各类型文件上传，文件大小限制在5M内，总数不超过5个。

内容：根据审批要求，说明审批内容。

 

注意：提交后确认无误，点“发布”，发起审批。

未发起时，没有发起人和时间。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps190.jpg) 

#### **2.7.3** 批阅审批

位置：后台——导航栏——审批——我的审批

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps191.jpg) 

**1)** 查看我的审批

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps192.jpg) 

可根据状态查询我的审批，未审批，已通过，已拒绝。

点击后面操作里面的查阅，可查看审批详细信息。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps193.jpg) 

 

**2)** 发起审批

当审批到达某级审批人时，他能看到对应审批，并点“查看”进行批阅。

可以同意或拒绝，同意后传到下级审批，拒绝后审批终止。

支持上传附件和备注说明。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps194.jpg) 

### **2.8** 运维管理

#### **2.8.1** 停车场进度

1) 验收查看

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps195.jpg) 

2) 易停项目进度

 

#### **2.8.2** 掉线数据

 

### **2.9** 报表及导出

#### **2.9.1** 欢迎页面

查看车场基本数据：停车场收入、进出场开闸统计及用户数据等

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps196.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps197.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps198.jpg) 

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps199.jpg) 

#### **2.9.2** 车场报表

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps200.jpg) 

2.月卡比对

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps201.jpg) 

默认为所有易停车场的月卡收入，可左右拉动滑条查看；

可选择大区、事业部进行查看；

默认月份为11月和10月，可选择月份查看和前月；

可切换成月卡总数的对比。

下面为数据列表

A. 月卡趋势

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps202.jpg) 

 

车场的月卡统计：左图为某车场不同规则的收入和数量，右图为该车场的月卡总收入和总月卡数（一整年，12月为预交月卡费用）；

左上角可以输入想要查看的停车场

下面为数据列表

B. 车场掉线（可选择演示）

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps203.jpg) 

易停车场掉线情况分析，次数：每五分钟查询一次，若掉线，就＋1，今日（从零点开始）掉线次数累计值。

点击柱状图，查看掉线明细，能进行实时监控。

C. 收入报表

查看某车场，某月份的收入情况，同一月的应收和实收对比。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps204.jpg) 

 

#### **2.9.3** 数据导出

停车场支持导出数据：交易订单、日报订单、续费订单、收入报表、月卡、进场数据、出场数据、异常开闸、车场掉线等。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps205.jpg) 

根据不同需求可以导出停车场文件、事业部文件、大区文件、集团文件。

除了月卡外，导出数据文件是提前生成的，直接下载便可。

#### **2.9.4** 大屏幕

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps206.png) 

**1)** 首页数据

数据实时更新。

 

A. 今日数据：从零点开始，进出易停车场的车辆数据，包括：

a) 进出车次：进出一次算一次，累计车辆进出的次数

b) 进出车辆：进出车场的不同车辆数目累计

B. 不同城市历史收入数据总和：分成了五段，可点击不同颜色方块查看。

C. 实时进出场车辆明细

D. 实时进出场车辆照片

### **2.10** 权限管理

#### **2.10.1** 后台权限

后台权限是由角色的功能权限+所属的区域权限确定。

1） 角色权限

角色权限：根据不同的角色控制对应功能权限。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps207.jpg) 

2） 用户授权

后台——管理员——添加

OA账号：目前连通了彩生活集团OA系统，登录账号密码为OA账号密码。

私有账号：非彩生活用户权限开通，用私有账号密码开通。

区域权限：事业部和停车场确定区域权限。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps208.jpg) 

#### **2.10.2** 车辆及会员

车辆，EP停车系统车辆数据库，可以添加车辆。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps209.jpg) 

会员，EP停车系统车主用户数据库，可以添加/编辑会员信息。

![img](https://ep-1256130579.cos.ap-guangzhou.myqcloud.com/pro_doc/EP-Parking%20system/wps210.jpg) 