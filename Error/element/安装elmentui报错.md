#### 安装elmentui报错

错误图：

![](img/安装element出错1.png)

原因：

版本过高。

解决：

1. 降低版本。
2. 使用命令  `npm install (xxxx) --legacy-peer-deps `  做出彻底的决定，不安装任何前版本的依赖。
3. 使用命令 `npm install -g npm@6.14.8` 降低npm的版本

