---
title: 运维日志 2020/03/07
tags: 日志
article_header:
  type: cover
  image:
    src: /screenshot.jpg
---


## 更新gem source


```sh
# 添加 TUNA 源并移除默认源
gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/
# 列出已有源
gem sources -l
# 应该只有 TUNA 

```
[Ruby Gems 镜像使用帮助][1]


[1]: https://gems.ruby-china.com/


## 卸载rvm重新安装在 zhumeng用户目录下

- 卸载
```
 rvm  implode
```