# shell
减少在命令行中频繁的输入重复的命令，提高工作效率。
shell脚本
- 正月点灯笼
- 赋值符号两边不要空格
- 运算符两边一定要有空格
- 乘号要转义\*
- 左右圆括号要加转义\(
```shell
a=5
b=10
c=`expr $a + $b`
echo $c
```
- 乘法
```shell
a=5
b=10
c=`expr $a \* $b`
echo $c
```
- 条件语句
```
b=10

if [ $a -gt 5 ]
then
  echo $a
else
  echo $b
fi
```
- 比较符号
```shell
-gt  >
-lt <
-ge >=
-le <=
-eq =
```
- for循环
```shell
for x in 1 2 3 4 5
do
  echo $x
done

// 简化
for x in {1..10}
do
  echo $x
done
```
- while循环

```shell
x=1
while [ $x -lt 10 ]
do
  echo $x
  x=`expr $x + 1`
done
```