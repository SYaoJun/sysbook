## Linux命令

```sh
export PATH=/Users/yaojun/MyInstall/pg_install/bin:$PATH 
```
## 查看端口
```shell
lsof -i:8080
```
## 查看进程下的线程
```shell
top -H -p 12345
```
## readelf
```shell
readelf -h a.out
```
## 分配权限
```shell
chown yaojun:yaojun /data/yaojun -R
du -sh ./* 查看目录和文件磁盘使用情况
du -sh * |sort -rh  从大到小排序
```
## 查看二进制文件执行的系统调用
```shell
strace ./a.out
```
