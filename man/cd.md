# cd 命令
---
## 简介
cd是change directory的简写，功能是在不同目录间进行切换。

## 语法
cd [参数]

## 选项
无

## 参数
- ` `： 省略时默认切换到当前用户的家目录。root用户是在/root/，普通用户是在/home/username/。   
- `~`： 切换到家目录，和省略效果相同。    
- `-`：切换到上一次所在目录。只能在两个目录间切换，彼此为自己的上一次。   
- `.`：切换到当前目录，就是没有切换。   
- `..`:切换到上一级目录，即父目录。   
- `/var/www/hmtl/`:绝对路径。切换到指定目录。    
- `etc/sysconfig/`:相对路径。切换到指定目录。   