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

