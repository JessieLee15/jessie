# TODOS

下滑/上拉刷新 实现方案



* PWA ：Progressive Web App

* 微前端 ： ThoughtWorks

* BFF（Backend For Frontend）架构

* Serverless: 接口、服务端渲染


![mis server render](../img/todos/micro_fe.png)


https://github.com/vuejs/vuepress


手动搭一套全栈框架
https://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000/001434501628911140e1cb6ce7d42e5af81480f7ecd5802000


---

* 一个小疑问：
![arrow-return](../img/todos/arrow-return.jpeg)
  现象：箭头函数 当函数体只有一个语句时，可以不要大括号包裹，并且会默认把这个语句的结果作为return；用大括号包裹的函数体，哪怕里面只有一个语句，都没有默认return～

  疑问： 不知道如何解释或理解


jQ 的find无法获取到动态添加的节点。。。。啊。。。。



* URL hash 

* js数据类型的隐式转换


### 111
需求：在淘宝，单日四亿PV，页面数据来自各个不同接口，为了不影响体验，先产生页面框架后，在发起多个异步请求取数据更新页面，这些多出来的请求带来的影响不小，尤其在无线端。

解决方案：在 NodeJS 端使用 Bigpiper 技术，合并请求，降低负担，分批输出，不影响体验。同时可以拆分大接口为独立小接口，并发请求。串行 => 并行，大幅缩短请求时间。


https://tech.meituan.com/2018/09/06/fe-tiny-spa.html