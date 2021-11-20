<p align="center">
  <img src="https://cdn.rawgit.com/ElemeFE/element/dev/element_logo.svg">
</p>

<p align="center">
  基于Element ui 2.15.6二次开发
</p>

> A Vue.js 2.0 UI Toolkit for Web.

Element will stay with Vue 2.x 

## Install
```shell
npm install dib-element-ui -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'dib-element-ui'

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'dib-element-ui'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```
For more information, please refer to [Quick Start](http://element.eleme.io/#/en-US/component/quickstart) in our documentation.

## 修改内容

1.date-picker：日期组件修改：年份选择面板区域10年=》12年<br>
<img alt="year-table-update" src="https://github.com/dibtzw/readme-image/blob/main/element/year-table.png" width="200"><br>
2.date-picker：日期组件修改：月份选择面板设置为数字月份<br>
<img alt="month-table-update" src="https://github.com/dibtzw/readme-image/blob/main/element/month-table.png" width="200"><br>

## Browser Support
Modern browsers and Internet Explorer 10+.

## LICENSE
[MIT](LICENSE)
