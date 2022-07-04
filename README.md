<!--
 * @Author: your name
 * @Date: 2021-05-26 20:43:34
 * @LastEditTime: 2021-09-18 16:06:18
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \mobgi_ua_element_ui\README.md
-->


## Install
```shell
npm install element-ui -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'element-ui'

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'element-ui'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```
For more information, please refer to [Quick Start](http://element.eleme.io/#/en-US/component/quickstart) in our documentation.

## Browser Support
Modern browsers and Internet Explorer 10+.

## Development
Skip this part if you just want to use Element.

For those who are interested in contributing to Element, please refer to our contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md) | [Español](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.es.md) | [Français](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.fr-FR.md)) to see how to run this project.


### 发布到npm
```code

本地执行npm login
输入账号密码邮箱后，执行npm publish

有可能出错：426 Upgrade Required
解决办法执行两行命令如下
npm install -g https://tls-test.npmjs.com/tls-test-1.0.0.tgz
npm config set registry https://registry.npmjs.org
```
