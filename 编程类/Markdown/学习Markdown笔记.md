# 学习Markdown by Ngai Yean Coi 2023.8.28更新

[返回主页](https://www.stayrabbit.top/)

---

此篇是由Ngai Yean Coi整理编写出的Markdown教程，如有错误的请指出。  
Stayrabbit & Ngai Yean Coi是同一人。  
全篇建议配合源代码一起阅读
[点我查看源码](https://github.com/NgaiYeanCoi/NYC-Notes/blob/master/%E7%BC%96%E7%A8%8B%E7%B1%BB/Markdown/%E5%AD%A6%E4%B9%A0Markdown%E7%AC%94%E8%AE%B0.md?plain=1)  

## 目录

- [学习Markdown by Ngai Yean Coi 2023.8.28更新](#学习markdown-by-ngai-yean-coi-2023828更新)
  - [目录](#目录)
  - [一、前言](#一前言)
    - [1.1 关于Markdown](#11-关于markdown)
    - [1.2 Markdown的应用](#12-markdown的应用)
    - [1.3 Markdown的编辑器](#13-markdown的编辑器)
  - [二、Markdown的语法](#二markdown的语法)
    - [2.1 标题的写法](#21-标题的写法)
    - [2.2 段落](#22-段落)
    - [2.3 分割线](#23-分割线)
    - [2.4 字体格式](#24-字体格式)
      - [2.4.1 Markdown常用下面这几种字体](#241-markdown常用下面这几种字体)
      - [2.4.2 其他的字体](#242-其他的字体)
    - [2.5 列表格式](#25-列表格式)
      - [2.5.1 无序列表](#251-无序列表)
      - [2.5.2 嵌套无序列表](#252-嵌套无序列表)
      - [2.5.3 有序列表](#253-有序列表)
      - [2.5.4 嵌套有序列表](#254-嵌套有序列表)
      - [2.5.5 Markdown Preview Enhanced 拓展](#255-markdown-preview-enhanced-拓展)
    - [2.6 区块引用](#26-区块引用)
      - [2.6.1 区块的嵌套](#261-区块的嵌套)
      - [2.6.2 区块中使用列表](#262-区块中使用列表)
      - [2.6.3 列表中使用区块](#263-列表中使用区块)
    - [2.7 转义](#27-转义)
    - [2.8 代码](#28-代码)
      - [2.8.1 行内代码（片段的代码）](#281-行内代码片段的代码)
      - [2.8.2 代码块区块](#282-代码块区块)
    - [2.9 超链接](#29-超链接)
      - [2.9.1 超链接的高级用法](#291-超链接的高级用法)
    - [2.10 插入图片](#210-插入图片)
      - [2.10.1 指定图片的高度与宽度](#2101-指定图片的高度与宽度)
    - [2.11 表格](#211-表格)
  - [参考文献](#参考文献)
  - [扩展阅读](#扩展阅读)
  - [后续将继续更新...](#后续将继续更新)


## 一、前言

### 1.1 关于Markdown

* Markdown是一种轻量标记语言,它可以让人们更容易读懂纯文本的文档说明

* Markdown编写的文档可以导出为HTML、World、图像、PDF 等多种格式的文档

* Markdown文档的后缀`.md` `.markdown`


### 1.2 Markdown的应用

+  Markdown可以用来写笔记、电子书

+  目前很多网站都广泛使用Markdown来撰写帮助文档或者是用于论坛，例如：GitHub、简书等 


### 1.3 Markdown的编辑器

* Markdown存在有多种多样的编辑器，并没有哪种编辑器更好的说法，只有适合自己的编辑器。

* 常见的Markdown编辑器有**Visual Studio Code**、**Typora**、**Obsidian**等

## 二、Markdown的语法

* Markdown 有着非常简洁的语法，不过由于它的自由性，Markdown 也产生了许多变体，如 GitHub Flavored Markdown (GFM) 和 Pandoc 。

* 其他的暂且不讨论，先来看看Markdown 通用的基础语法。

* 以下的语法基于 **VS Code** 与 **Markdown Preview Enhanced 插件** 


### 2.1 标题的写法

* 标题的写法可以用"#"来表示标题的大小

>\# 一级标题  
>\## 二级标题  
>\### 三级标题  
>\#### 四级标题  
>\##### 五级标题  
>\###### 六级标题  

例如一级标题：

>\#&nbsp;要输入的文本  

---


### 2.2 段落

* Markdown段落没有特殊的格式段落跟段落之间要隔开一行，**段落的换行是使用两个以上空格加上回车**。    

>段落一\&nbsp;\&nbsp;
段落二  

示例：  

段落一  
段落二

P.S. 结合源代码来看

---

### 2.3 分割线

* 分割线的写法可以用三条横线 `-`、星号 `*`、下划线 `_` 或者三条以上，**行内不能有其他东西**。  

> \---  
> \***  
> \___  
> \-----  
> \*****  

示例：

---

* 你也可以在星号或是横线中间插入空格。  

> \* * *  
> \- - -  
> \_ _ _

---

### 2.4 字体格式

* Markdown在使用的时候，我们需要**加粗**、*斜体*、***粗斜体*** 来让笔记更加的醒目跟美观。  

#### 2.4.1 Markdown常用下面这几种字体 

* 加粗文本  
> \*\*文字**  

示例：**文字**


*  斜体文本
> \*文字*   

示例：*文字*


*  粗斜体文本 
> \*\*\*文字***  

示例：***文字***


#### 2.4.2 其他的字体

Markdown在使用的时候还会使用到 ~~删除线~~、<u>下划线</u> 、脚注的情况。

*  删除线文本  
> \~~文字~~  

示例：~~文字~~


*  下划线文本  
>\<u>文字\</u>

示例：<u>文字</u>


*  脚注文本  

首先创建脚注 
>\[^定义脚注文本]  

后面再创建跟前面创建的脚注补充说明的文字
>\[^定义脚注文本]:（补充文字）。

示例：[^stayrabbit]  

[^stayrabbit]:（`2.4.2`脚注的示例）

P.S. 结合源代码来看

---

### 2.5 列表格式

* Markdown 支持有序列表和无序列表列表，是记笔记时非常基本的元素。

#### 2.5.1 无序列表

* 无序列表使用星号`*`、加号`+`或是减号`-`作为列表标记，这些标记后面要添加一个空格，然后再填写内容。

> \* 第一项  
> \* 第二项  
> \* 第三项  

> \+ 第一项  
> \+ 第二项  
> \+ 第三项  

> \- 第一项  
> \- 第二项  
> \- 第三项  

示例：
* 第一项
* 第二项
* 第三项  


#### 2.5.2 嵌套无序列表

* 嵌套无序列表，嵌套列表需要再子列表选项中前面多加两个空格或者四个然后再填写内容。

>*第一项  
> &nbsp;&nbsp;*嵌套第一项  
> &nbsp;&nbsp;*嵌套第二项  
> &nbsp;&nbsp;*嵌套第三项  
>*第二项  
> &nbsp;&nbsp;*嵌套第一项  
> &nbsp;&nbsp;*嵌套第二项  
> &nbsp;&nbsp;*嵌套第三项


示例：

* 第一项
  * 嵌套第一项
  * 嵌套第二项
  * 嵌套第三项  
* 第二项
  * 嵌套第一项
  * 嵌套第二项
  * 嵌套第三项


#### 2.5.3 有序列表

* 有序列表使用数字并加上`.` 号加上空格输入内容来表示。

>1. 第一项  
>2. 第二项  
>3. 第三项

P.S. `“.”`后面有空格

示例：

1. 第一项  
2. 第二项
3. 第三项


#### 2.5.4 嵌套有序列表

* 嵌套有序列表与[2.5.2](#252-嵌套无序列表)方法类似，嵌套列表需要再子列表选项中前面多加两个空格或者四个然后再填写内容。

>1. 第一项  
>&nbsp;&nbsp;1. 嵌套第一项  
>&nbsp;&nbsp;2. 嵌套第二项  
>&nbsp;&nbsp;3. 嵌套第三项  
>2. 第二项  
>&nbsp;&nbsp;1. 嵌套第一项  
>&nbsp;&nbsp;2. 嵌套第二项  
>&nbsp;&nbsp;3. 嵌套第三项  

示例:

1. 有序列表 1
   1. 嵌套有序列表第一项
   2. 嵌套有序列表第二项
2. 有序列表 2
   1. 嵌套有序列表第一项
   2. 嵌套有序列表第二项

#### 2.5.5 Markdown Preview Enhanced 拓展

* 任务列表待办事项，基于Markdown Preview Enhanced插件的拓展任务列表
  
> \* \[ &nbsp;] 1. 未完成事情
>\* \[ &nbsp;] 2. 未完成事情
> \* [X] 3. 已完成的事情

示例:
* [ ] 1. 未完成事情
* [ ] 2. 未完成的事情
* [x] 3.已完成的事情

---

### 2.6 区块引用

* Markdown 区块引用是在段落开头使用 `>`符号 ，然后后面紧跟一个空格符号。


> \>&nbsp;引用文本test

示例：

> Stayrabbit:Hello World！


#### 2.6.1 区块的嵌套

*  区块跟列表一样是可以嵌套的，一个 `>` 符号是最外层，两个 `>` 符号是第一层嵌套，以此类推。

> \>&nbsp;第外层  
> \>\>&nbsp;第一层嵌套   
> \>\>\>&nbsp;第二层嵌套  
> \>\>\>\>&nbsp;第三层嵌套


示例:
> 最外层
>> 第一层嵌套
>>> 第二层嵌套  
>>>> 第三层嵌套


#### 2.6.2 区块中使用列表

* 在区块中是可以使用列表的列表的规则请参照[2.5](#25-列表格式)的格式。

> \>区块中使用列表  
> \* 无序第一项  
> \* 无序第二项  
> 1\. 有序第一项  
> 2\. 有序第二项

示例：

>区块中使用列表示例
> * 无序第一项  
> * 无序第二项  
> 1. 有序第一项  
> 2. 有序第二项

#### 2.6.3 列表中使用区块

* 如果要在列表内放进区块，就需要在 > 前添加四个空格的缩进。

> \* 无序第一项  
&nbsp;&nbsp;&nbsp;&nbsp;>区块第一项  
&nbsp;&nbsp;&nbsp;&nbsp;>区块第二项  
> \* 无序第二项  
&nbsp;&nbsp;&nbsp;&nbsp;>区块第一项  
&nbsp;&nbsp;&nbsp;&nbsp;>区块第二项 

示例：
* 无序第一项  
    > 区块第一项  
    > 区块第二项
* 无序第二项  
    > 区块第一项  
    > 区块第二项 

P.S. 有序列表也类似请参考[2.6.3](#263-列表中使用区块)与[2.5](#25-列表格式)。

---


### 2.7 转义

*  Markdown 使用了很多特殊符号来表示特定的意义，如果需要显示特定的符号则需要使用转义字符，Markdown 使用反斜杠`\`转义特殊字符。  

> \\ * \\* 文本字符 \ \*\ \*

示例:
> \*\*文本字符\*\*

* Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号包括`\`本身：

>\   反斜线
>`   反引号
> \*   星号
> _   下划线
> {}  花括号
> []  方括号
> ()  小括号
> \#   井字号
> \+   加号
> \-   减号
> \.   英文句点
> \!   感叹号

P.S. 转义在区块引用[2.6](#26-区块引用)中也是有效的。

---


### 2.8 代码

* Markdown在写代码笔记或者在撰写帮助文档的时候，可以让其更加规范、简洁、易懂。

#### 2.8.1 行内代码（片段的代码）

* 如果是段落上的一个函数或片段的代码可以用反引号“ ` ”把它包起来。


>\`printf("Hello World");``  

示例：
`printf("Hello World");`


#### 2.8.2 代码块区块

* Markdown可以用 “ ``` ” 来包围一段代码，并指定一种语言（也可以不指定）。

> \```C {.line-numbers} //指定一种语言例如C语言。{.line-numbers}表示显示代码行数（基于Markdown Preview Enhanced插件）
> #include <stdio.h>
> int main()
> {
> printf("Hello World");
> return 0;
> }
> \```&nbsp; //引用结束

示例:

```C{.line-numbers}
#include <stdio.h>
int main()
{
printf("Hello World");
return 0;
}
```

* 或者你可以用第二种方法  
* 代码块前后需要有至少一个空行，且每行代码前需要有至少两个`Tab`或四个空格。 

>&nbsp;&nbsp;&nbsp;&nbsp;#include <stdio.h>//前面有四个空格
&nbsp;&nbsp;&nbsp;&nbsp;int main()//前面有四个空格
&nbsp;&nbsp;&nbsp;&nbsp;{//前面有四个空格
&nbsp;&nbsp;&nbsp;&nbsp;printf("Hello World");//前面有四个空格
&nbsp;&nbsp;&nbsp;&nbsp;return 0;//前面有四个空格
&nbsp;&nbsp;&nbsp;&nbsp;}//前面有四个空格

示例：  

    #include <stdio.h>
    int main()
    {
    printf("Hello World");
    return 0;
    }

---

### 2.9 超链接

* Markdown中的文本可以用下面的方式插入超链接

> \[超链接名称](超链接地址)


<https://www.stayrabbit.top/>

示例：

[超链接](https://www.stayrabbit.top/)  

- 或者可以直接引用链接

> <超链接地址>

示例：

<https://www.stayrabbit.top/>


#### 2.9.1 超链接的高级用法

- Markdown还可以通过一个变量名称来设置一个超链接，在后面进行变量的赋值。
 
> [定义一个超链接名称]\[定义一个超链接变量名称]&nbsp;  
> [超链接变量名称]:https:\\www.stayrabbit.top //需跟上面定义的变量名称相对应:后面接地址

示例：

 [2.9.1的示例][example]

 [example]:http://www.stayrabbit.top/

 P.S. 查看本篇Markdown的源代码，这里把`example`用作超链接的变量名称，把`2.9.1的示例`用作超链接的名称

---

 ### 2.10 插入图片

- 在Markdown中插入图片  

>\![图片属性名称]\(图片的地址 "图片提示语") //"图片提示语"可以不填  

>\![图片属性名称]\(https://avatars.githubusercontent.com/u/59606047?s=400&u=155fe46660bc002266cbcba0719bdda83d79edb4&v=4 "示例图片提示语")

示例
![图片属性名称](https://avatars.githubusercontent.com/u/59606047?s=400&u=155fe46660bc002266cbcba0719bdda83d79edb4&v=4 "示例图片提示语")


- 或者引用文件中的相对地址

>\![图片属性名称]\(./img/profile.jpg "图片提示语")  //"图片提示语"可以不填

示例：

![相对地址图片名称](./img/profile.jpg "示例图片提示语")




#### 2.10.1 指定图片的高度与宽度

- Markdown不能指定图片的高度与宽度，如果你需要改变的话可以用HTML的`<img>`标签

> \<img decoding="async" src="./img/profile.jpg" width="30%" title="img标签的示例" >

示例：


> <img decoding="async" src="./img/profile.jpg" width="30%" title="img标签的示例">

### 2.11 表格

-

## 参考文献

1. Markdown - 维基百科，自由的百科全书 -wiki- https://zh.wikipedia.org/wiki/Markdown  
2. 第 3 期、写作：使用 Markdown 记笔记入门 -知乎- https://zhuanlan.zhihu.com/p/496076040
3. runoob Markdown教程 -runoob.com- https://www.runoob.com/markdown/md-tutorial.html


## 扩展阅读

1. Markdown 写作规范和格式规范 -腾讯云|开发者社区- https://cloud.tencent.com/developer/article/2087118  
2. Markdown 编写规范 -Github- https://github.com/fex-team/styleguide/blob/master/markdown.md
3. Markdown style guide -Github- https://github.com/google/styleguide/blob/gh-pages/docguide/style.md
4. 搭建 Markdown 强大写作环境（VSCode）-知乎- https://zhuanlan.zhihu.com/p/139140492
5. 计算机学生的第零课 -OrangeX4's Blog- https://orangex4.cool/post/lesson-zero-for-cs-students/



## 后续将继续更新...


