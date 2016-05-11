##面试总结
2016年4月面试总结（百度外卖、网易、饿了么、去哪儿、光音网络）
###react vs vue
1. 生命周期
2. react和vue有什么不同，各种优缺点
3. react底层diff算法了解么
4. vue源码看过么
5. mvc理解
6. 用react的时候，怎么组织你的代码的
7. 如果让你重新做一遍，你觉得有哪些可以优化改进的地方（代码方面，还有其他方面）


###webpack
1. 对其理解
2. 对比用过其他的打包工具


###基础知识
1. 闭包，什么叫，闭包作用。
2. 原型，proptotype和一个对象原型还是有区别的。
```
function A() {
}
function B() {
}
var b=new B();
B.prototype={};
B.prototype.constructor=B;
console.log(b instanceof B);
//结果为false
```
3. this指向
4. 函数科里化
	1. 写一个方法，实现f(2,3)=5;f(2)(3)=5
	2. 如何实现es6 当中的Promise。
5. js源码extentd实现原理，手写深拷贝
6. es5新增加哪些东西
7. 正则
	1. 取url以‘\’分开的最后一个，不包括#？
8. 找出一个字符串当中重复子字符串最多的字符串和重复次数。
9. 实现trim方法
10. 二叉树遍历
11. 写一个函数，输入n，输出n个不重复的[2,32]之间的整数。
12. 事件冒泡捕获，事件代理
13. 路由实现原理
14. dom原生操作
15. 从浏览器输入网址到最终渲染页面这当中都发生了什么
15. 历史管理
16. ajax，跨域方法
17. 选择题：哪些事件没有冒泡（onblur）


###其他
1. 有代码规范的习惯吗？eslint
2. eslint是默认的还是自定义的
3. 原公司都用什么框架


###项目
1. 都做过哪些项目，描述一下（得好好准备）


###html+css
1. less你怎么用的
2. BFC知道么，盒子模型
3. 对web语义化的理解


###非技术
1. 谈谈你的优点，缺点
2. 你对未来的职业规划，近两年你想达到一个什么样的水平，接下来准备做什么
3. 为什么离职

#续

页面优化

1. **浏览器渲染过程**
2.  优化技巧总结
2. **项目描述**
3. 技术选型
4. 语义化理解
5. 项目承担角色
6. redux；状态如何管理。
7. 移动端，适配。
8. 状态码

##阿里

1. new
2. 优化
3. js动画、开启硬件加速
4. css动画
5. 移动端
6. 语义化理解
7. 滚动很卡优化
8. 调试
9. 绝对定位默认
