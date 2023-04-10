# awk 的实战用例

> AWK 入门文章：(AWK 简明教程)[https://coolshell.cn/articles/9070.html]

## 过滤出文件中没有被`#`或`;`注释的语句
```bash
# 过滤出 redis.conf 文件中没有被`#`注释的语句
awk '$1 ~ /^[^#]/' redis.conf
```
```bash
# 过滤出 example.conf 文件中没有被`;`注释的语句
awk '$1 ~ /^[^;]/' example.conf
```

## 输出给定文件中第 n 行到行尾的内容
```bash
# 输出从第 8 行到结尾的内容
awk '{for(i=8;i<=NF;i++) printf "%s ",$i; print ""}' filename.txt
```

## 对指定行进行求和并输出到控制台
```bash
# 对第 7 行的数据进行求和
awk '{sum+=$7} END {print sum}' filename.txt
```

