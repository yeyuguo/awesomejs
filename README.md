对使用过、和需要用到的技术记录   

望各位广大的技友们多多提交你们用过的 js 库，也许对你来说没用，但可能会帮助到我解决问题，就使用你提供的库来快速开发解决问题！再次感谢，无论什么方向的都行。



## node端

*工具* | ***建站、命令行工具、配置***

名称 | 描述
---|---
commander | 命令行工具 - node 命令行获取参数
pm2 | 命令行工具 - node 管理服务器项目启动的进程
nodemon | 命令行工具 - 代替 node 热替换启动服务
express | 建站 - node 端服务
koa | 建站 - express原作者，利用 es6 general 功能，使用 cojs，弥补js和express 的回调黑洞
config | 配置 - 获取配置选项 


*工具* | ***数据抓取、工具***

名称 | 描述
---|---
compressjs | 工具 - 压缩资源中间件，传递压缩资源到前端后再解压
puppeteer | 数据抓取 - 操作 chrome 请求页面，获取各种参数

*数据* | ***数据库***

名称 | 描述
---|---
mongoose | 数据库 - mongodb 的数据库

*数据* | ***数据请求、数据代理***

名称 | 描述
---|---
reqwest | 数据请求 - 可以在node 和 前端都能 ajax 请求数据；
express-http-proxy | 数据代理 - express 中间件：代理数据请求


## 前端

### UI 库|框架 体系
*UI* | ***框架|UI框架***

名称 | 描述
---|---
react | 框架 - 纯 UI 容器组件框架，mvvm 的框架
react-native - 移动端 - 未使用 | 框架 -和 react 同接口，使用js开发跨终端的 native 开发，类似 AST 来实现的
ant - PC端 | UI框架 - 针对中后端，在 react 基础上二次封装的成熟UI组件库
ant-mobile - 移动端 | 框架 - 针对移动端，接口和组件接口类似 ant
vue | UI框架 - 简洁使用的 纯 UI 容器组件的框架，mvvm
bootstrap | UI库 - css 框架
backbone | UI框架 - mvc 的框架  

### UI 图表
*UI* | ***图表***

名称 | 描述
---|---
echart | UI 图表 - canvas 绘制的图表，接口简洁易用
highchart | UI 图表 - svg 绘制的图表，接口简洁易用

### 动画
*UI* | ***动画弹窗***

名称 | 描述
---|---
swal | 动画弹窗

### 数据管理 
*数据* | ***数据管理***

名称 | 描述
---|---
lodash | 数据处理 - js 端对数据进行处理
vuex - 未使用 | 数据管理 - vue 大型项目管理数据
pubsub-js | 数据管理 - 轻量简单的发布订阅
Rxjs | 数据管理 - 发布订阅的数据框架
redux | 数据管理 - 前端数据管理的框架,可插拔式的使用
react-redux | 数据管理 - react 结合 redux,简化 redux 的使用,核心还是 redux
redux-thunk | 数据管理 - 解决 redux 的异步副作用
redux-saga | 数据管理 - 使用 general 方式简化 redux 业务复杂副作用（异步）,能处理比redux-thunk 更复杂的业务功能，相应接口也比较多
dva | 数据管理 - 针对 antd 框架，在 roadhog 基础上，结合 redux、react-saga的实践应用的脚手架，缺点，依赖redux、redux-saga
easy-mock | 数据管理 - web网站，开发阶段，模拟数据接口
jquery-mockjax | 数据管理 - 对ajax 请求进行拦截，模拟返回的数据
mock | 数据管理 - 模拟假数据，专业造假

### 请求
*数据* | ***数据请求 & 节点操作***

名称 | 描述
---|---
ajax | 数据请求 & 节点操作 - 专门用于请求数据管理的，最大的作用是对 dom 进行处理
zepto | 数据请求 & 节点操作 - 针对移动端，轻量化的 ajax 库
graphql | 数据请求 - 根据查询条件请求接口自定义返回数据结构

## 工具 & 脚手架
*工具* | ***脚手架、工具类***

名称 | 描述
---|---
webpack | 脚手架 - 能做任何事，编译源代码，提高开发体验，插件化扩展
rollup - 未使用 | 脚手架 - 类 webpack，默认已经有很多功能自带了，不用像 webpack 需要额外添加
babel | 工具类 - 核心利用 AST 转义 js 代码，插件话扩展
fontCreator - 软件 | 工具类 - 把图片转成字体图标，矢量图
roadhog  | 脚手架 - 在create-react-app 基础上，加上了热替换，按需加载，代理等，和ant紧密结合
create-react-app | 脚手架 - 快速创建一个初始化的项目，结合 webpack 与 react 



