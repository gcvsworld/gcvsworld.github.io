---
title: React学习
date: 2022-11-13 18:49:36
tags:
  - React
---

_天气:🌤_

## React

_1.定义：_
_React 是一个用于构建用户界面的 JavaSript 库_
_2.特点：_
_声明式编程_
_组件化_
_一次学习，随处编写（通过 React 语法配合 React Dom、React Native、React 360 实现 pc，移动，vr 等不同平台的应用）_
_React 的执行结果相当于视频文件数据，在不同的播放器设备上，可能需要通过转换器，将视频编译成不同的格式，来让他们在不同的播放器上播放，React Dom 相当于 React 在 pc 端的渲染器_

---

## JSX

_JSX:JavaScript 的语法扩展_
_React Element 是不可变的对象_
_JSX 会在运行和编译阶段被 babel 编译生成浏览器可以识别的代码_

```
const element = <h1>Hello,world!<h1>;
                          👇
var element = React.creatElement("h1",null,"Hello,world !");
```

---

## JSX 的好处有什么？

_利用 JSX 语法扩展极大的极大的简化了代码，提升了开发效率_
_更重要的是_
![image](https://thumbnail0.baidupcs.com/thumbnail/190b402fcq32d5ce455be5392700df87?fid=3031270481-250528-587206677233301&time=1670979600&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-YlXExp9a7W859auhqv%2BMnnYjVKU%3D&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=9210461343861067433&dp-callid=0&file_type=0&size=c710_u400&quality=100&vuk=-&ft=video)
_在 React 之前 Jq 时代 html 和 js 是分开的，人们在写代码时的往往会把 UI 逻辑和展示逻辑分开，我们本来就是在用 js 不停的改变 ui 分开思考反而会带来很多的操作不便和编程的低效_
_JSX 将 html 和 js 甚至 css 都可以写在一起，可以用 js 的思维去思考整个 UI 逻辑，而不用像传统模式那样切换一个新的语法上下文，一会去这个文件写写 html，一会去另一个文件写写 js_

---

## React 组件开发

### 提取\组合

_一个简单完整的页面应该有_
_app👇_
_Header👇 Content Footer_
_Title_

_注：props 为只读不可修改_

_未完待续~_
