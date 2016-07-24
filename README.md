# ThoughtWorksTest

ThoughtWorks西邮暑期培训训练集

暑期培训时间为2016年 7.18~8.26 每周6天，每天8小时

培训期间，每日尽可能更新当日作业至本仓库

## 项目训练

* take-out-food

## 基于 pipeline 的 tasking 方法

### pipeline 画图规范要点

* 用动词和小驼峰法命名函数

* 输入数据不能写到输出线上

* 每个对象要说明数据类型

* 每个函数只处理一个功能 -- 便于分块和命名

* 图中只需出现英文

### 常见动词

get 获取
generate 创建 生成
find 获取集合中的子集
calculate 计算
merge 合并
split 拆分

//布尔值
is    是...
has   拥有

### 零散笔记

拿到一个开发需求 --> 画 pipeline 图 --> 写 tasking 测试函数 --> 写核心函数 --> 进行测试

每个函数的圈复杂度要有所控制（每有一个if/for/while等圈复杂度加一），圈复杂度越小越利于维护

人肉测试 -- console.log()

单元测试 -- jasmine

工程实践

一个优化漂亮的代码可以成为自注释

一个漂亮/优化符合命名/使用规范的代码可以成为自注释（不需要写注释）

代码是给人看的，偶尔在机器上跑一下

Atwood定律：Any application that can be written in JavaScript,will eventually be written in JavaScript

马丁·福勒：计算机科学最难应付的两件事——命名和缓存失效。

## JS要点

JS中的多种循环方式

for i

for in

for of

assign

push

split

find

map

filter

reduce

JSON.stringify()

对象克隆 -- 原型链/值传递/引用传递