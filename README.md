# pve-kernel

### 5.15.x:kernel 5.15.x 
### 5.17.x:kernel 5.17.x
### 5.18.x:kernel 5.18.x
### 5.19.x:kernel 5.19.x
## 自用pve-kernel 
- 修复了 NAT1 / FULLCONE-NAT 在 5.15/5.17/5.18/5.19 kernel上失效问题。  原项目：[@Chion82](https://github.com/Chion82/netfilter-full-cone-nat)
- linux kernel version :5.15/5.17/5.18/5.19  感谢：[@ubuntu-jammy](https://code.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/jammy) [@pve-kernel](https://github.com/proxmox/pve-kernel) [@fabianishere](https://github.com/fabianishere/pve-edge-kernel)
- 添加ppp拨号组件
- 添加i225等驱动
- 开启了 io_uring+zerocopy支持
- 开启了FLOW_OFFLOAD 支持

## INSTALL
```
git clone --depth=1 https://github.com/sxx1314/pve-kernel
cd pve-kernel
dpkg -i *.deb
#注意最好直接下载Releases 解压安装，以后可能不会再把deb直接放在仓库里，因为会导致仓库容量暴增，除非我做仓库瘦身。
```
