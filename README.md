# vue-quick-start-in-4-hours

视屏[4个小时带你快速入门vue]学习笔记，B站[链接](https://www.bilibili.com/video/av76249419?p=3)

## 实验环境

IDE：VSCode
插件：live server

### Note04

* el用来设置Vue实例挂载(管理)的元素
* Vue会管理el选项命中的元素及其内部的后代元素
* 可以使用其他选择器，但建议使用ID选择器
* 可以使用其他双标签，不能使用Html和Body

### Note05

* Vue中用到的数据定义在data中
* data中可以写复杂类型的数据
* 渲染复杂类型数据时，遵守js的语法即可

### Note07

* v-text 指令的作用是：设置标签的内容（textContent）
* 默认写法会替代全部内容，使用 差值表达式 {{}} 可以替换指定内容
* 内部支持写表达式

### Note08

* v-html指令的作用是：设置元素的innerHTML
* 内容中有 html 结构会被解析为标签
* v-text指令无论内容是什么，只会解析为文本
* 解析文本用 v-text，需要解析 html 结构使用 v-html

## 一些骚操作

* VSCode 中，在html文件里输入 `!` + 回车，可以快速生成网页模版
