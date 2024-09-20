# Adguard Home 折腾手记

## 介绍
Adguard Home 服务器的安装以及折腾手记。

- Adguard Home 适用版本：v0.107.32

- 演示机：
    - 虚拟化：Proxmox VE
    - 宿主系统：Debian 12
    - CPU：host
    - 内存：2GB
    - 网卡：VirtIO
    - SCSI 控制器：VirtIO SCSI Single

- 内部网络：
    - IPv4 网络
        - IP 地址：`172.16.1.2`
        - 子网掩码：`255.255.255.0` ( 即 `/24` )
        - 网关：`172.16.1.1`
    - IPv6 网络
        - 首选 `SLAAC` 自动配置
        - IPv6 ULA 网络使用 `fdac::/64` 作为演示


### 系列章节

0.  [Adguard Home 初始化设置](./00.AGH初始化设置.md)  
1.  [Adguard Home 功能设置](./01.AGH功能设置.md)  
2.  [Adguard Home 拦截清单收集](./02.AGH拦截清单收集.md)  

### 文章说明

1.  本系列文章涉及的部分参数需要手动调整来符合切实使用需求。
2.  随着 Adguard Home 的迭代更新，截图中的内容和实际页面显示可能存在差异。
3.  如需引用，请注明本文出处。

