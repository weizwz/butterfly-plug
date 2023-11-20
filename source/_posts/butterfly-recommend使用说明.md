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
      - '无限热爱'
      - '技术与生活'
      - 'WEIZWZ.COM'
    skill:
      - name: 'Html'
        icon: 'fa-brands fa-html5'
        color: '#fff'
        background: '#e9572b'
      - name: 'Css'
        icon: 'fa-brands fa-css3-alt'
        color: '#fff'
        background: '#2c51db'
      - name: 'Vue'
        icon: 'fa-brands fa-vuejs'
        color: '#fff'
        background: '#42b883'
      - name: 'Node'
        icon: 'fa-brands fa-node'
        color: '#7dbd05'
        background: '#37322e'
      - name: 'Git'
        icon: 'fa-brands fa-git-alt'
        color: '#fff'
        background: '#df5b40'
  category:
    - name: '必看精选'
      path: '/categories/精选/'
      icon: 'fa-solid fa-star'
      color: 
        - '#358bff'
        - '#15c6ff'
    - name: '热门文章'
      path: '/categories/热门/'
      icon: 'fa-solid fa-fire'
      color: 
        - '#f65'
        - '#ffbf37'
    - name: '优质资源'
      path: '/categories/资源/'
      icon: 'fa-solid fa-gem'
      color: 
        - '#18e7ae'
        - '#1eebeb'
```