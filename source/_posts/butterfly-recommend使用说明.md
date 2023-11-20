---
title: butterfly_recommend 使用说明
recommend_index: 2
date: 2023-11-20 18:26:13
tags: hexo hexo-butterfly-plug
categories: 精选
---

## 说明
`butterfly_recommend` 是 `hexo-theme-butterfly` 主题的扩展，首页推荐组件

## 安装
```shell
npm i hexo-butterfly-recommend --save
```

## 默认配置
将以下配置添加到 `_config.butterfly.yml` 或 `_config.yml`。
```yml
recommend:
  enable: true #开关
  priority: 5 #过滤器优先权
  enable_page: / #应用页面 /是首页
  layout: # 挂载容器类型
    type: id
    name: content-inner
    index: 1
  banner: #banner
    title: 
```