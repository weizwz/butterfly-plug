# butterfly-plug
`hexo-theme-butterfly` 扩展插件调试模板，版本号随 `hexo-theme-butterfly` 更新。 

当前调试插件 
+ [hexo-butterfly-recommend](https://github.com/weizwz/hexo-butterfly-recommend)
+ [hexo-butterfly-navctrl](https://github.com/weizwz/hexo-butterfly-navctrl)

其他插件调试方法类似。

## `hexo-butterfly-recommend` 和 `hexo-butterfly-navctrl` 效果
`1920*1080` 

![banner](/source/img/demo1.png "banner") 

`width <= 1200` 

![banner](/source/img/demo2.png "banner") 

`移动端` 

<img src="https://github.com/weizwz/butterfly-plug/blob/main/source/img/demo3.png" width="430" alt="移动端效果"/><br/>

## 版本
+ `hexo` 7.0.0 
+ `hexo-theme-butterfly` 4.11.0 
+ `hexo-butterfly-recommend` 1.0.2
+ `hexo-butterfly-navctrl` 1.0.0

## 安装

```shell
npm i
```

## 引入本地插件

1. `npm init` 初始化本地插件（插件项目，非此项目，比如 `hexo-butterfly-recommend`）

2. 修改 `package.json`，示例
```json
{
  "name": "hexo-butterfly-recommend",
  "version": "1.0.0",
  "description": "hexo-theme-butterfly主题的扩展，首页推荐",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "directories": {
    "lib": "./lib"
  },
  "files": [
    "lib/",
    "index.js"
  ],
  "repository": {
    "type": "git",
    "url": "git+https://github.com/weizwz/hexo-butterfly-recommend.git"
  },
  "keywords": [
    "blog",
    "hexo",
    "butterfly",
    "theme-butterfly",
    "hexo-theme-butterfly",
    "recommend",
    "butterfly-recommend",
    "hexo-butterfly-recommend",
    "plugin"
  ],
  "dependencies": {
    "hexo-renderer-pug": "^3.0.0"
  },
  "author": "weizwz",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/weizwz/hexo-butterfly-recommend/issues"
  },
  "homepage": "https://github.com/weizwz/hexo-butterfly-recommend#readme"
}
```
3. 将插件目录拷贝至此项目的 `node_modules` 目录下

4. 在此项目 `package.json` 中引入当前项目名称

```json
"dependencies": {
  "hexo-butterfly-recommend": "^1.0.2",
  "hexo-butterfly-navctrl": "^1.0.0",
}
```

## 运行

```shell
hexo server
```

## hexo-theme-butterfly 升级

```shell
npm update hexo-theme-butterfly
```