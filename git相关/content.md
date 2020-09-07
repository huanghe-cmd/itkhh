[TOC]

# Tip

## 1.城市轨道交通基于通信的列车控制系统（CBTC）互联互通系统规范

communication based on control（CBTC）：基于通信的列车控制：通过不依赖轨旁列车占用检测设备的列车主动定位技术，连续车-地双向数据通信技术以及能够执行安全功能的车载和地面处理器而构建的连续式列车自动控制系统。城市轨道交通基于通信的列车运行控制系统（CBTC)互联互通是指装备不同信号厂家车载设备的列车可以在装备不同信号厂家轨旁设备的一条轨道交通线路内或多条轨道交通线路上无缝互通安全可靠运营。

###### 1.术语

main line(正线)：载客列车运营贯穿全程的线路。

列车自动控制 （automatic train control):信号系统自动实现列车监控、安全防护和运行控制等技术的总称。

列车自动监控（automatic train supervision)：根据列车时刻表为列车运行自动设定进路，指挥行车，实施列车运行管理等技术的总称。

列车自动防护（automatic train protection)：自动实现列车运行间隔、超速防护、进路安全和车门等监控技术的总称。

计算机联锁（computer inter locking):以计算机技术为核心，自动实现进路、道岔、信号机等防护技术的总称。

移动授权（moventment authority):列车沿给定的行驶方向进入并在某一特定轨道区段行车的许可。

危险点（danger point):列车运行前方不允许列车任何部位越过的特定点。

###### 2.缩略语

AM：列车自动驾驶模式（Automatic Train Operating Mode）

ATC：列车自动控制（Automatic Train Control）

ATO：列车自动运行（Automatic Train Operation）

ATP：列车自动防护（Automatic Train Protection）

ATS：列车自动监控（Automatic Train Supervision）

BTM：应答器传输模块（Balise Transfer Module）

CBTC：基于通信的列车控制（Communication Based Train Control）

CI：计算机联锁（Computer Interlocking）

CM：列车自动防护模式（Coded Train Operating Mode）

DCS：数据通信系统（Data Communication System）

EUM：非限制人工驾驶模式（Emergency Unrestricted Train Operating Mode）

LEU：轨旁电子单元（Lineside Electronic Unit）

MA：移动授权（Movement Authority）

MSS：维护支持子系统（Maintenance Support System）

MTBF：平均故障间隔时间（Mean Time Between Failures）

MTTR：平均修复时间（Mean Time To Repair）

PIS：乘客信息系统（Passenger Information System）

PSD：站台门（Platform Screen Door）

RM：限制人工驾驶模式（Restricted Train Operating Mode）

SIL：安全完整性等级（Safety Integrity Level）

TMS：列车管理系统（Train Management System）

TSR：临时限速（Temporary Speed Restriction）

UPS：不间断电源（Uninterruptible Power System）

ZC：区域控制器（Zone Controller）

###### 　3.准则

在工程实施过程中，对于新建线路网络，招标单位应根据线路条件，约定相关信号系统工程设计参数范围；对于既有互联互通线路延伸工程，招标单位应根据既有线路网络工程，设定信号系统工程设计参数范围。应预先约定的工程设计参数包括但不限于最小计轴区段长度、最小保护区段长度（在满足各个供货商的安全保护距离的条件下预留一定的余量）、运营间隔时间等。

CBTC系统应采用可靠、统一的无线通信系统作为车-地信息传输的透明传输通道，采用满足GB/T 24339.2-2009标准要求的网络传输安全防护技术；应采用可靠、统一的有线通信系统作为地-地信息传输的透明传输通道，采用满足GB/T 24339.1-2009标准要求的网络传输安全防护技术。

###### 4.系统要求

　1.CBTC系统应识别和防护的系统风险及对应的防护措施如下：

a)  列车冲突（追尾、侧冲、迎面冲突），该风险映射为列车间隔防护、退行防护、列车完整性防护、联锁安全进路功能；

b)  列车与轨旁设施（如车档等）相撞，该风险映射为轨道末端防护、进路限制防护；

c)  列车脱轨，该风险映射为列车超速防护、联锁安全进路防护等；

d)  与列车移动和列车车门及站台门相关的乘客人身风险，该风险映射为CBTC系统和列车车门及站台门系统接口防护、列车停稳检测、发车联锁。



2.CBTC系统的列车运行控制级别宜统一为：连续式列车控制级别、点式列车控制、联锁控制级别，并符合下列要求：

a)  连续式列车控制级别为CBTC系统的正常控制方式，基于移动闭塞原理，采用连续速度曲线控制方式，实时监督列车运行；

b)  点式列车控制级别为CBTC系统的降级控制方式，基于固定闭塞原理，采用一次模式速度曲线控制方式，实时监督列车运行；

c)  联锁控制级别为CBTC系统的降级控制方式，基于固定闭塞原理，司机根据轨旁信号机的显示行车。

3.CBTC系统中，列车应具有的驾驶模式包括：AM,CM,RM,EUM。

4.AM，CM为列车正常驾驶模式。

5.各驾驶模式满足转换条件可由人工转换，也可自动转换，车载设备应予以记录和显示。













## 2.BRaVE

data->file->map->

1.导入地图，进入编辑模式，生成路径长度，添加轨旁设备（信号机、计轴器、应答器）及其设备信息。

无源应答器（休眠唤醒固定应答器，固定应答器）

应答器（可变应答器，应答器环线，预告应答器）

校验应答器(轮径校验应答器)

2.添加坡度曲度信息。

3.添加站与站台。

4.公里标变更-》公里标。

5.信号机配置。

6.时刻表构建。

## 3.git

1.常用命令

git add:将本地文件增加到暂存区

git commit:将暂存区的内容 提交到 本地仓库（本地分支，默认master分支）

git push:将本地仓库内容 推送到 远程仓库（远程分支）

git pull：将远程仓库（远程分支）内容 拉取到 本地仓库（本地分支）

git branch :查看所有分支

git checkout xxx:切换分支到xxx

git checkout xxx -f：强制切换分支到xxx

git branch xxx：创建分支

git checkout -b xxx：创建并切换到xxx分支

git branch -d xxx：删除xxx分支

git branch -D xxx：强制删除xxx分支























