<!--
 * @Author: web.王晓冬
 * @Date: 2021-08-19 18:56:59
 * @LastEditors: web.王晓冬
 * @LastEditTime: 2021-09-17 15:39:07
 * @Description: file content
-->
[![Version](https://img.shields.io/npm/dt/vue3-lock-screen.svg?style=flat-square)](https://www.npmjs.com/package/vue3-lock-screen)
[![Downloads](https://img.shields.io/npm/v/vue3-lock-screen.svg?style=flat-square)](https://www.npmjs.com/package/vue3-lock-screen)
[![GitHub stars](https://img.shields.io/github/stars/xdlumia/vue3-lock-screen.svg?style=flat-square)](https://github.com/xdlumia/vue3-lock-screen/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/xdlumia/vue3-lock-screen.svg?style=flat-square)](https://github.com/xdlumia/vue3-lock-screen/issues)
[![GitHub forks](https://img.shields.io/github/forks/xdlumia/vue3-lock-screen.svg?style=flat-square)](https://github.com/xdlumia/vue3-lock-screen/network)
[![GitHub last commit](https://img.shields.io/github/last-commit/google/skia.svg?style=flat-square)](https://github.com/xdlumia/vue3-lock-screen)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](https://github.com/xdlumia/vue3-lock-screen)

[![NPM](https://nodei.co/npm/vue3-lock-screen.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue3-lock-screen)

基于vue3开发的锁屏界面

## 功能一览

# 主页示例

[https://dreamwq.com/vue3-lock-screen/](https://dreamwq.com/vue3-lock-screen/)



## 近期更新 v1.3.1-beta.3 🎉

# 使用指南

## 安装
npm安装：
``` bash
npm i vue3-lock-screen --save
```
yarn安装：
``` bash
yarn add vue3-lock-screen --save
```

## 开始使用

#### 全局使用

``` js
import { createApp } from 'vue'
import App from './App.vue'
let app = createApp(App)

import vue3videoPlay from 'vue3-lock-screen' // 引入组件
import 'vue3-lock-screen/dist/style.css' // 引入css
app.use(vue3videoPlay)

app.mount('#app')
```

#### 组件内使用

```js
// require style
import 'vue3-lock-screen/dist/style.css'
import { videoPlay } from 'vue-video-play'
export default {
  components: {
    videoPlay
  }
}
```


## 基本示例
提供了丰富了配置功能

## Props


| 名称   |    说明    |  类型  | 可选值 | 默认值 |
| ------ | :--------: | :----: | :----: | :----: |
| width  | 播放器宽度 | string |   -    | 800px  |
| height | 播放器高度 | string |   -    | 450px  |


## Events
vue3-lock-screen支持video原生所有事件  [video默认事件](https://segmentfault.com/a/1190000008053507)

| 事件名称     | 说明         | 回调 |
| ------------ | ------------ | ---- |
| mirrorChange | 镜像翻转事件 | val  |


## 快捷键说明
支持快捷键操作
| 键名  | 说明 |
| ----- | ---- |
| Space | /    |
# Author

[xdlumia](https://dreamwq.com)

# 点个start

[vue3-lock-screen](https://github.com/xdlumia/vue3-lock-screen)

