# Markdown --Mou

![Mou 图标](http://mouapp.com/Mou_128.png)

## 概览

**Mou**，**Web开发者**缺失的Markdown编辑器

### 语法

##### 加重和强调

**加重** or __加重__ (Cmd + B)

*强调* or _强调_ (Cmd + I)

**有时候，我想让很多文字变成粗体。
真的，很_多_文字**

#### 引用

> 右尖括号 &gt; 用于引用。

#### 链接和Email地址

一个Email地址 <zhuhongxu@gmail.com> 链接。

简单的行内链接 <http://twitter.com/nixzhu>，另一个行内链接[苹果中国](http://www.apple.com.cn)，再来另一个有标题的行内链接[Ubuntu](http://www.ubuntu.com "Linux for human beings")。

一个[引用样式][id]，输入ID，在文档的任何地方，定义一个到对应ID的链接：

[id]: http://mouapp.com "Mac OS X上的Markdown编辑器"

明显，链接上的标题（或者说工具贴士）是可选的。

#### 图片

一个行内图片![Smaller图标](http://smallerapp.com/favicon.ico "我是标题")，标题同意可选。

一个 ![Resize icon][2] 引用样式的图片.

[2]: http://resizesafari.com/favicon.ico "Title"

#### 行内代码和区块代码

行内码由反`引号`包围。要创建区块码：

	每行缩进至少一个Tab或者4个空格。
	var Mou = 真是我想要的那个应用

#### 有序列表

有序列表的创建使用 "1." 和一个空格：

1. 有序列表项目
2. 有序列表项目
3. 有序列表项目

#### 无序列表

无序列表的创建使用 "*" 和一个空格：

* I love Ubuntu
* I love Apple
* I love Mou

或者使用 "-"和一个空格：

- 你喜欢Ubuntu吗？
- 你喜欢Apple吗？
- 你喜欢Mou吗？

#### 强制换行

每行以两个或者多个空格结束会创建一个强制换行，在HTML里叫做 `<br \>`。（Control + 回车）  
上一行以两个空格结束。

#### 水平线

三个或更多星号或短横线：

***
---
- - - -

##### 标题

Setext风格：

这是H1
=====

这是H2
-----

atx风格：

# 这是H1
## 这是H2
### 这是H3
#### 这是H4
##### 这是H5
###### 这是H6

### 额外的语法

##### 删除线

由两个波浪线包含：
~~GFW 方滨兴~~

#### 围栏代码块

开始与一个包含三个或更多反引号的行，结束于同样数目的反引号行：

```
围栏代码块更像是是标准Markdown的正规代码块，
但它们不是用缩进
而是用开始和结束围栏来划分代码块。
```
#### 表格

一个简单的表格看起来如下：

第一个头部 | 第二个头部 | 第三个头部
--------|---------|-------
内容格子 | 内容格子 | 内容格子
内容格子 | 内容格子 | 内容格子

如果你喜欢，你可以给表格的每行都添加引导和结尾分割线：

|第一个头部 | 第二个头部 | 第三个头部|
|---------|-----------|---------|
|内容格子  | 内容格子   | 内容格子 |
|内容格子  | 内容格子   | 内容格子 |

每列的对齐可以通过在分割线上添加冒号来实现：

第一个头部 | 第二个头部 | 第三个头部
:--------|:---------:|-------:
左对齐 | 居中 | 右对齐
左对齐 | 居中 | 右对齐

### 快捷键

#### 查看

* 切换实时预览: Shift + Cmd + I
* 左/右 = 1/1: Cmd + 0
* 左/右 = 3/1: Cmd + +
* 左/右 = 1/3: Cmd + -
* 切换写作方向: Cmd + L
* 全屏切换: Control + Cmd + F

#### 动作

* 拷贝HTML: Option + Cmd + C
* 加重: 选择文字, Cmd + B
* 强调: 选择文字, Cmd + I
* 行内代码: Select text, Cmd + K
* 删除线: Select text, Cmd + U
* 列表: Select lines, Control + L
* 链接: Select text, Control + Shift + L
* 图片: Select text, Control + Shift + I
* 转成大写: Select text, Control + U
* 转成小写: Select text, Control + Shift + U
* 首字母大写: Select text, Control + Option + U
* 空格转Tab: Control + [
* Tab转空格: Control + ]
* 选择单词: Control + Option + W
* 选择行: Shift + Cmd + L
* 选择所有: Cmd + A
* 全不选: Cmd + D
* 插入实体 <: Control + Shift + ,
* 插入实体y >: Control + Shift + .
* 插入实体 &: Control + Shift + 7
* 插入实体 Space: Control + Shift + Space
* 行左移: Select lines, Cmd + [
* 行右移: Select lines, Cmd + ]
* 新行: Cmd + Return
* 注释: Cmd + /
* 强制换行: Control + Return

#### 编辑

* 自动补全当前单词: Esc
* 查找: Cmd + F
* 关闭查找工具栏: Esc

#### 导出

* 导出为 HTML: Option + Cmd + E
* 导出为 PDF:  Option + Cmd + P


### 更多？

别忘了检查偏好设置，那有许多有用的选项。你可以关闭/使能新文档的**显示实时预览**，关闭/使能**自动配对**，**在编辑器里使链接可点击**，改变**基本字体**，选择另一种**主题**或创建你自己的主题。


在Twitter [@chenluois](http://twitter.com/chenluois) 上关注我获取最新的消息。

若有反馈，请用菜单`Help`-`Send Feedback`