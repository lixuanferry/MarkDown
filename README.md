# MarkDown-语法说明

## 一、标题

> \# 这是h1
>
> \## 这是h2
>
> \### 这是h3

## 二、区块引用

> \>This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

## 三、列表

### 3.1 无序列表

> \* Red
>
> \* Green
>
> \* Blue

等同于：

> \+ Red
>
> \+ Green
>
> \+ Blue

也等同于：

> \- Red
>
> \- Green
>
> \- Blue

### 3.2 有序列表

> 1. Bird
> 2. McHale
> 3. Parish

## 四、代码区块

缩进4个空格或是1个制表符

> 这是一个普通段落：
>
>     这是一个代码区块。

## 五、分割线

在一行中使用三个以上的星号、减号、底线来建立一个分割线

> \* \* \*
>
> \*\*\*
>
> \*\*\*\*\*
>
> \- \- \-
>
> \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

## 六、链接

### 6.1 行内式

> \[链接文字](htttp://example.com/"title")

### 6.2 参考式

>I get 10 times more traffic from [Google] [] than from
>[Yahoo] [2] or [MSN] [3].
>
>\[Google]: http://google.com/ "Google"
>
>\[2]: http://search.yahoo.com/ 'Yahoo Search'
>
>\[3]: http://search.msn.com/ (MSN Search)

## 七、强调

### 7.1 斜体

`<em>`

> \*斜体文字*

等同于：

> \_斜体文字_

### 7.2 加粗

`<strong>`

> \*\*加粗文字**

等同于：

> \_\_加粗文字__

## 八、代码

> \`printf()`

## 九、图片

### 9.1 行内式

> \!\[图片替代文字](http://example.com"title")

### 9.2 参考式

> \!\[Alt text][id]

## 十、自动链接

> \<http://example.com>
>
> \<address@example.com>
