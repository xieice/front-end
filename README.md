# 📚 前端工程师（复习）学习路线

> 从基础到全栈，涵盖现代前端生态，紧跟技术发展趋势。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

## 🎯 学习路线总览

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         🚀 前端工程师成长之路                                 │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│   阶段一          阶段二          阶段三          阶段四          阶段五     │
│   ─────          ─────          ─────          ─────          ─────      │
│   基础巩固   ──▶  ES6+深化   ──▶  框架进阶   ──▶  工程化    ──▶  全栈      │
│   2-3周          2-3周          4-6周          2-3周          4-6周       │
│                                                                              │
│   ·HTML5新特性    ·TypeScript    ·Vue3深入     ·Vite/Webpack  ·Node.js    │
│   ·CSS3进阶      ·ES2024新特性   ·React18      ·Git工作流      ·Express    │
│   ·CSS变量       ·手写实现原理   ·状态管理      ·CI/CD          ·NestJS     │
│   ·布局方案      ·设计模式       ·性能优化      ·Docker         ·数据库     │
│                                  ·SSR/SSG       ·部署            ·Redis     │
│                                  ·小程序        ·安全            ·微服务     │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 📂 仓库目录结构

```
front-end-review/
├── README.md
│
├── 0-前置知识/                    # 环境配置、工具安装
│   ├── VSCode配置.md
│   ├── Git使用指南.md
│   └── 开发环境搭建.md
│
├── 1-HTML_CSS/                   # 第一阶段：HTML/CSS
│   ├── 01-HTML基础/
│   ├── 02-HTML5新特性/
│   ├── 03-CSS基础/
│   ├── 04-CSS3进阶/
│   ├── 05-布局方案/
│   └── 06-CSS动画/
│
├── 2-JavaScript/                  # 第二阶段：JavaScript
│   ├── 01-基础回顾/
│   ├── 02-ES6新特性/
│   ├── 03-ES7-ES14/
│   ├── 04-异步编程/
│   ├── 05-设计模式/
│   ├── 06-手写实现/
│   └── 07-TypeScript基础/
│
├── 3-Vue3/                        # 第三阶段：Vue3
│   ├── 01-核心概念/
│   ├── 02-组合式API/
│   ├── 03-Pinia状态管理/
│   ├── 04-路由进阶/
│   ├── 05-工程化/
│   └── 06-Vue3源码解读/
│
├── 4-React/                       # 第三阶段：React
│   ├── 01-核心概念/
│   ├── 02-Hooks深入/
│   ├── 03-Redux/Zustand/
│   ├── 04-ReactRouter/
│   ├── 05-性能优化/
│   └── 06-源码解读/
│
├── 5-Node.js/                     # 第四阶段：后端
│   ├── 01-Node基础/
│   ├── 02-Express_Koa/
│   ├── 03-NestJS/
│   ├── 04-数据库/
│   ├── 05-Redis缓存/
│   └── 06-微服务/
│
├── 6-工程化/                      # 第五阶段：工程化
│   ├── 01-Vite/
│   ├── 02-构建工具/
│   ├── 03-自动化测试/
│   ├── 04-CI_CD/
│   └── 05-DevOps/
│
├── 7-实战项目/                     # 项目实战
│   ├── 01-类Notion笔记应用/
│   ├── 02-AI聊天助手/
│   ├── 03-低代码平台/
│   ├── 04-协作白板/
│   └── ...
│
└── 8-面试突击/                     # 面试准备
    ├── 前端八股文/
    └── 算法题解/
```

---

## 📖 详细学习内容

---

## 第一阶段：HTML/CSS 基础巩固 🔰

### 1.1 HTML 基础回顾

- [ ] HTML 文档结构（doctype、html、head、body）
- [ ] 常用标签：div、span、p、h1-h6、ul、ol、li、a、img
- [ ] 语义化标签：header、nav、main、section、article、aside、footer
- [ ] 表单元素：input、textarea、select、button、form
- [ ] 表单属性：type、name、value、placeholder、required、pattern
- [ ] HTML 属性：class、id、data-*、style
- [ ] 链接与图片
- [ ] 列表与表格
- [ ] iframe 内联框架
- [ ] 代码标签：code、pre

### 1.2 HTML5 新特性

- [ ] 语义化标签（IE兼容处理）
- [ ] 表单输入类型：email、tel、url、number、range、date、color
- [ ] 表单属性：autocomplete、autofocus、multiple、pattern
- [ ] 新增标签：video、audio、canvas、svg、progress、meter
- [ ] WebSocket 基础
- [ ] Web Storage：localStorage、sessionStorage
- [ ] 离线缓存：Application Cache（了解）
- [ ] Web Worker
- [ ] 地理定位 Geolocation
- [ ] 拖拽 API
- [ ] 文件 API：FileReader
- [ ] 剪切板 API
- [ ] 通知 API
- [ ] requestAnimationFrame

### 1.3 CSS 基础

- [ ] CSS 引入方式：行内、内联、外链、导入
- [ ] 选择器：标签、类、ID、通配符、属性、伪类、伪元素
- [ ] 优先级计算（!important、内联、ID、类、标签）
- [ ] CSS 继承
- [ ] 盒模型：content、padding、border、margin
- [ ] box-sizing：content-box、border-box
- [ ] 常见的 CSS 属性：color、background、font、border、display
- [ ] display 属性：none、block、inline、inline-block
- [ ] 元素类型：块级元素、行内元素、行内块元素
- [ ] 文本样式：text-align、text-decoration、text-indent、white-space
- [ ] 溢出处理：overflow、text-overflow
- [ ] 隐藏元素：visibility、opacity、display:none

### 1.4 CSS3 进阶

- [ ] CSS 变量（自定义属性）：--variable、var()
- [ ] 弹性盒子 Flex 布局
  - [ ] flex-direction、flex-wrap
  - [ ] justify-content、align-items、align-content
  - [ ] flex-grow、flex-shrink、flex-basis
  - [ ] flex 简写
  - [ ] flex 经典布局：骰子、圣杯、双飞翼、悬挂式
- [ ] 网格 Grid 布局
  - [ ] grid-template-columns、grid-template-rows
  - [ ] gap、grid-area
  - [ ] repeat()、minmax()、auto-fit、auto-fill
  - [ ] 网格布局经典案例
- [ ] 媒体查询 @media
- [ ] 响应式单位：rem、em、vw、vh、vmax、vmin、%
- [ ] CSS 函数：calc()、clamp()、min()、max()
- [ ] CSS 新增选择器：:nth-child()、:first-of-type、:not()、:is()、:where()
- [ ] CSS 新增属性：border-radius、box-shadow、text-shadow
- [ ] 渐变：linear-gradient、radial-gradient、conic-gradient
- [ ] 滤镜：filter（blur、brightness、contrast、grayscale...）
- [ ] 混合模式：mix-blend-mode、background-blend-mode
- [ ] CSS 遮罩：clip-path、mask-image
- [ ] backdrop-filter
- [ ] object-fit、object-position
- [ ] aspect-ratio

### 1.5 CSS 动画

- [ ] 过渡 transition
- [ ] 变换 transform：translate、rotate、scale、skew
- [ ] 关键帧动画 @keyframes
- [ ] animation 属性详解
- [ ] 3D 变换：perspective、transform-style、translate3d
- [ ] 动画性能优化：will-change、transform、opacity
- [ ] 逐帧动画
- [ ] Lottie 动画

### 1.6 高级布局方案

- [ ] BFC（块级格式化上下文）
- [ ] IFC（行内格式化上下文）
- [ ] FFC（灵活盒格式化上下文）
- [ ] GFC（网格格式化上下文）
- [ ] CSS Subgrid
- [ ]瀑布流布局
- [ ] 响应式瀑布流
- [ ] 移动端适配方案：viewport、flexible.js、lib-flexible
- [ ] 1px 边框问题及解决方案
- [ ] 多列布局
- [ ] CSS 容器查询 @container

### 1.7 CSS 架构与工程化

- [ ] CSS 预处理器：Sass/SCSS、Less、PostCSS
- [ ] BEM 命名规范
- [ ] OOCSS、SMACSS 思想
- [ ] CSS Modules
- [ ] Tailwind CSS 实用主义
- [ ] UnoCSS 原子化引擎
- [ ] CSS-in-JS：styled-components、emotion
- [ ] Design Token 设计令牌

### 1.8 CSS 实战技巧

- [ ] 水平垂直居中（N种方案）
- [ ] 三角形、箭头、对话框
- [ ] 圆角头像/头像边框
- [ ] 文本省略号（单行/多行）
- [ ] 滚动穿透问题
- [ ] 清除浮动
- [ ] 重绘与回流
- [ ] CSS Houdini 魔法

---

## 第二阶段：JavaScript 深化 ⭐

### 2.1 JavaScript 基础回顾

- [ ] 变量声明：var、let、const 及区别
- [ ] 数据类型：Number、String、Boolean、Undefined、Null、Symbol、BigInt
- [ ] typeof 运算符
- [ ] 类型转换：隐式转换、显式转换
- [ ] 运算符：算术、比较、逻辑、三元、位运算
- [ ] 流程控制：if/else、switch、for、while、do-while、for...in、for...of
- [ ] break、continue、return 区别
- [ ] 函数定义：函数声明、函数表达式、箭头函数
- [ ] 函数参数：默认参数、剩余参数、arguments
- [ ] 作用域：全局作用域、函数作用域、块级作用域
- [ ] 闭包：概念、作用、应用场景
- [ ] this 指向：普通函数、箭头函数、构造函数、call/apply/bind
- [ ] 原型与原型链：prototype、__proto__、constructor
- [ ] 继承：原型链继承、构造函数继承、组合继承、寄生继承、class extends

### 2.2 ES6 新特性

- [ ] let、const 作用域提升
- [ ] 解构赋值：数组解构、对象解构、嵌套解构、默认值
- [ ] 模板字符串：插值、多行字符串、嵌套模板、标签模板
- [ ] 箭头函数：语法、this指向、不能使用的情况
- [ ] 扩展运算符：...数组、...对象、函数参数
- [ ] REST 参数：...args
- [ ] Symbol：创建、用途、Symbol.for、Symbol.keyFor
- [ ] Set：创建、方法、去重
- [ ] Map：创建、方法、与Object对比
- [ ] WeakSet、WeakMap
- [ ] Proxy：代理、Reflect、拦截操作
- [ ] Class 类：class声明、constructor、方法、getter/setter、静态方法
- [ ] 类的继承：extends、super、方法重写
- [ ] 模块化：export/import、默认导出、命名导出、动态导入

### 2.3 ES7-ES14 新特性

**ES2016 (ES7)**
- [ ] Array.prototype.includes()
- [ ] 指数运算符 **

**ES2017 (ES8)**
- [ ] async/await
- [ ] Object.values()、Object.entries()
- [ ] 对象属性描述符：getOwnPropertyDescriptors
- [ ] 字符串填充：padStart()、padEnd()
- [ ] 尾随逗号

**ES2018 (ES9)**
- [ ] 异步迭代：for await...of
- [ ] Promise.finally()
- [ ] 正则表达式增强：dotAll、命名捕获组、lookbehind断言
- [ ] 对象展开运算符 ...

**ES2019 (ES10)**
- [ ] Array.prototype.flat()、flatMap()
- [ ] Object.fromEntries()
- [ ] 字符串方法：trimStart()、trimEnd()
- [ ] Symbol.description
- [ ] 可选的catch参数

**ES2020 (ES11)**
- [ ] 空值合并运算符 ??
- [ ] 可选链 ?.
- [ ] BigInt
- [ ] GlobalThis
- [ ] Promise.allSettled()
- [ ] 动态 import()
- [ ] String.prototype.matchAll()

**ES2021 (ES12)**
- [ ] 逻辑赋值运算符：||=、&&=、??=
- [ ] 数字分隔符：1_000_000
- [ ] Promise.any()
- [ ] Array.prototype.replaceAll()
- [ ] 字符串.replace() 支持正则符号

**ES2022 (ES13)**
- [ ] 类字段声明：public、private、static
- [ ] 私有字段 #
- [ ] Static 类字段
- [ ] 顶层 await
- [ ] 私有字段 in 运算符
- [ ] .at() 索引访问
- [ ] Object.hasOwn()

**ES2023 (ES14)**
- [ ] Array.prototype.toReversed()
- [ ] Array.prototype.toSorted()
- [ ] Array.prototype.toSpliced()
- [ ] Array.prototype.with()
- [ ] Hashbang / Shebang

**ES2024 (ES15) - 最新**
- [ ] Array.prototype.groupBy()、groupByToMap()
- [ ] Promise.withResolvers()
- [ ] Symbol.dispose、Symbol.asyncDispose
- [ ] ArrayBuffer.prototype.transfer()

### 2.4 异步编程

- [ ] 同步与异步概念
- [ ] 回调函数：概念、回调地狱
- [ ] Promise：创建、状态、then/catch/finally、链式调用
- [ ] Promise 静态方法：Promise.resolve()、Promise.reject()、Promise.all()、Promise.race()、Promise.allSettled()、Promise.any()
- [ ] async/await 语法糖
- [ ] async/await 错误处理
- [ ] 并行请求处理
- [ ] 任务队列与事件循环
- [ ] 宏任务与微任务：setTimeout、Promise、MutationObserver
- [ ] Generator 函数：yield、next()、yield*
- [ ] async generator

### 2.5 设计模式

- [ ] 单例模式：惰性单例、代理单例
- [ ] 工厂模式：简单工厂、抽象工厂
- [ ] 建造者模式
- [ ] 观察者模式：发布/订阅
- [ ] 策略模式
- [ ] 代理模式：保护代理、虚拟代理、缓存代理
- [ ] 迭代器模式：Iterator、Generator
- [ ] 装饰器模式：Decorator
- [ ] 适配器模式
- [ ] 外观模式
- [ ] 享元模式
- [ ] MVC、MVP、MVVM 架构模式

### 2.6 手写实现

- [ ] 手写 new
- [ ] 手写 instanceof
- [ ] 手写 bind/call/apply
- [ ] 手写 Promise（Promises/A+规范）
- [ ] 手写 async/await
- [ ] 手写防抖 debounce
- [ ] 手写节流 throttle
- [ ] 手写深拷贝：JSON.parse(JSON.stringify())、递归拷贝、循环引用处理
- [ ] 手写节流定时器
- [ ] 手写数组方法：map、filter、reduce、forEach、find、some、every
- [ ] 手写 new 操作符
- [ ] 手写 JSON.parse（简化版）
- [ ] 手写 LRU 缓存
- [ ] 手写简易模板引擎
- [ ] 手写 EventEmitter（发布订阅）
- [ ] 手写 compose/pipe
- [ ] 手写函数柯里化
- [ ] 手写uncurry
- [ ] 手写偏函数

### 2.7 TypeScript 基础

- [ ] TypeScript 简介与优势
- [ ] TypeScript 安装与配置：tsconfig.json
- [ ] 类型系统：基础类型、对象类型、数组类型、元组、枚举
- [ ] 接口：interface vs type
- [ ] 联合类型与交叉类型
- [ ] 类型断言：as、<>、unknown
- [ ] 类型守卫：typeof、instanceof、in、is
- [ ] 泛型：泛型函数、泛型约束、泛型类
- [ ] 泛型工具类型：Partial、Required、Readonly、Pick、Omit、Record、Exclude、Extract
- [ ] 索引签名
- [ ] 函数类型：函数声明、函数表达式、箭头函数类型
- [ ] 可选参数、默认参数、剩余参数
- [ ] 类：public、private、protected、readonly
- [ ] 抽象类与接口
- [ ] 命名空间与模块
- [ ] 装饰器：类装饰器、方法装饰器、属性装饰器、参数装饰器
- [ ] 声明文件：.d.ts
- [ ] tsconfig.json 详解
- [ ] TypeScript 编译选项
- [ ] TypeScript 类型体操

---

## 第三阶段：前端框架 🔥

### 3.1 Vue3 核心

#### 基础部分
- [ ] Vue3 简介：Composition API vs Options API
- [ ] 创建 Vue 应用：createApp()
- [ ] 模板语法：插值、指令、动态参数
- [ ] 响应式原理：Proxy、Reflect
- [ ] ref 与 reactive：定义响应式数据
- [ ] computed 计算属性
- [ ] watch 侦听器：watch vs watchEffect
- [ ] 生命周期钩子
- [ ] 模板引用：ref 属性
- [ ] 组件基础：注册、传props、emit事件

#### 组合式API
- [ ] setup() 函数
- [ ] 响应式工具：toRef、toRefs、isRef
- [ ] provide/inject 跨级通信
- [ ] nextTick 原理
- [ ] 自定义Hooks：useXxx 组合式函数
- [ ] 逻辑复用：Mixin vs Hooks
- [ ] Teleport 传送门
- [ ] Suspense 异步组件
- [ ] 异步组件：defineAsyncComponent

#### Vue3 新特性和深入
- [ ] v-model 双向绑定新语法
- [ ] watchEffect 立即执行
- [ ] 深度响应式：reactive 中的数组、深层对象
- [ ] 浅层响应式：shallowRef、shallowReactive、triggerRef
- [ ] toRaw 取消响应式
- [ ] MarkRaw 标记非响应式
- [ ] customRef 自定义ref
- [ ] 响应式检测：isProxy、isReactive、isRef
- [ ] Vue3 CSS 新特性：v-bind CSS、scoped 深度选择器
- [ ] Script Setup 语法糖

#### 路由 Vue Router
- [ ] 路由基础：createRouter、createWebHistory
- [ ] 路由配置：path、name、component、redirect
- [ ] 嵌套路由：children
- [ ] 路由传参：params、query、props
- [ ] 编程式导航：push、replace、go
- [ ] 路由守卫：beforeEach、beforeEnter、afterEach
- [ ] 路由元信息：meta
- [ ] 滚动行为控制
- [ ] 懒加载：() => import()
- [ ] 动态路由：addRoute、removeRoute

#### 状态管理 Pinia
- [ ] Pinia 简介与优势
- [ ] 创建 Store：defineStore
- [ ] State 状态
- [ ] Getters 计算属性
- [ ] Actions 同步/异步操作
- [ ] 解构 store：storeToRefs
- [ ] 持久化：pinia-plugin-persistedstate
- [ ] 模块化：store 拆分与组合
- [ ] Pinia vs Vuex

#### Vue3 生态与工程化
- [ ] Vite 构建工具
- [ ] Pinia 状态管理
- [ ] Vue Router 4
- [ ] VueDevtools 调试工具
- [ ] ESLint + Prettier 代码规范
- [ ] Vitest 单元测试
- [ ] Vue Test Utils 测试
- [ ] Nuxt3 全栈框架
- [ ] VuePress 文档生成
- [ ] Vant4 移动端组件库

### 3.2 React18 深入

#### 核心基础
- [ ] React 18 新特性
- [ ] JSX 语法：表达式、条件渲染、列表渲染
- [ ] 组件：函数组件 vs 类组件
- [ ] Props 传值
- [ ] State 状态：useState Hook
- [ ] 事件处理：合成事件、事件绑定
- [ ] 表单处理：受控组件、非受控组件
- [ ] 组件通信：props、callback、Context、订阅发布

#### Hooks 深入
- [ ] useState：基础、函数式更新
- [ ] useEffect：副作用、依赖、清理
- [ ] useLayoutEffect：与 useEffect 区别
- [ ] useRef：DOM引用、持久化
- [ ] useMemo：计算结果缓存
- [ ] useCallback：函数缓存
- [ ] useContext：跨级通信
- [ ] useReducer：复杂状态逻辑
- [ ] useImperativeHandle：暴露方法
- [ ] useDebugValue：自定义Hook调试
- [ ] 自定义 Hooks

#### React 18 新特性
- [ ] Automatic Batching 自动批处理
- [ ] Concurrent Features 并发渲染
- [ ] useTransition 过渡任务
- [ ] useDeferredValue 延迟值
- [ ] Suspense 服务端组件
- [ ] 新的 Root API：createRoot

#### 状态管理
- [ ] Context API：createContext、useContext
- [ ] Redux：Store、Reducer、Action、dispatch
- [ ] React-Redux：useSelector、useDispatch
- [ ] Redux Toolkit：createSlice、createAsyncThunk
- [ ] Zustand：轻量状态管理
- [ ] Jotai：原子化状态
- [ ] Recoil：Facebook 出品
- [ ] React Query / TanStack Query：服务端状态
- [ ] Valtio：响应式状态

#### 路由 React Router
- [ ] React Router v6 新特性
- [ ] 路由配置：Routes、Route
- [ ] 嵌套路由
- [ ] 路由传参：params、searchParams、state
- [ ] 编程式导航：useNavigate
- [ ] 路由守卫：Wrapper Component
- [ ] 懒加载：React.lazy、Suspense
- [ ] 路由Hooks：useParams、useSearchParams、useLocation

#### 性能优化
- [ ] React.memo 缓存组件
- [ ] useMemo 缓存计算
- [ ] useCallback 缓存函数
- [ ] Virtual List 虚拟列表
- [ ] 懒加载：React.lazy、Suspense
- [ ] Code Splitting 代码分割
- [ ] 状态管理优化
- [ ] Key 的正确使用
- [ ] 组件拆分原则
- [ ] Tree Shaking

#### React 生态
- [ ] Vite + React
- [ ] Ant Design / Ant Design Mobile
- [ ] MUI / Chakra UI
- [ ] Tailwind CSS
- [ ] Framer Motion 动画
- [ ] React Spring 物理动画
- [ ] React Query 数据请求
- [ ] React Router 路由
- [ ] React DnD 拖拽
- [ ] React Virtual 虚拟列表
- [ ] SWR 数据请求

### 3.3 小程序开发

#### 微信小程序
- [ ] 小程序注册与开发环境
- [ ] 项目结构：app.js、app.json、app.wxss、pages
- [ ] WXML 模板语法：数据绑定、列表渲染、条件渲染
- [ ] WXSS 样式
- [ ] JS 逻辑层：Page、Component、Behavior
- [ ] 生命周期：应用生命周期、页面生命周期、组件生命周期
- [ ] 路由：navigateTo、redirectTo、switchTab
- [ ] 数据请求：wx.request
- [ ] API：界面、网络、媒体、存储、设备
- [ ] 组件：内置组件、自定义组件、Component构造器
- [ ]插槽：slot、slot-scope
- [ ] 抽象节点：componentGenerics
- [ ] 分包加载
- [ ] npm 支持
- [ ] 云开发：云函数、云数据库、云存储

#### UniApp（多端）
- [ ] UniApp 项目创建
- [ ] 开发规范：视图层、逻辑层
- [ ] 条件编译：#ifdef、#ifndef
- [ ] 样式管理：rpx、样式隔离
- [ ] 生命周期：应用、页面、组件
- [ ] 组件：原生组件、uni-ui
- [ ] 通信：props、$emit、provide/inject、bus
- [ ] Vuex/Pinia 状态管理
- [ ] API：网络、支付、推送、分享
- [ ] 打包：H5、App、小程序

#### Taro（React）
- [ ] Taro 项目初始化
- [ ] 目录结构
- [ ] 路由配置
- [ ] 组件开发
- [ ] 状态管理
- [ ] Redux/Taroize
- [ ] 请求封装
- [ ] 多端适配

#### 鸿蒙/OpenHarmony
- [ ] ArkTS 语法
- [ ] ArkUI 声明式UI
- [ ] 组件化开发
- [ ] 状态管理
- [ ] 分布式能力

---

## 第四阶段：工程化与工具链 ⚙️

### 4.1 Vite

- [ ] Vite vs Webpack 区别
- [ ] Vite 项目创建：npm create vite
- [ ] Vite 配置：vite.config.ts
- [ ] 插件系统：vite-plugin-xxx
- [ ] 环境变量：.env
- [ ] HMR 热模块替换
- [ ] 预构建：esbuild、dependencies
- [ ] 构建优化：build.target、terser
- [ ] 公共基础路径：base
- [ ] 部署：preview、github actions

### 4.2 构建工具

#### Webpack
- [ ] Webpack 核心概念：entry、output、loader、plugin
- [ ] Webpack 配置：webpack.config.js
- [ ] Loader：css-loader、sass-loader、babel-loader、ts-loader
- [ ] Plugin：html-webpack-plugin、mini-css-extract-plugin、clean-webpack-plugin
- [ ] DevServer：热更新、代理配置
- [ ] Code Splitting：splitChunks、dynamic import
- [ ] Tree Shaking
- [ ] 懒加载/预加载
- [ ] Source Map：production/development
- [ ] 性能优化：体积优化、速度优化
- [ ] 自定义 Loader
- [ ] 自定义 Plugin

#### Rollup
- [ ] Rollup vs Webpack
- [ ] Rollup 配置
- [ ] 输出格式：es、cjs、umd、iife
- [ ] 插件：@rollup/plugin-node-resolve、commonjs
- [ ] 输出可视化分析

#### Turbopack
- [ ] Turbopack 简介
- [ ] Turbopack vs Webpack vs Vite

#### esbuild
- [ ] esbuild 快速打包
- [ ] Go 实现的极速构建

### 4.3 包管理器

- [ ] npm：安装、脚本、配置、版本管理
- [ ] yarn：yarn.lock、工作区
- [ ] pnpm：pnpm-lock.yaml、软链接、硬链接、monorepo
- [ ] npx：执行命令
- [ ] nvm/n：Node版本管理
- [ ] nrm：镜像源管理

### 4.4 代码规范与质量

#### ESLint
- [ ] ESLint 配置文件：.eslintrc.js、eslint.config.js
- [ ] 规则配置：extends、plugins、rules
- [ ] Parser：babel-eslint、@typescript-eslint/parser
- [ ] 常见规则：no-unused-vars、no-console、prettier
- [ ] 自动修复：--fix
- [ ] Git Hooks：husky、lint-staged
- [ ] ESLint 退出码

#### Prettier
- [ ] Prettier 配置：.prettierrc
- [ ] 忽略文件：.prettierignore
- [ ] 与 ESLint 集成：eslint-config-prettier
- [ ] 格式化命令

#### Stylelint
- [ ] Stylelint 配置
- [ ] CSS/SASS/Less 规范
- [ ] 与 Prettier 集成

#### EditorConfig
- [ ] .editorconfig 跨编辑器配置

### 4.5 Git 进阶

- [ ] Git 基础：add、commit、push、pull、clone
- [ ] 分支管理：branch、checkout、merge、rebase
- [ ] 远程仓库：origin、remote
- [ ] 撤销操作：reset、revert、checkout
- [ ] 暂存：stash
- [ ] 日志：log、reflog
- [ ] Cherry-pick
- [ ] Tag 标签
- [ ] Git Flow 工作流
- [ ] GitHub Flow
- [ ] GitLab Flow
- [ ] .gitignore 规则
- [ ] 钩子：pre-commit、commit-msg、pre-push
- [ ] 子模块：submodule
- [ ] Git bisect 二分查找

### 4.6 自动化测试

#### Jest / Vitest
- [ ] 单元测试概念
- [ ] Jest 配置
- [ ] 测试文件：.test.js、.spec.js
- [ ] 匹配器：expect、toBe、toEqual、toContain
- [ ] 异步测试：async/await、done 回调
- [ ] 生命周期：beforeEach、afterEach
- [ ] Mock：jest.fn()、jest.mock()、jest.spyOn()
- [ ] 覆盖率：--coverage
- [ ] 快照测试：toMatchSnapshot
- [ ] Vitest：Vite 原生测试框架

#### Testing Library
- [ ] @testing-library/react
- [ ] @testing-library/vue
- [ ] @testing-library/jest-dom
- [ ] 查询方法：getBy、findBy、queryBy
- [ ] 事件模拟：fireEvent、userEvent
- [ ] 异步查询：waitFor、findBy

#### E2E 测试
- [ ] Cypress 端到端测试
- [ ] Playwright 跨浏览器测试
- [ ] Puppeteer 无头浏览器

### 4.7 CI/CD

- [ ] 持续集成概念
- [ ] GitHub Actions：workflows、jobs、steps
- [ ] GitLab CI
- [ ] Jenkins
- [ ] 自动化部署流程
- [ ] 环境管理：dev、test、staging、production
- [ ] Docker 基础

### 4.8 部署与运维

#### Docker
- [ ] Docker 概念：镜像、容器、仓库
- [ ] Dockerfile 编写
- [ ] Docker 命令：build、run、ps、exec、logs
- [ ] Docker Compose：多容器编排
- [ ] Docker 网络与数据卷
- [ ] 前端项目 Docker 化

#### 部署平台
- [ ] Vercel：前端部署
- [ ] Netlify：静态网站部署
- [ ] GitHub Pages：免费托管
- [ ] 阿里云、腾讯云：ECS
- [ ] Nginx 配置与优化
- [ ] PM2 Node 进程管理
- [ ] 宝塔面板（了解）

#### 性能监控
- [ ] 前端监控：性能、错误、行为
- [ ] Sentry：错误追踪
- [ ] Lighthouse：性能审计
- [ ] Web Vitals：LCP、FID、CLS

---

## 第五阶段：Node.js 全栈 🚀

### 5.1 Node.js 基础

- [ ] Node.js 简介与优势
- [ ] 模块化：CommonJS、ES Module
- [ ] 包管理：npm、package.json
- [ ] 全局对象：global、process、Buffer
- [ ] 事件循环：EventEmitter
- [ ] 异步I/O：回调、Promise、async/await
- [ ] 文件系统：fs 模块
- [ ] 路径处理：path 模块
- [ ] HTTP 模块：创建服务器
- [ ] URL 模块：URL 解析
- [ ] querystring：查询字符串
- [ ] crypto：加密模块
- [ ] stream：流操作
- [ ] zlib：压缩模块
- [ ] debug：调试模块

### 5.2 Express 框架

- [ ] Express 项目创建
- [ ] 路由：GET、POST、PUT、DELETE、PATCH
- [ ] 中间件：app.use()、next()
- [ ] 内置中间件：express.static、express.json、express.urlencoded
- [ ] 第三方中间件：body-parser、cors、morgan
- [ ] 路由参数：params、query
- [ ] 请求体解析
- [ ] 错误处理：error handler
- [ ] 模板引擎：ejs、pug、art-template
- [ ] 静态资源服务
- [ ] Router 模块化
- [ ] MVC 架构
- [ ] Cookie 与 Session
- [ ] 文件上传：multer
- [ ] 日志管理：morgan
- [ ] JWT 认证
- [ ] 权限控制

### 5.3 Koa 框架

- [ ] Koa vs Express
- [ ] 核心概念：ctx、next
- [ ] 中间件机制：洋葱模型
- [ ] 异步中间件
- [ ] 错误处理
- [ ] 常用中间件：koa-router、koa-body、koa-cors
- [ ] 脚手架：koa-generator

### 5.4 NestJS 框架

- [ ] NestJS 架构：Controller、Provider、Module
- [ ] 依赖注入：IoC 容器
- [ ] 装饰器：@Get、@Post、@Body、@Param
- [ ] 模块化设计
- [ ] 数据库集成：TypeORM、Prisma
- [ ] 验证与转换：class-validator
- [ ] 认证授权：Passport、JWT
- [ ] 文档生成：Swagger/OpenAPI
- [ ] 微服务：@nestjs/microservices
- [ ] GraphQL：@nestjs/graphql

### 5.5 数据库

#### MongoDB
- [ ] MongoDB 简介
- [ ] 数据库操作：创建、删除、切换
- [ ] 集合操作：创建、删除
- [ ] 文档操作：CRUD
- [ ] 查询：find、findOne、投影、排序、分页
- [ ] 更新：update、updateOne、updateMany
- [ ] 删除：remove、deleteOne、deleteMany
- [ ] 聚合管道：aggregate
- [ ] 索引：createIndex
- [ ] mongoose ODM
  - [ ] Schema 定义
  - [ ] Model 创建
  - [ ] CRUD 操作
  - [ ] 验证器：required、unique、enum
  - [ ] 中间件：pre、post
  - [ ] 静态方法
  - [ ] 虚拟属性
  - [ ] 关联查询：populate

#### MySQL / PostgreSQL
- [ ] SQL 基础：DDL、DML、DQL、DCL
- [ ] 常用查询：SELECT、WHERE、JOIN
- [ ] 聚合函数：COUNT、SUM、AVG、MAX、MIN
- [ ] 子查询与联合查询
- [ ] 事务：ACID、BEGIN、COMMIT、ROLLBACK
- [ ] 索引：主键、唯一、普通、全文、复合
- [ ] Node.js 操作：mysql2、pg
- [ ] ORM：Sequelize、TypeORM

### 5.6 Redis 缓存

- [ ] Redis 简介与安装
- [ ] 数据类型：String、Hash、List、Set、ZSet
- [ ] 常用命令
- [ ] Node.js 操作：ioredis、node-redis
- [ ] 缓存策略：Cache-Aside、Read-Through、Write-Through
- [ ] 会话存储：express-session
- [ ] Token 存储
- [ ] 分布式锁
- [ ] 消息队列：Redis Stream、Pub/Sub

### 5.7 接口设计

- [ ] RESTful API 设计规范
- [ ] 接口版本管理
- [ ] 统一响应格式：{code, data, message}
- [ ] 错误码设计
- [ ] 参数校验：joi、zod、class-validator
- [ ] 接口文档：Swagger、Apifox、Postman
- [ ] 限流熔断：rate-limit
- [ ] CORS 跨域处理
- [ ] 接口安全：XSS、CSRF、SQL注入
- [ ] HTTPS 配置
- [ ] HTTP/2 特性

### 5.8 微服务

- [ ] 微服务架构概念
- [ ] 服务拆分原则
- [ ] API Gateway：Kong、NGINX
- [ ] 服务发现：Consul、Eureka
- [ ] 配置中心：Apollo、Nacos
- [ ] 消息队列：RabbitMQ、Kafka、Redis Stream
- [ ] 容器化部署：Docker Swarm、Kubernetes
- [ ] 服务监控：Prometheus、Grafana
- [ ] 链路追踪：Jaeger、Zipkin

---

## 第六阶段：项目实战 🎯

### 项目一：类 Notion 协作笔记应用

**技术栈：** Vue3/React + TypeScript + Tailwind CSS + Zustand/Pinia + Vite

**功能点：**
- [ ] 文档编辑器（富文本/markdown）
- [ ] 块级编辑：段落、标题、列表、代码块、图片
- [ ] 双向链接：@提及、页面引用
- [ ] 实时协作：WebSocket、CRDT
- [ ] 页面历史版本
- [ ] 模板系统
- [ ] 搜索功能：全文搜索、标签搜索
- [ ] 权限管理：公开/私有/团队共享
- [ ] 导入导出：PDF、Markdown、HTML
- [ ] AI 辅助：智能摘要、续写、翻译

**亮点：**
- 实时协作编辑
- 块级拖拽排序
- 本地优先，离线可用

---

### 项目二：AI 聊天助手（类 ChatGPT）

**技术栈：** React/Vue + TypeScript + Tailwind CSS + Zustand + Vite

**功能点：**
- [ ] 对话列表管理
- [ ] 多轮对话上下文
- [ ] Markdown 代码渲染
- [ ] 代码高亮：Prism/Shiki
- [ ] 流式输出（SSE）
- [ ] 消息复制、重新生成
- [ ] 对话搜索
- [ ] Prompt 模板市场
- [ ] 主题切换
- [ ] 本地存储对话记录
- [ ] 接入多模型：OpenAI、Claude、本地模型

**亮点：**
- 支持多模型切换
- 插件化 Prompt 模板
- 移动端适配

---

### 项目三：低代码可视化编辑器

**技术栈：** Vue3 + TypeScript + Element Plus + Vite

**功能点：**
- [ ] 拖拽式页面构建
- [ ] 物料面板：基础组件、业务组件
- [ ] 属性配置面板
- [ ] 画布：缩放、网格、标尺
- [ ] 预览与编辑模式切换
- [ ] 组件嵌套：栅格布局
- [ ] 撤销/重做
- [ ] 复制/粘贴/删除
- [ ] 响应式预览
- [ ] 页面交互配置：跳转、弹窗、表单提交
- [ ] 生成低代码 Schema
- [ ] 导出 JSON/生成代码

**亮点：**
- 实时预览
- 组件市场
- 自定义物料

---

### 项目四：实时协作白板

**技术栈：** React + TypeScript + Tailwind CSS + Socket.IO + Canvas API

**功能点：**
- [ ] 画布操作：缩放、平移、撤销、重做
- [ ] 绘图工具：画笔、形状、橡皮擦
- [ ] 工具栏：颜色、粗细、透明度
- [ ] 素材库：图片、贴纸
- [ ] 文本工具
- [ ] 多人实时协作
- [ ] 激光笔演示模式
- [ ] 房间管理：创建、加入
- [ ] 录屏功能
- [ ] 导出图片/PDF
- [ ] 历史记录回放

**亮点：**
- WebSocket 实时同步
- Canvas 性能优化
- 演示模式

---

### 项目五：开源博客系统（前后端分离）

**技术栈：** Vue3 + Nuxt3 + TypeScript + Tailwind CSS | Node.js + NestJS + PostgreSQL + Redis

**功能点：**
- [ ] 用户系统：注册、登录、第三方登录
- [ ] 文章管理：富文本编辑器、Markdown
- [ ] 分类与标签系统
- [ ] 评论系统：楼层评论、回复
- [ ] 点赞与收藏
- [ ] 文章搜索：ElasticSearch
- [ ] RSS 订阅
- [ ] 站内信/通知系统
- [ ] 个人主页/作品集
- [ ] 后台管理系统
- [ ] SEO 优化：SSG/SSR、Sitemap
- [ ] 性能优化：CDN、图片优化

**亮点：**
- 全栈开发能力
- SSR/SSG 渲染
- 完整的用户体系

---

### 项目六：在线代码编辑器

**技术栈：** React + Monaco Editor + WebContainer API

**功能点：**
- [ ] 代码编辑器：语法高亮、自动补全
- [ ] 多语言支持：JavaScript、Python、Go
- [ ] 终端模拟器
- [ ] 文件树结构
- [ ] WebContainer 沙箱运行
- [ ] 实时预览 iframe
- [ ] 主题切换
- [ ] Vim/Emacs 模式
- [ ] Git 集成
- [ ] 一键部署：Vercel、Netlify

**亮点：**
- 浏览器内运行 Node.js
- 真实终端体验
- 云端同步

---

### 项目七：数据可视化大屏

**技术栈：** Vue3 + ECharts/AntV + DataV + Vite

**功能点：**
- [ ] 多种图表：折线、柱状、饼图、地图
- [ ] 实时数据刷新
- [ ] 动态标题与时间
- [ ] 组件库：数字翻牌、进度条、轮播表
- [ ] 主题切换
- [ ] 全屏适配
- [ ] 导出为图片
- [ ] 响应式布局
- [ ] 地图可视化

**亮点：**
- 酷炫的视觉效果
- 真实数据接入
- 多种大屏模板

---

## 第七阶段：进阶技能 ⭐

### 浏览器与网络

- [ ] 浏览器架构：渲染进程、JS引擎、网络进程
- [ ] 页面加载流程：DNS、TCP、TLS、HTTP
- [ ] 渲染过程：DOM树、CSSOM、Layout Tree、Paint、Composite
- [ ] 重绘与回流
- [ ] 事件循环：宏任务、微任务
- [ ] 垃圾回收：标记清除、引用计数
- [ ] V8 引擎原理
- [ ] HTTP/1.1 vs HTTP/2 vs HTTP/3
- [ ] HTTPS 原理：TLS/SSL
- [ ] DNS 解析：递归查询、迭代查询
- [ ] TCP 三次握手、四次挥手
- [ ] WebSocket 原理
- [ ] CDN 原理

### Web 安全

- [ ] XSS 跨站脚本攻击：存储型、反射型、DOM型
- [ ] CSRF 跨站请求伪造
- [ ] SQL 注入
- [ ] 点击劫持
- [ ] 中间人攻击
- [ ] CSP 内容安全策略
- [ ] CORS 跨域资源共享
- [ ] CSRF Token
- [ ] SameSite Cookie
- [ ] HTTPS 加密
- [ ] 密码加密存储

### 性能优化

#### 前端性能
- [ ] 关键渲染路径
- [ ] 图片优化：格式、WebP、懒加载、srcset
- [ ] 代码分割：路由、组件
- [ ] Tree Shaking
- [ ] 预加载/预取：preload、prefetch
- [ ] 缓存策略：强缓存、协商缓存
- [ ] CDN 加速
- [ ] Gzip/Brotli 压缩
- [ ] 代码压缩：Terser
- [ ] 防抖与节流
- [ ] 虚拟滚动
- [ ] 骨架屏
- [ ] SSR vs SSG vs CSR
- [ ] Core Web Vitals：LCP、FID、CLS、INP

#### Webpack 优化
- [ ] 减少构建体积
- [ ] 加快构建速度
- [ ] 分包策略
- [ ] 缓存优化
- [ ] Tree Shaking

### PWA 与移动端

- [ ] Service Worker：缓存、离线
- [ ] Manifest：安装到桌面
- [ ] Push Notification：推送通知
- [ ] 后台同步
- [ ] 离线页面
- [ ] 移动端适配：viewport、rem、flex
- [ ] 1px 边框问题
- [ ] 点击延迟问题：fastclick
- [ ] 滑动体验：better-scroll
- [ ] 原生交互：唤起App、分享

### WebAssembly

- [ ] WebAssembly 简介
- [ ] Rust/C++ 编译为 Wasm
- [ ] Wasm 在前端应用
- [ ] 性能提升场景

### Serverless

- [ ] Serverless 架构
- [ ] Vercel Functions
- [ ] AWS Lambda
- [ ] 云函数：腾讯云、阿里云
- [ ] Serverless + SSR

### Web3 与区块链

- [ ] 区块链基础概念
- [ ] Web3.js / Ethers.js
- [ ] 智能合约：Solidity
- [ ] 钱包连接：MetaMask
- [ ] NFT 概念与实现
- [ ] DApp 前端开发

---

## 学习进度追踪 📊

| 阶段 | 主题 | 数量 | 完成 | 进度 |
|:---:|------|:---:|:---:|:---:|
| 1 | HTML/CSS | 0/50 | ░ | 0% |
| 2 | JavaScript | 0/60 | ░ | 0% |
| 3 | Vue3 | 0/40 | ░ | 0% |
| 3 | React | 0/45 | ░ | 0% |
| 4 | 小程序 | 0/30 | ░ | 0% |
| 5 | 工程化 | 0/50 | ░ | 0% |
| 6 | Node.js | 0/50 | ░ | 0% |
| 7 | 实战项目 | 0/7 | ░ | 0% |
| 8 | 进阶技能 | 0/40 | ░ | 0% |

---

## 📚 参考资源

### 官方文档
| 资源 | 链接 |
|------|------|
| MDN Web Docs | https://developer.mozilla.org/zh-CN/ |
| Vue 官方文档 | https://cn.vuejs.org/ |
| React 官方文档 | https://react.dev/ |
| TypeScript 文档 | https://www.typescriptlang.org/zh/ |
| Vite 文档 | https://vitejs.cn/ |
| Node.js 文档 | https://nodejs.org/zh-cn/docs/ |
| Express 文档 | https://express.nodejs.com/ |
| NestJS 文档 | https://nestjs.com/ |


### 工具网站
| 资源 | 链接 |
|------|------|
| Can I Use | https://caniuse.com/ |
| Babel REPL | https://babeljs.io/repl |
| TypeScript Playground | https://www.typescriptlang.org/play |
| RegExr | https://regexr.com/ |
| JSONPlaceholder | https://jsonplaceholder.typicode.com/ |
| CodeSandbox | https://codesandbox.io/ |
| StackBlitz | https://stackblitz.com/ |

---

## ⚠️ 注意事项

1. **按顺序学习**：基础不牢，地动山摇，每个阶段都要扎实
2. **动手实践**：只看不做等于白学，每个知识点都要写代码
3. **定期复习**：艾宾浩斯遗忘曲线，知识需要反复巩固
4. **输出笔记**：写博客、教别人，学习效果最好
5. **参与项目**：开源项目、实习、比赛都是很好的实践
6. **关注前沿**：技术日新月异，关注新技术但不要追新

---

## 📄 许可证

本项目为个人学习使用，不涉及任何商业用途。

---

*🌟 代码不息，学习不止！每天进步一点点🌟！*
