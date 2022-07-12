# GT06 客户端功能

## 修订历史

| Version |   Date     |   Author   |   Change expression   |
| :------ | ---------- | ---------- | --------------------- |
| 1.0.0   | 2022-07-12 | 孙健       | 初始版本               |

## GT06 介绍

### 功能概述

该项目实现了GT06协议**客户端**功能, 用户可直接使用该功能与对应服务端进行标准内的数据交互。

### 主要功能

- 服务器连接
- 终端登录
- 终端GPS&LBS定位信息上报
- 终端设备状态信息上报
- 服务端指令下发与应答

### 备注

GT06协议规定的消息较少, 该项目只实现了基础的消息功能, 不同的服务平台自定义的消息需要进行二次开发, 扩展的消息也需要进行接口调整。