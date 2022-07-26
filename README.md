# Markdown语法

## 标题

创建标题，几级标题，前面就有多少个`#`号。

语法：

``` md
# 一级标题
## 二级标题
### 三级标题
```

## 文本样式

### 粗体

语法：`** **`或`_ _`

键盘快捷键：`CTRL`+`B`

样式：**粗体**

```md
**粗体**
```

### 斜体

语法：`* *`或`- -`

键盘快捷键：`CTRL`+`I`

样式：*斜体*

```md
*斜体*
```

### 删除线

语法：`~~ ~~`

样式：~~删除线~~

```md
~~删除线~~
```

### 粗体和嵌入的斜体

语法：`** **`和`* *`

样式：**这是*斜体*的**

```md
**这是*斜体*的**
```

### 全部粗体和斜体

语法：`*** ***`

样式：***都是斜体和粗体***

```md
***都是斜体和粗体***
```

### 下标

语法：`<sub> </sub>`

样式：<sub>下标文本</sub>

```md
<sub>下标文本</sub>
```

### 上标

语法：`<sup> </sup>`

样式：<sup>上标文本</sup>

```md
<sup>上标文本</sup>
```

## 公式

语法：`$ $`或

```md
$$ 

$$
```

样式：

$F=ma$

```md
$F=ma$
```

$$
F=ma
$$

```md
$$
F=ma
$$
```

## 引用文本

语法:`>`

样式:
>引用文本
>
>引用文本
>
>引用文本
>
>引用文本
>
>引用文本

```md
>引用文本
>
>引用文本
>
>引用文本
>
>引用文本
>
>引用文本
```

## 引用代码

语法:一行用` `` `,多行用` ``` ``` `

键盘快捷键:`CTRL`+`E`

样式:`引用的代码`

```md
第一行
第二行
第三行
```

## 链接

语法:把链接文本包含在`[ ]`内,然后将URL包含在`( )`内

键盘快捷键:`CTRL`+`K`

样式:[百度](https://www.baidu.com)

```md
[百度](https://www.baidu.com)
```

## 图像

语法:添加`!`然后在`[ ]`中放alt文本文件,把图像链接放在`( )`中

样式:![图片](https://i0.hdslb.com/bfs/album/37aa35b7702d7b481785e00e58b1e0f813c19c7a.jpg)

```md
![图片](https://i0.hdslb.com/bfs/album/37aa35b7702d7b481785e00e58b1e0f813c19c7a.jpg)
```

## 列表

语法:`-`或`+`

样式:

```md
- 第一行
- 第二行
- 第三行
```

- 第一行
- 第二行
- 第三行
  
```md
+ 第一
+ 第二
```

- 第一
- 第二
