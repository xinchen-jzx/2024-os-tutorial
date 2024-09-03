# Lab0: 实验环境搭建

## 0.1 预备操作

官方源下载相关依赖项较慢，建议更换为清华源等国内源。
```bash
sudo apt-get update && sudo apt-get upgrade   # 更新软件列表
```

## 0.2 安装编译器和QEMU模拟器

```bash
# 安装工具链
sudo apt-get install git build-essential gdb-multiarch qemu-system-misc gcc-riscv64-linux-gnu binutils-riscv64-linux-gnu
```

## 0.3 下载实验框架代码

```bash
# 克隆代码
git clone https://gitee.com/xinchen-boom/os-labs-2024.git

# 切换分支，如果发现为空不要紧张！切换git分支即可
git checkout <branch-name>
```