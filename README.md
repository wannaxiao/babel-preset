# babel-preset

## 安装

```bash
# for js
yarn add -D @momoko/babel-preset-js
# for vue
yarn add -D @momoko/babel-preset-vue
```

## 使用

> package.json 中添加

```js
  "babel": {
    "presets": [
      ["@momoko/js", {
        "useBuiltIns": "usage"
      }]
    ]
  },
  "browserslist": [
    "iOS >= 8",
    "Android >= 4.4"
  ]
```
