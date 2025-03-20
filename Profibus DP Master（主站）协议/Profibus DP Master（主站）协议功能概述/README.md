# Profibus DP Master（主站）协议功能概述

Beacon Global Technology的Profibus DP Master系列通讯网关模块可以支持多种设备在 EtherNet/IP、Modbus TCP、Modbus RTU、Siemens 工业以太网、IEC60870-5-104 等协议与 Profibus DP 网络中的数据交换，最大支持 20,000个字节数据交换区（型号不同数据区有所区别）。

Profibus DP主站可以进行通讯的设备有西门子各类PLC，变频器，仪表和有Profibus DP从站协议的设备，支持V0和V1。模块提供一个 Profibus DP 串行端口，可以通过串行接口对Profibus DP网络进行组态和配置。

| <div style="width: 150pt">Profibus-DP主站规约： |                                                              |
| ----------------------------------------------- | ------------------------------------------------------------ |
| DP网络数据量                                    | 支持1500个字节输入，1500个字节输出                           |
| 支持Profibus-DP主站功能                         | 支持  Profibus-DP V0、V1 版本主站   支持冻结模式   支持同步模式   支持通讯速度自动匹配配置   可对连续数据交换或者非循环数据交换进行监控和调整    支持Profibus-DP多主站模式    在线监控Profibus-DP从站工作状态    支持CRC校验 |
| 可配置通信参数                                  | 波特率：  9.6 kbit/s – 12 Mbit/s   支持高低位字节交换   PROFIBUS 链接丢失状态查询   通讯失败暂停时间参数 |
| 连接从站数量                                    | 1至25                                                        |
| 从站GSD文件                                     | 可通过拖拽方式将 Profibus-DP 从站 GSD 文件导入到配置软件中   |

 
