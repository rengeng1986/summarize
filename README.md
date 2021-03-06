# QuFei Blog

14年开始创建个人博客，之前由于服务器等因素，一次又一次迁移，最终选择了github来记录一些平常在工作或者学习中遇到的一些问题

* 14年第一版，采用织梦CMS内容管理系统，搭建个人站点，内容迁移到了第二版
* 16年第二版，采用PHP+MySql+Laravel框架前端blade做为模版引擎，发布于腾讯云服务器，可惜部分内容没有做好备份，当时设计的前端页面[个人博客](https://q-angelo.github.io/qublog/)
* 17年初第三版，采用github仓库进行管理

## JavaScript

* [常见问题](/javascript/base.md#常见问题)
* [定时器](/javascript/base.md#定时器)
* [作用域](/javascript/base.md#作用域)
    - `[作用域]` eval()、with欺骗词法作用域 [`[more]`](/javascript/base.md#欺骗词法作用域)
* [类型检测](/javascript/base.md#类型检测)
    - `[类型检测]` typeof、instanceof类型检测 [`[more]`](/javascript/base.md#类型检测)
* [关于this](/javascript/this.md#关于this)
    - `[关于this]` 错误认识 [`[more]`](/javascript/this.md#对于this的错误认识)
    - `[关于this]` this四条绑定规则 [`[more]`](/javascript/this.md#this绑定规则)
    - `[关于this]` 绑定规则优先级 [`[more]`](/javascript/this.md#优先级)
    - `[关于this]` 箭头函数 [`[more]`](/javascript/this.md#箭头函数)
    - `[关于this]` 项目中使用this的一些场景及需要注意的问题 [`[more]`](/javascript/this.md#this在项目中使用问题总结)
* [数组](/javascript/base.md#数组)
    - `[数组去重]` Set数组去重 [`[more]`](/javascript/base.md#set数组去重)
    - `[数组去重]` reduce数组对象去重 [`[more]`](/javascript/base.md#reduce数组对象去重)
    - `[数组去重]` lodash uniqBy数组去重 [`[more]`](/javascript/base.md#参考lodash)
    - `[数组降维]` 数组降维三种方法 [`[more]`](/javascript/base.md#数组降维)
* [函数](/javascript/base.md#函数)
    - `[函数]` push()数组添加新值后的返回值 [`[more]`](/javascript/base.md#push()数组添加新值后的返回值)
    - `[函数]` arguments.callee递归调用实现一个阶乘函数 [`[more]`](/javascript/base.md#arguments.callee递归调用实现一个阶乘函数)
    - `[函数]` call和apply的使用与区别? [`[more]`](/javascript/base.md#call和apply的使用与区别?)
    - `[函数]` javascript没有引用传递都是按值传递的 [`[more]`](/javascript/base.md#javascript没有引用传递都是按值传递的)
    - `[函数]` 函数声明与函数表达式 [`[more]`](/javascript/base.md#函数声明与函数表达式)
* [匿名函数与闭包](/javascript/base.md#匿名函数与闭包)
    - `[匿名函数与闭包]` 匿名函数的自我执行 [`[more]`](/javascript/base.md#匿名函数的自我执行)
    - `[匿名函数与闭包]` 函数里放一个匿名函数将会产生闭包 [`[more]`](/javascript/base.md#函数里放一个匿名函数将会产生闭包)
    - `[匿名函数与闭包]` 闭包中使用this对象将会导致的一些问题 [`[more]`](/javascript/base.md#闭包中使用this对象将会导致的一些问题)
    - `[匿名函数与闭包]` 一个例子看懂循环和闭包之间的关系 [`[more]`](/javascript/base.md#一个例子看懂循环和闭包之间的关系)
* [正则](/javascript/base.md#正则)
    - `[正则]` 模式修饰符的可选参数 [`[more]`](/javascript/base.md#模式修饰符的可选参数)
    - `[正则]` 两个测试方法test、exec [`[more]`](/javascript/base.md#两个测试方法)
    - `[正则]` 4个正则表达式方法 [`[more]`](/javascript/base.md#4个正则表达式方法)
    - `[正则]` 匹配模式 [`[more]`](/javascript/base.md#匹配模式)
    - `[正则]` 常用正则表达式 [`[more]`](/javascript/base.md#常用正则表达式)
* [错误](/javascript/base.md#错误)
    - `[错误]` ReferenceError错误 [`[more]`](/javascript/base.md#ReferenceError错误)
    - `[错误]` TypeError错误 [`[more]`](/javascript/base.md#TypeError错误)

## Node

* [`[系统模块系列一]` console模块解读](/node/console.md)
  - `console是同步的还是异步的?`[`[more]`](/node/console.md#console是同步的还是异步的?)
  - `实现一个console.log`[`[more]`](/node/console.md#实现一个console.log)
  - `使用说明 基础例子log、info、error、warn、clear`[`[more]`](/node/console.md#使用说明)
  - `使用说明 trace打印错误堆栈`[`[more]`](/node/console.md#trace打印错误堆栈)
  - `使用说明 dir显示一个对象的所有属性和方法`[`[more]`](/node/console.md#dir显示一个对象的所有属性和方法)
  - `使用说明 time和timeEnd计算程序执行消耗时间`[`[more]`](/node/console.md#time和timeEnd计算程序执行消耗时间)

* [`[系统模块系列二]` 子进程child_process](/node/child_process.md)
  - `创建异步进程的四种方法 spawn、fork、exec、execFile`[`[more]`](/node/child_process.md#创建进程)
  - `采用child_process.spawn编写一个守护进程`[`[more]`](/node/child_process.md#采用child_process.spawn编写一个守护进程)
  - `fork创建子进程解决cpu计算密集程序阻塞`[`[more]`](/node/child_process.md#fork创建子进程解决cpu计算密集程序阻塞)

* [对象引用与理解module.exports与exports的关系](/node/object_reference.md)
  - `引用类型比较`[`[more]`](/node/object_reference.md#引用类型比较)
  - `数组对象深度拷贝`[`[more]`](/node/object_reference.md#数组对象深度拷贝)
  - `exports与module.exports的区别?`[`[more]`](/node/object_reference.md#exports与module.exports的区别)

* [JavaScript运行机制](/node/operational_mechanism.md)
  - `js工作机制，微任务与宏任务术语`[`[more]`](/node/operational_mechanism.md#js工作机制)
  - `javascript是单线程，只有同步代码执行完毕后，才会去执行异步代码，详情看示例`[`[more]`](/node/operational_mechanism.md#例2)
  - `process.nextTick与setTimeout递归调用区别?`[`[more]`](/node/operational_mechanism.md#process.nextTick与setTimeout递归调用区别)
  - `setImmediate与setTimeout分别在浏览器与node环境下的区别?`[`[more]`](/node/operational_mechanism.md#setImmediate与setTimeout)

* [性能优化](/node/performance_optimization.md)
  - `map比forEach功能强大, 但是map会创建一个新的数组, 将会占用内存.`[`[more]`](/node/performance_optimization.md#map与forEach)
  - `高并发应对之道.`[`[more]`](/node/performance_optimization.md#高并发应对之道)
  - `require特性与优化`[`[more]`](/node/performance_optimization.md#require特性与优化)
* [爬虫](/node/creeper.md)
  - `抓取目标数据，采用http模块、chromeless中间件`[`[more]`](/node/creeper.md#抓取目标数据)
  - `使用cheerio解析`[`[more]`](/node/creeper.md#使用cheerio解析)
  - `案例-爬取某网站课程标题信息`[`[more]`](/node/creeper.md#案例-爬取某网站课程标题信息)
* [crypto模块实现md5、Cipher等多种加密方式](/node/crypto.md)
  - `对称密钥加解密Cipher实例介绍` [`[more]`](/node/creeper.md#cipher)
  - `不可逆向解密的md5加密` [`[more]`](/node/creeper.md#md5加密)

* [常用插件](/node/plugins.md)
* [经纬度计算](/node/distance.md)
* [C++编写node插件](/node/c_addons.md)
* [Javascript排序](/node/sort.md)

## ES6
* [`[ES6语法扩展系列一]` let、const声明变量](/javascript/ES6/1-let%20const.md)
* [`[ES6语法扩展系列二]` 数组、对象解构赋值](/javascript/ES6/2-解构赋值.md)
* [`[ES6语法扩展系列三]` 正则扩展](/javascript/ES6/3-%E6%AD%A3%E5%88%99%E6%89%A9%E5%B1%95.md)
* [`[ES6语法扩展系列四]` 字符串扩展](/javascript/ES6/4-%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%89%A9%E5%B1%95.md)
* [`[ES6语法扩展系列五]` 数值扩展](/javascript/ES6/5-%E6%95%B0%E5%80%BC%E6%89%A9%E5%B1%95.md)
* [`[ES6语法扩展系列六]` 数组扩展](/javascript/ES6/6-%E6%95%B0%E7%BB%84%E6%89%A9%E5%B1%95.md)  
* [`[ES6语法扩展系列七]` 函数扩展](/javascript/ES6/7-%E5%87%BD%E6%95%B0%E6%89%A9%E5%B1%95.md)
* [`[ES6语法扩展系列八]` 对象扩展](/javascript/ES6/8-%E5%AF%B9%E8%B1%A1%E6%89%A9%E5%B1%95.md)
* [`[ES6语法扩展系列九]` Symbol用法](/javascript/ES6/9-Symbol%E7%94%A8%E6%B3%95.md)
* [`[ES6语法扩展系列十]` set-map用法](/javascript/ES6/10-set-map%E7%94%A8%E6%B3%95.md)
* [`[ES6语法扩展系列十一]` Promise](/javascript/ES6/13-Promise.md)
* [`[ES6语法扩展系列十二]` Symbol.iterator](/javascript/ES6/14-Iterator.md)
* [`[ES6语法扩展系列十三]` Generator](/javascript/ES6/15-Generator.md)
* [`[ES6语法扩展系列十四]` Decorators](/javascript/ES6/16-Decorators.md)

## 项目发布

* [npm发布自己模块](/release/npm_deploy.md)
    - `npm安装模块速度很慢的情况下可以将npm源设置为国内的淘宝源，npm发布需切换回npm源`[`[more]`](/release/npm_deploy.md#npm源设置)
    - `npm注册登录`[`[more]`](/release/npm_deploy.md#npm注册登录)
    - `npm module 发布`[`[more]`](/release/npm_deploy.md#npm-module-发布)
    - `在发布过程中可能遇到的问题汇总`[`[more]`](/release/npm_deploy.md#可能遇到的问题)

* [NodeJs线上服务器部署与发布](/release/nodejs_deploy.md)
    - `创建用户与修改用户权限`[`[more]`](/release/nodejs_deploy.md#创建用户)
    - `三种可选方法登录远程服务器`[`[more]`](/release/nodejs_deploy.md#登录远程服务器)
    - `增强服务器安全等级`[`[more]`](/release/nodejs_deploy.md#增强服务器安全等级)
        - `[增强服务器安全等级]` 出于基本的安全考虑修改端口号
        - `[增强服务器安全等级]` 设定iptables规则
        - `[增强服务器安全等级]` 设置fail2ban
    - `nodejs生产环境部署`[`[more]`](/release/nodejs_deploy.md#nodejs生产环境部署)
    - `Nginx映射配置`[`[more]`](/release/nodejs_deploy.md#Nginx映射)
    - `MongoDB`[`[more]`](/release/nodejs_deploy.md#mongodb)
        - `[MongoDB]` mongodb安装
        - `[MongoDB]` 防火墙中加入mongodb端口号
        - `[MongoDB]` 更改MongoDB默认端口号
        - `[MongoDB]` 开启MongoDB服务
    - `项目发布`[`[more]`](/release/nodejs_deploy.md#项目发布)
        - `[项目发布]` 选择代码托管仓库
        - `[项目发布]` 实现服务器与第三方仓库的关联
        - `[项目发布]` PM2部署代码到服务器

* [forever发布Nodejs项目](/release/forever_deploy_nodejs.md)

* [React 项目发布](/release/react_deploy.md)

## 项目经验

* [React仿大众点评WebApp开发](https://github.com/Q-Angelo/React-Dianping)
* [基于NodeJs的Web静态资源服务器](https://github.com/Q-Angelo/wsrs)
* [ES6+Gulp 构建彩票项目](https://github.com/Q-Angelo/Gulp-Init-ES6)
* [Nodejs+Express+MongoDB+Jade 仿豆瓣电影网](https://github.com/Q-Angelo/Movies)
* [bootstrap响应式布局开发南钢街道“党群E服务”云平台前端页面](https://q-angelo.github.io/partyMember/)
* [div+css+javascript开发个人博客静态页面](https://q-angelo.github.io/qublog/)
* [div+css仿天猫首页](https://q-angelo.github.io/tm/)

## 数据库

* [聚合函数 aggregate](/database/mongo_Aggregate.md)
* [MongoDB数据引用](/database/mongo_dbref.md)
* [Mac系统下安装MongoDB](/database/mongo_install.md)
* [MongoDB之update更新操作](/database/mongo_update.md)
* [Nodejs链接mongodb](/database/mongo_nodejs_link.md)

## web前端

* [React基础](/web-front-end/react_base.md)
    - `React生命周期`[`[more]`](/web-front-end/react_base.md#React生命周期)
    - `ref是什么?`[`[more]`](/web-front-end/react_base.md#ref是什么?)
* [React开发中遇到的问题汇总](/web-front-end/react_question.md)
    - `question1 Warning: Expected server HTML to contain a matching <div> in <div>.`[`[more]`](/web-front-end/react_question.md#question1)
* [前端项目工程架构(React+Mobx+Webpack+NodeJs+Eslint)](https://github.com/Q-Angelo/web_front_end_frame)
* [flux后起之秀Mobx结合React实现倒计时](/web-front-end/mobx_count_down.md)

## 服务器

* [sudo 出现unable to resolve host 解决方法](/doc/linux_unable_to_host.md)

## 干货分析

* `[版本控制]`[git常用操作](/doc/git.md)
* `[SEO优化]`[SEO网站优化title设置与快速排名](/doc/seo.md)
