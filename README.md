# react-intros

An Introduction to ReactJS.

 - Diff 算法
 - 虚拟 DOM

JSX to everything 

 - JSX --> HTML
 - JSX --> native ios / android
 - JSX --> VR
 - JSX --> 物联网
 
React的基本使用

 - ReactDOM.render() 渲染入口
 
JSX的基本使用

 - JavaScript XML
 - Babel编译
 
React组件

 - 通过函数创建，函数组件， 无状态
 - 通过类创建，类组件，有状态

函数组件
1. 函数名必须以大写字母开头，React 以此来判断是不是组件
2. 函数必须有返回值，可以是 null 或 JSX 对象
3. 返回的 JSX 必须有一个根元素
4. 组件的返回值用（）包裹，避免换行问题

类组件
1. 须继承自 React.Component 类
2. 必须有render方法，并返回一个 react 对象或 null

封装组件到独立的文件中

 - export default Xxxx

父子组件传递数据: props
 - 组件中有一个只读的对象叫 props
 - 传递给组件的属性会转变为 props对象的属性
 
类组件的状态: state
 - 只有类组件才有状态
 - 状态是私有的 完全由组件来控制

组件绑定事件
 - React 事件机制绑定 onClick
 - 通过 bind 绑定
 - 通过箭头函数绑定

React单向数据流动
 - props 自上向下 从父组件流动到子组件
 - 共享的状态提升至父组件中 props