# butterfly-plug
`hexo-theme-butterfly` 扩展插件调试模板，版本号随 `hexo-theme-butterfly` 更新

## 效果
![banner](/source/img/cover1.png "banner")

## 版本
`hexo` 7.0.0
`hexo-theme-butterfly` 4.10.0
`hexo-butterfly-recommend` 1.0.0

## 安装
`hexo-butterfly-recommend` 还未上线，安装前请在 `package.json` 的依赖里删除它。

```shell
npm i
```

安装完成后，下载 `https://github.com/weizwz/hexo-butterfly-recommend`，解压后放至 `node_modules` 目录下，在 `package.json` 中引入

```json
"dependencies": {
  "hexo-butterfly-recommend": "^1.0.0",
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