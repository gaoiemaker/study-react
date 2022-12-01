# study-react
study-react every day


## day01 

### react 简介：
react 的优点：

1.采用组件化的模式、声明式编码 提高开发效率及组件的复用率

2.在react native中可以使用react语法进行移动端开发

3.是用来虚拟dom 和 优秀的diff算法 尽量减少与真实动漫的交互

### 创建虚拟dom两种方式

1.使用jsx ：
    <h1> hello world</h1>

2.使用js
    React.createElement('h1',{id:'text','hello world'})

## 为什么使用jsx （js的语法糖）

    在嵌套结构的标签的构建的时候 使用jsx可以让编码人员更加简洁的生成结构

## 虚拟dom
    1.虚拟dom就是一个js对象 抽象思想的一种数值代替品

    2.虚拟dom比较轻 真实dom比较重 属性相较少一些

    3.虚拟dom最终会被react转换成真实dom

## jsx语法规则
    1.定义虚拟dom的时候 不要加引号
    2.标签中混入js表达式的时候 使用 {} 
    3.如果想用样式的类名 使用className 
    4.内联样式的css时候 使用 style={{color:'#fff'}}

    5.虚拟dom只能有一个跟标签
    6.标签必须闭合
    7.标签的首字母
        （1）若是小写字母开头 则将去html中找响应同名标签 若html中午改标签报错
        （2） 若是大写字母开头 react就去渲染对应的组件 


