# reactDemo

## 1.库与框架的区别
## 2. React 由 Fackbook开发，开源。
## 3.react特点 
   3.1 组件化模式，声明式编码，提高代码复用率。
   3.2 react-navtive 开发移动端
   3.3 虚拟dom + diffing算法。减少原生dom交互。
## 4.browsefiyg   https://browserify.org/
## 5. bootcdn(https://www.bootcdn.cn/react/17.0.0/)
## 6. Babel (https://www.babeljs.cn/)->cjs -> browserify- > 浏览器代码
    babel 可以把jsx->js
## 7.虚拟DOM与真实DOM 
   7.1 虚拟DOM，结构比较“轻”，真实DOM比较“重”
   7.2 虚拟DOM，最终转为真实DOM放入页面
## 8. Jsx 语法规则
   8.1 创建虚拟DOM，不要写引号；
   8.2标签中要混入js表达式，要用{}
   8.3标签类名用 className 指定
   8.4 style={{color:’red’}} 内联样式书写格式
   8.5  只能有1个根标签
   8.6 标签要闭合
   8.7 关于标签首字母
       8.7.1 若首字母小写，那么react就回去寻找与之同名的htl标签。找到，直接转为html同名元素，未找到，报错
       8.7.2 若首字母大写，那么react寻找同名组件。找到则用组件，未找到，报错。
## 9.jsx 的定义
## 10.注意区分：【js语句（代码）】与 【js表达式】
     10.1.表达式：一个表达式会产生一个值，可以放在任何一个需要值的地方
       下面这些都是表达式
        （1). a
          (2). a+b
          (3). demo(1)
          (4). arr.map()
          (5) function test(){}. …..
       10.2 语句（代码）
           (1). if(){}
           (2). for(){}
           (3). switch(){case:xx}
## 11.vscode-用户代码片段
## 12.函数式组件（babel严格模式，this 为undefined） 与 类式组件(this  类的实例对象)
## 13.组件3大核心属性。state props refs
    13.1 state 用 api set 改变。改变后调用render。
## 14.原生点击事件几种实现方式
   14.1 <button id=“btn” onclick=“add()”>
   14.2 const btn = document.getElementById(‘btn’)
          btn.onclick=()=>{}
    14.3 btn.addEventListener(‘click’,()=>{})
## 15. 类中函数 通过 bind 改变this 指向问题，组件的方法用箭头 避免this undefied 问题。
## 16. props 的限制，  propTypes  defaultProps
## 17. refs。 this.xxxRef =  React.createRef()； 回调形式refs
## 18. 1.类式组件中的构造函数完全可以省略
     2.若不省略，则必须写super()
## 19. React的事件处理
    19.1 通过onXxx属性指定事件处理函数
         19.1.1 React使用的是自定义(合成)事件，而不是使用原生Dom事件——为了更好的兼容性
          19.1.2React中的事件是通过事件委托方式处理的（委托给组件最外层的元素）——为了效率高
    19.2通过event.target得到发生事件的dom元素对象
## 20. 非受控组件 / 受控组件


   
