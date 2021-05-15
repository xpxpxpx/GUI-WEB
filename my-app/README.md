
# 前期的知识准备
1.javascript
2.HTML+CSS
3.构建工具：webpack；https://webpack.docschina.org/
    安装命令：npm install webpack -g
4.安装node：
5.cnpm
6.官方文档  https://reactjs.org/

# 创建react项目
npx create-react-app my-app
cd my-app
npm start

# 环境介绍
node——modules：非常大
public：入口文件
src：源文件

# react基础知识
## JSX语法介绍
jsx语法：javascript + XML语法（HTML语法）
解读jsx语法：遇到《》按照HTML语法解析，遇到{}按照JavaScript

# 元素渲染

# 组件
组件的后缀可以使js，也可以是jsx
一个react项目，是由成千上万个组件组成

# porps属性
组件的复用性很重要

# 事件处理
1. this问题
2. 向时间处理程序传递参数

# state

# react生命周期函数
随着我们对React理解和使用越来越多，生命周期的参考价值越来越高
函数列表：start---getDefaultProps----->getinitstate

     componentWILLMount：在组件渲染之前执行
     componentDidMount：在组件渲染之后执行
     shouldComponentUpdate：返回true和false；true则代表改变正确，false代表不容许更改
     componentWILLUpdate：数据在改变之前执行（state，props）
     componentDidUpdate：数据修改完成（state，props）
     componentWILLRecieveProps：props发生改变执行
     componentWILLUnMount：组件卸载前执行



# anti

