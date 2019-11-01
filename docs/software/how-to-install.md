# 如何安装nch

## 最新版本

当前最新的内测版本为 v1.0.0

## 服务器配置

推荐的服务器配置：

* CPU 核数： 2
* 内存： 4GB
* 磁盘：100GB SSD
* 操作系统： Ubuntu 16.04+
* 带宽：10Mbps
* 开放端口： 26656和26657

## 安装

### 1. 安装并配置go

安装和配置go，请点击[这里](../software/go-install.md)

### 2. 源码编译nch节点程序

```shell
# 获取nch 源码
git clone https://github.com/NetCloth/netcloth-chain.git
cd netcloth-chain && git checkout v1.0.0

# 编译安装
make install

# 编译完成后，检查版本号
nchd version
nchcli version
```