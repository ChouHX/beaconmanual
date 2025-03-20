# 配置Client（主站）与西门子1200&1500PLC通讯

1. 设置IP地址，与网关通讯设置成相同的网段。

<div align=center><img src="assets/clip_image002-1688021764122-3.jpg" alt="img" style="zoom:50%;" />
<div align=center><img src="assets/clip_image004-1688021764123-4.jpg" alt="img" style="zoom:50%;" />



2. 建立与网关通讯的DB块数据。点击添加新快，选择数据块（DB）

<div align=center><img src="assets/clip_image006.jpg" alt="img" style="zoom:50%;" />



3. 修改所建立的DB块的属性，建立数据之前或之后修改都可以，修改目的是要保证数据块(DB)1是带地址的背景数据块。

<div align=center><img src="assets/clip_image007.png" alt="img" style="zoom: 80%;" />



4. 点击属性后，把“优化的块访问”去掉勾选，默认是勾选的。

<div align=center><img src="assets/clip_image009.jpg" alt="img" style="zoom:50%;" />



5. 点击确定，会弹出是否更改，点击确定。

<div align=center><img src="assets/clip_image010.png" alt="img" style="zoom:67%;" />



6. 点击确定，去掉勾选项，然后确定数据块(DB)

<div align=center><img src="assets/clip_image012.jpg" alt="img" style="zoom:50%;" />



7. 西门子1200系列DB块通讯的数据量显示如下，各种类型可同时传输。可以对不同的DB块进行操作。数组或者是单个的变量都支持，以最终地址为准。

<div align=center><img src="assets/clip_image014.jpg" alt="img" style="zoom:50%;" />

8. 举例：

​     **布尔量**

<div align=center><img src="assets/clip_image002-1688106537865-1.jpg" alt="img" style="zoom:50%;" />

<div align=center><img src="assets/clip_image004.gif" alt="b9fc8d6a3a71864c7e0eb404faea67b" style="zoom: 33%;" />

<div align=center><img src="assets/clip_image006.gif" alt="ec7757878f57bd80c812e2ae577b39d" style="zoom:50%;" />

​    **字节**

<div align=center><img src="assets/clip_image002-1688106719599-5.jpg" alt="img" style="zoom:50%;" />

<div align=center><img src="assets/clip_image004-1688106719600-6.gif" alt="63d60b982a90957a7e4a537a8062d1d" style="zoom:33%;" />

<div align=center><img src="assets/clip_image006-1688106719600-7.gif" alt="6fd54192fa832c2e8e995e45c041788" style="zoom:50%;" />

​     **整数**

<div align=center><img src="assets/clip_image002-1688106847210-11.jpg" alt="img" style="zoom:50%;" />

<div align=center><img src="assets/clip_image004-1688106847210-12.gif" alt="2ad4c6e302a3fb6e16cf44e3431c347" style="zoom:33%;" />

<div align=center><img src="assets/clip_image006-1688106847214-13.gif" alt="e23d74897cb086f138ebceb123e596f" style="zoom:50%;" />

​     **实数**

<div align=center><img src="assets/clip_image002-1688106949387-17.jpg" alt="img" style="zoom:50%;" />

<div align=center><img src="assets/clip_image004-1688106949388-18.gif" alt="9e1071d28db5d80c61b7a41eee93ef9" style="zoom:33%;" />

<div align=center><img src="assets/clip_image006-1688106949389-19.gif" alt="9681f93b34e40ddc9d727dcc43409ad" style="zoom:50%;" />

 
