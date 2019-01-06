<!--GFM-TOC--->
<!--ts-->
* [md文件](#md%E6%96%87%E4%BB%B6)
  * [注释说明](#%E6%B3%A8%E9%87%8A%E8%AF%B4%E6%98%8E)
    * [1\. 标题](#1-%E6%A0%87%E9%A2%98)
    * [2\. 换行](#2-%E6%8D%A2%E8%A1%8C)
    * [3\. 列表](#3-%E5%88%97%E8%A1%A8)
      * [无序列表](#%E6%97%A0%E5%BA%8F%E5%88%97%E8%A1%A8)
      * [有序列表](#%E6%9C%89%E5%BA%8F%E5%88%97%E8%A1%A8)
    * [4\. 区块引用](#4-%E5%8C%BA%E5%9D%97%E5%BC%95%E7%94%A8)
    * [5\. 分割线](#5-%E5%88%86%E5%89%B2%E7%BA%BF)
    * [6\. 链接](#6-%E9%93%BE%E6%8E%A5)
      * [行内式](#%E8%A1%8C%E5%86%85%E5%BC%8F)
      * [参数式](#%E5%8F%82%E6%95%B0%E5%BC%8F)
    * [7\. 图片](#7-%E5%9B%BE%E7%89%87)
      * [行内式](#%E8%A1%8C%E5%86%85%E5%BC%8F-1)
      * [参数式](#%E5%8F%82%E6%95%B0%E5%BC%8F-1)
    * [8\. 代码框](#8-%E4%BB%A3%E7%A0%81%E6%A1%86)
      * [当行代码](#%E5%BD%93%E8%A1%8C%E4%BB%A3%E7%A0%81)
      * [多行代码](#%E5%A4%9A%E8%A1%8C%E4%BB%A3%E7%A0%81)
    * [9\. 表格](#9-%E8%A1%A8%E6%A0%BC)
      * [表1](#%E8%A1%A81)
      * [表2](#%E8%A1%A82)
    * [10\. 字体](#10-%E5%AD%97%E4%BD%93)
      * [强调](#%E5%BC%BA%E8%B0%83)
      * [转义](#%E8%BD%AC%E4%B9%89)
      * [删除线5](#%E5%88%A0%E9%99%A4%E7%BA%BF5)
    * [11\. 流程图](#11-%E6%B5%81%E7%A8%8B%E5%9B%BE)
    * [12\. 快捷键](#12-%E5%BF%AB%E6%8D%B7%E9%94%AE)
<!--te-->

# md文件

## 注释说明

### 1. 标题
#\# 一级标题
##\#\# 二级标题 
###\#\#\# 三级标题
以此类推

> ctrl + 数字 为#快捷键
### 2. 换行
行末加两个空格，即可
### 3. 列表
#### 无序列表
* 年后
* 科大
#### 有序列表 
3. 张  
4. 王
8. 李
> 序号是自动生成的 
### 4. 区块引用
> 这是一个引用，用\>符号
### 5. 分割线
--------------
- - - -
### 6. 链接
#### 行内式
* [将夜](https://www.baidu.com/s?wd=将夜 "提示: 搜索将夜") 是什么？
> 链接放在\[ \]里,地址在后面用英文状态下的( )表示
#### 参数式
[name]: http://www.baidu.com/s?wd=name "提示"
点击翻译[name]
### 7. 图片
#### 行内式
![我是图片](https://static.52pojie.cn/static/image/common/10logo.png)
#### 参数式
[图片]: https://static.52pojie.cn/static/image/common/10logo.png
![图片]
> 参数式图片链接有问题  
> 是sublime编译的问题, 换用md pad2之后就没问题  
> 而且,sublime快捷键有冲突  
> typora 里又有问题
### 8. 代码框
#### 当行代码
`<p><a href="baidu.com">`

> 用单反引号, ~下面的符号
#### 多行代码
```
<p><a href="baidu.com">
<p><a href="baidu.com">
<p><a href="baidu.com">
```
> 用三个单反引号
### 9. 表格
#### 表1
姓名|年龄|分数
---|---|---
张|12|99
杨|12|98

#### 表2

姓名|年龄|分数
:-|:-:|-:
张大幅度|12|99
杨第三方|12|98

> 简单的表格绘制,利用：决定对齐方式
### 10. 字体
#### 强调
正常字体  
*字体倾斜*  
**字体加粗**  
***字体加粗倾斜***

#### 转义
\#  
\*

> 用反斜杠\
#### 删除线5
~~删除~~
> 用两个~

#### 待办事宜

* 早晨

> - [x] 起床
> - [ ] 吃饭
> - [x] 打豆豆
### 11. 流程图
```flow
s=>start: 开始
op=>operation: 操作
cond=>condition: 是或否？
e=>end
s->op->cond
cond(yes)->e
cond(no)->op
```

```flow
st=>start: 开始 
e=>end: 登录 
io1=>inputoutput: 输入用户名密码 
sub1=>subroutine: 数据库查询子类 
cond=>condition: 是否有此用户 
cond2=>condition: 密码是否正确 
op=>operation: 读入用户信息
st->io1->sub1->cond
cond(yes)->cond2
cond(no)->io1
cond2(yes)->e
cond2(no)->io1

```



> 不能画出流程图, 不知道是不是sublime 编译的问题  
> 是sublime编译的问题
> md pad2编译也有问题  
> typora里面没有问题

### 12. 快捷键 ###

* ##### markdown pad2

  * ctrl+B: 加粗
  * ctrl+I: 斜体
  * ctrl+Q: 引用  
  * ctrl+K: 添加单行公式
  * ctrl+U: 无序列表
  * ctrl+shift+O: 有序列表
  * ctrl+R：水平线
  * ctrl+L: 添加链接
  * ctrl+G: 添加图片链接
  * ctrl+数字: 显示#
  * ctrl+T: 显示时间戳
  * ctrl+shift+1: 导出为html
  * ctrl+shift+2: 导出为pdf

* Typora

  - ctrl+]: 缩进，同tab
  - ctrl+[: 取消缩进
  - ctrl+/: 查看源代码
  - ctrl+\: 清除格式


