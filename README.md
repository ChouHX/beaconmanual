# 配置Profinet Server (从站)

在模块主页面中点击 “Profinet IO Device**”**，在下拉菜单中点击Configuration设置Profinet的I/O配置。

<img src="assets/图片1.png" style="zoom:50%;" />

**Swap Input Data Mode:** 输入数据是否高低位转换

**Swap Output Data Mode:** 输出数据是否高低位转换

**Clear Database Offine:** 选择当Profinet通讯中断时是否清除最后传过来的数据

**Input Buffer Size:** 输入数据大小（最大为1440byte）

**Output Buffer Size:** 输出数据大小（最大为1440byte）

**Input Buffer Offset In Database:**  输入数据在模块内部的起始地址（图中表示PROFINET主站读取模块的输入数据，将从地址2500开始。）

**Output Buffer Offset In Database:** 输出数据在模块内部的起始地址（图中表示PROFINET主站写入模块的输出数据，将从地址0开始。）

**Access Interval:** 交换数据的时间间隔（初始为100ms，建议设置为5ms）



配置I/0内容，设置好后，点击Save，再点击OK,模块重启后配置生效。

<img src="assets/图片2.png" style="zoom:50%;" />
