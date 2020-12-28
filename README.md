# vue-front-pj

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

> 安装 element-ui

```
npm i element-ui -S
```

> 运行时自动打开浏览器

```
config文件夹--->index.js--->autoOpenBrowser: true
```

> 热更新

```
build文件夹--->webpack.dev.conf.js--->devServe--->hot: true
```

> 引入sass

```
npm install sass-loader -D
npm install node-sass -D
```

> 使用颜色值变量
```
npm install sass-resources-loader --save-dev
新建.scss文件存放变量值
```

> 引入全局变量

```
新建全局样式文件
app.vue文件中---> style 标签 ---> @import 全局样式文件
```