# LRani-Linux
## 一个强兼alpine的Linux
-----------
### - 📱主要特征
#### 1. 使用 **apk** 包管理器，轻量 · 简单  · 快速
#### 2. 已配置的国内软件源
#### 3. 最新 *最稳定* 的 Linux 版本
#### 4. 精简的文件系统（镜像包1G,实际占用在200MB左右）
#### 5. 虽然精简但网络驱动完全
#### 6. 我编不下去了
### - 🚫缺点
#### 1. 没有图形界面
#### 2. 没有完整驱动（有1G多的驱动源代码你相信？？？）
#### 3. 我又编不下去了
### - 🧱构建教程
#### 1. 你需要完整的开发环境，输入命令
######Debain / Ubuntu / Other
```shell
sudo apt update
sudo apt install build-essential openssl
sudo apt install zlibc minizip
sudo apt install libidn11-dev libidn11
sudo apt install libncurses*
```
#### 2. 下载[Linux内核源码（点我）](https://kernel.org "Linux内核源码")
#### 3. 构建内核：
```shell
make defconfig -j2
make -j4
```
######  “ -j ” 后面的数字是你cpu的核心数，决定使用多少核心编译，越多越快，但其他应用就越卡
#### 4.构建根目录和busybox
###### 懒得写了，自己去看  [网页链接 不要戳我喵～](https://zhuanlan.zhihu.com/p/637951209 "网页链接 不要戳我喵～")
#### 5. 安装apk包管理器
###### *我要累死了，教你个办法吧，[点我获得一对一问答](https://chat.deepseek.com)*
### - ⬇️直接安装
#### 1. 下载文件[戳我](https://github.com/Little-Rani/LRani-Linux/releases/tag/v0.0.1 "戳我")
#### 2. 安装依赖
```shell
sudo apt update
sudo apt install qemu-system
sudo apt install p7zip
```
#### 3. 解压文件
> 7z LRani.7z

#### 4. 运行命令
> ./start.sh

### - 🧑‍🤝‍🧑加入我们
##### 作者QQ 3679702858
##### 欢迎前来贡献！感谢你的贡献！
