对使用过、和未来可能使用到的技术记录   

望各位广大的技友们多多提交你们用过的 js 库，可能会帮助到我解决问题，项目开发时，就能使用你推荐的库来快速开发解决问题！再次感谢，无论什么库都行。

如果对您有用，欢迎也提供你的小觉得不错的库

欢迎：https://github.com/yeyuguo/awesomejs.git  


## 前端 - broswer端

### UI 
--- 

#### UI框架
*UI* | ***UI框架***

名称 | 描述
---|---
react | 框架 - 纯 UI 容器组件框架，mvvm 的框架
react-native - 移动端 - 未使用 | 框架 -和 react 同接口，使用js开发跨终端的 native 开发，类似 AST 来实现的
ant - PC端 | UI+框架 - 针对中后端，在 react 基础上二次封装的成熟UI组件库
ant-mobile - 移动端 | UI+框架 - 针对移动端，接口和组件接口类似 ant
vue | 框架 - 简洁使用的 纯 UI 容器组件的框架，mvvm
backbone | 框架 - mvc 的框架  
knockout | 框架 - mvvm框架


#### 样式
*UI* | ***css样式库***

名称 | 描述
---|---
bootstrap | css样式 - css 框架


#### 图表
*UI* | ***UI 图表***

名称 | 描述
---|---
echart | UI 图表 - canvas 绘制的图表，接口简洁易用
highchart | UI 图表 - svg 绘制的图表，接口简洁易用

#### 动画
*UI* | ***UI动画***

名称 | 描述
---|---
swal | 动画 - 弹窗
animate.css | 动画 - 动画css  
[css-doodle](https://css-doodle.com/) | 动画 - 使用函数式编写 css 动画


### 数据
---

#### 框架 
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




#### 请求
*数据* | ***数据请求 & 节点操作***

名称 | 描述
---|---
ajax | 数据请求 & 节点操作 - 专门用于请求数据管理的，最大的作用是对 dom 进行处理
zepto | 数据请求 & 节点操作 - 针对移动端，轻量化的 ajax 库
graphql | 数据请求 - 根据查询条件请求接口自定义返回数据结构
reqwest | 数据请求 - 可以在node 和 前端都能 ajax 请求数据 
catta | 数据请求 - 一个轻量级请求工具，支持 fetch,jsonp,ajax
axios | 数据请求 - node端、brower端都良好支持的请求数据


#### 模拟
*数据* | ***数据模拟***

名称 | 描述
---|---
easy-mock | 数据模拟 - web网站，开发阶段，模拟数据接口
jquery-mockjax | 数据模拟 - 对ajax 请求进行拦截，模拟返回的数据
mock | 数据模拟 - 模拟假数据，专业造假

#### 处理
*数据* | ***数据处理***

名称 | 描述
---|---
lodash | 数据处理 - js 端对数据进行处理
underscore | 数据处理 - js 端对数据进行处理

### 工具
---

#### 脚手架
*工具* | ***脚手架***

名称 | 描述
---|---
webpack | 脚手架 - 能做任何事，编译源代码，提高开发体验，插件化扩展
rollup - 未使用 | 脚手架 - 类 webpack，默认已经有很多功能自带了，不用像 webpack 需要额外添加
grunt | 脚手架 - 多用于应用开发工具类软件
babel | 工具类 - 转译JS代码，核心利用 AST 转义 js 代码，配置、插件化扩展
roadhog  | 脚手架 - 在create-react-app 基础上，加上了热替换，按需加载，代理等，和ant紧密结合
create-react-app | 脚手架 - 快速创建一个初始化的项目，结合 webpack 与 react 

#### 软件
*工具* | ***工具类***

名称 | 描述
--|---
fontCreator - 软件 | 工具类 - 把图片转成字体图标，矢量图
SVGDeveloper - 软件 | 工具类 - 软件绘画 svg 图案


### 地图
---

#### 地图应用层
*工具* | ***脚手架、工具类***

名称 | 描述
---|---
leaflet | 地图 - 轻量级-PC、mobile 端都能适应的开源库
openstreetmap | 地图 - 类似 leaflet 一样的地图层；






## node端
---

### 建站
---

#### server服务

*建站* | ***服务 server 框架***

名称 | 描述
---|---
express | server - node 端服务
koa | server - express原作者，利用 es6 general 功能，使用 cojs，弥补js和express 的回调黑洞

#### 命令行工具
*建站* | ***命令行工具、日志、配置***

名称 | 描述
---|---
commander | 命令行工具 - node 命令行获取参数
pm2 | 命令行工具 - node 管理服务器项目启动的进程
nodemon | 命令行工具 - 代替 node 热替换启动服务
config | 配置 - 管理配置选项 
log4js | 日志 - 管理日志记录 

### node 数据
---

#### 处理
*数据* | ***node 数据处理***

名称 | 描述
---|---
compressjs | 工具 - 压缩资源中间件，传递压缩资源到前端后再解压
puppeteer | 数据抓取 - 操作 chrome 请求页面，获取各种参数  
express-http-proxy | 数据代理 - express 中间件：代理数据请求

#### node 数据库
*数据* | ***数据库***

名称 | 描述
---|---
mongoose | 数据库 - mongodb 的数据库


