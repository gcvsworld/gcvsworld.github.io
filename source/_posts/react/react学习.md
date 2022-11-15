---
title: React学习
date: 2022-11-13 18:49:36
tags:
  - React
---

*天气:🌤*

## React

*1.定义：*
*React是一个用于构建用户界面的JavaSript库*
*2.特点：*
*声明式编程*
*组件化*
*一次学习，随处编写（通过React语法配合React Dom、React Native、React 360实现pc，移动，vr等不同平台的应用）*
*React的执行结果相当于视频文件数据，在不同的播放器设备上，可能需要通过转换器，将视频编译成不同的格式，来让他们在不同的播放器上播放，React Dom 相当于React在pc端的渲染器*
---

## JSX
*JSX:JavaScript的语法扩展*
*React Element 是不可变的对象*
*JSX会在运行和编译阶段被babel编译生成浏览器可以识别的代码*

```
const element = <h1>Hello,world!<h1>;
                          👇
var element = React.creatElement("h1",null,"Hello,world !");
```
---

## JSX的好处有什么？
*利用JSX语法扩展极大的极大的简化了代码，提升了开发效率*
*更重要的是*
![image](https://thumbnail0.baidupcs.com/thumbnail/190b402fcq32d5ce455be5392700df87?fid=3031270481-250528-587206677233301&time=1668492000&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-Ipc7usRD07BdYXGrZeK0G6hgiTE%3D&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=471563202569812285&dp-callid=0&file_type=0&size=c710_u400&quality=100&vuk=-&ft=video)
*在React之前Jq时代html 和 js 是分开的，人们在写代码时的往往会把UI逻辑和展示逻辑分开，我们本来就是在用js不停的改变ui分开思考反而会带来很多的操作不便和编程的低效*
*JSX将html和js甚至css都可以写在一起，可以用js的思维去思考整个UI逻辑，而不用像传统模式那样切换一个新的语法上下文，一会去这个文件写写html，一会去另一个文件写写js*
---

## React组件开发

### 提取\组合
*一个简单完整的页面应该有*
*app👇*
*Header👇  Content   Footer*
*Title*

*注：props为只读不可修改*

*未完待续~*