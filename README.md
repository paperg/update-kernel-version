# update-kernel-version
update kernel version on Ubuntu20.04

## 1. 环境说明
 UBUNTU 20.04 更新内核 5.18.8
 
## 2. 安装依赖
```
sudo apt install build-essential libelf-dev libncurses-dev flex bison
```

## 3. 开始编译

### 3.1  解压内核到任意地方，并进入目录
### 3.2 
```
make mnuconfig
```
