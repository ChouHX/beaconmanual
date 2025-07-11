# DF1协议模块功能概述

Beacon Global Technology 的新型 DF1系列通讯网关模块，可以将多种工业协议统一转化为 DF1协议进行通讯。

| <div style="width: 150pt">DF1规约 |                                                              |
| --------------------------------- | ------------------------------------------------------------ |
| 支持DF1主站功能                   | 采用主站指令控制时，支持全双工模式，采用轮询方式时，支持半双工模式  单独指令内容包括：从站地址，内存区地址信息，字或者位进行数据交换 |
| 支持DF1主站数量                   | 根据不同型号可选择 1-4 个                                    |
| DF1命令数量                       | 每个主站端口最多支持 128 条命令                              |
| 命令列表轮询                      | 可单独启用或禁用每条命令；可采用连续进行方式，数据更改时仅允许写入 |
| 支持DF1从站功能                   | 端口配置为从站模式时可以接受 DF1 主站设备的读写指令   DF1 做从站可以支持全双工，作为被轮询时支持半双工    每个从站端口可配置的内容包括：   数据报文的起始地址   数据报文的数据长度   数据报文对应内部数据区的地址 |
| 可配置串口通信参数                | 奇偶校验：无、偶校验、奇校验   数据大小：  8 位   停止位：1  RTS 开/关延时：0 至 65535 ms   CRC 和 BCC  方式 错误校验 |
| DF1节点地址                       | 0 至 255  (可通过软件选择)                                   |
| RS接口选择                        | 软件配置  RS232、RS422 和 RS485                              |
