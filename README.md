# Adguard Home 折腾手记

## 介绍
Adguard Home 服务器的安装以及折腾手记。

- Adguard Home 适用版本：v0.107.12

- 演示机：
    - 虚拟化：Proxmox VE
    - CPU：host
    - 内存：2GB
    - 网卡：VirtIO
    - 磁盘：VirtIO SCSI Single

- 内部网络：
    - IPv4 网络
        - IP 地址：172.16.1.2
        - 子网掩码：255.255.255.0
    - IPv6 网络
        - 前缀：fc00::/60
        - 前缀长度：64
        - IP 地址：fc00::2


### 系列章节

0.  [Adguard Home 初始化设置](./0.ADH初始化设置.md)  
1.  [Adguard Home 功能设置](./1.ADH功能设置.md)  

### 文章说明

1.  本系列文章涉及的部分参数需要手动调整来符合切实使用需求。
2.  随着 Adguard Home 的迭代更新，截图中的内容和实际页面显示可能存在差异。
3.  如需引用，请注明本文出处。

