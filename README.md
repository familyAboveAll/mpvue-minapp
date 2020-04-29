# mpvue-minapp

> A Mpvue project

## Build Setup

``` bash
# 初始化项目
git clone git@github.com:familyAboveAll/mpvue-minapp.git
cd mpvue-minapp

# 安装依赖
yarn

# 开发时构建
npm dev

# 打包构建
npm build

# 指定平台的开发时构建(微信、百度、头条、支付宝)
npm dev:wx
npm dev:swan
npm dev:tt
npm dev:my

# 指定平台的打包构建
npm build:wx
npm build:swan
npm build:tt
npm build:my

# 生成 bundle 分析报告
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

# mpvue-entry
> 在使用mpvue的时候每个页面都需要配置main.js，繁琐又多余，所以这里使用了mpvue-entry解决这个问题

# http请求
> 使用flyio进行数据交互 [flyio](https://wendux.github.io/dist/#/doc/flyio/readme)









