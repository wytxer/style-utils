# Style Utils

常用样式库，支持 less 和 scss，包含 flex 布局、margin、padding 等。


## 快速使用

### 安装

```bash
# npm
npm i @wytxer/style-utils

# yarn
yarn add @wytxer/style-utils
```

### 使用

1、安装 less 编译器：

```bash
# npm
npm i less@3.9.0 less-loader@4.1.0 -D

# yarn
yarn add less@3.9.0 less-loader@4.1.0 -D
```

2、在入口文件导入样式库：

```js
import '@wytxer/style-utils/lib/common.less'
```

3、在标签的 class 上设置类名：

```html
<!-- 在 Vue.js 中 -->
<div class="PT12">
  <a-button class="MR10">操作一</a-button>
  <a-button class="MR10">操作二</a-button>
  <a-button class="MR10" type="primary">操作三</a-button>
</div>
<div class="FB FBJC-C">
  <a-button class="MR10">操作一</a-button>
  <a-button class="MR10">操作二</a-button>
  <a-button class="MR10" type="primary">操作三</a-button>
</div>

<!-- 在 React.js 中 -->
<div className="FB FBJC-C FBAI-C FBAC-C">
  <a-button className="MR10">操作一</a-button>
  <a-button className="MR10">操作二</a-button>
  <a-button className="MR10" type="primary">操作三</a-button>
</div>
```


## License

[MIT](/LICENSE)
