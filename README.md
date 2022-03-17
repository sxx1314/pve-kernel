# pve-kernel

## 自用pve-kernel 
- 修复支持了 NAT1 / FULLCONE-NAT  感谢：[@Chion82](https://github.com/Chion82/netfilter-full-cone-nat)
- linux kernel version :5.15.27-1  感谢：[@ubuntu-jammy](https://code.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/jammy) [@pve-kernel](https://github.com/proxmox/pve-kernel)
- 添加ppp拨号组件
- 添加i225等驱动

## INSTALL
```
git clone https://github.com/sxx1314/pve-kernel
cd pve-kernel
dpkg -i *.deb
```
