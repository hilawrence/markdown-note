# <a id="wow-ubuntu">Markdown 语法说明 (简体中文版) - Wow!Ubuntu</a>&nbsp;&nbsp;[:point_left:][readme.note] #

* 区块元素&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block]
  * 段落&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block.paragraph]
  * 换行&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block.line-break]
  * 标题&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block.header]
  * 引用&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block.block-quote]
  * 列表&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block.list]
  * 代码&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block.code]
  * 分隔线&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][block.horizontal]
* 区段元素&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][span]
  * 链接&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][span.link]
  * 图片&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][span.image]
  * 强调&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][span.emphasis]
  * 代码&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][span.code]
* 其他&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][miscellaneous]
  * 反斜杠&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][miscellaneous.backslash]

## <a id="block"></a>区块元素&nbsp;&nbsp;[:point_up:][wow-ubuntu] ##

### <a id="block.paragraph"></a>段落&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
0 blank line
0 blank line

1 blank line


2 blank line
```

0 blank line
0 blank line

1 blank line


2 blank line

### <a id="block.line-break"></a>换行&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
1 space 
2 spaces  
3 spaces   
```

1 space 
2 spaces  
3 spaces   

### <a id="block.header"></a>标题&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
# header1 #
## hader2 ##
### header3 ###
#### header4 ####
##### heade5 #####
###### header6 ######
header1
=
header2
-
```

# header1 #
## hader2 ##
### header3 ###
#### header4 ####
##### heade5 #####
###### header6 ######
header1
=
header2
-

### <a id="block.block-quote"></a>引用&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
> quote
lazyquote
> > nested quote
>
> * support markdown
```

> quote
lazy quote
> > nested quote
>
> * support markdown

### <a id="block.list"></a>列表&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
- item
+ item
* item
  * item
    * item
1. item
1. item
    1. item
    1. item
        1. item
        3. item
1. paragraph
  
   pragraph

   > quote

        <p>code</p>

1. item
```

- item
+ item
* item
  * item
    * item
1. item
1. item
    1. item
    1. item
        1. item
        3. item
1. paragraph
  
   paragraph

   > quote

        <p>code</p>

1. item

### <a id="block.code"></a>代码&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
<p>paragraph</p>

    <p>paragraph</p>
```

<p>paragraph</p>

    <p>paragraph</p>

### <a id="block.horizontal"></a>分隔线&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
***
---
___
****
* * *
```

***
---
___
****
* * *

## <a id="span"></a>区段元素&nbsp;&nbsp;[:point_up:][wow-ubuntu] ##

### <a id="span.link"></a>链接&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
[inline](http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu")

<http://wowubuntu.com/markdown/index.html>

[reference][link-id]

[link-id]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"

[angle bracket][link-ab]  
[single quote][link-sq]
[double quotes][link-dq]  
[parenthesis][link-p]  
[case insensitivity][LINK-CI]  
[implicit][]

[link-ab]: <http://wowubuntu.com/markdown/index.html> "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-sq]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-dq]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-p]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-ci]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[implicit]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
```

[inline](http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu")

<http://wowubuntu.com/markdown/index.html>

[reference][link-id]

[link-id]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"

[angle bracket][link-ab]  
[single quote][link-sq]
[double quotes][link-dq]  
[parenthesis][link-p]  
[case insensitivity][LINK-CI]  
[implicit][]

[link-ab]: <http://wowubuntu.com/markdown/index.html> "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-sq]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-dq]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-p]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[link-ci]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[implicit]: http://wowubuntu.com/markdown/index.html "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"

### <a id="span.image"></a>图片&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
![markdown](../image/markdown.jpg "markdown")

![markdown][markdown]

[markdown]: ../image/markdown.jpg
```

![markdown](../image/markdown.jpg "markdown")

![markdown][markdown]

[markdown]: ../image/markdown.jpg

### <a id="span.emphasis"></a>强调&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
*single asterisk italic*  
_single underscore italic_  
**double asterisks bold**  
__double underscores bold__
```

*single asterisk italic*  
_single underscore italic_  
**double asterisks bold**  
__double underscores bold__

### <a id="span.code"></a>代码&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
`<h1>`  
`` `backtick quote` ``
```

`<h1>`  
`` `backtick quote` ``

## <a id="miscellaneous"></a>其他&nbsp;&nbsp;[:point_up:][wow-ubuntu] ##

### <a id="miscellaneous.backslash"></a>反斜杠&nbsp;&nbsp;[:point_up:][wow-ubuntu] ###

```markdown
\\ \` \* \_ \{ \} \[ \] \( \) \# \+ \- \. \!
```

\\ \` \* \_ \{ \} \[ \] \( \) \# \+ \- \. \!

<!-- 链接 开始 -->
[wow-ubuntu]: #wow-ubuntu "Markdown 语法说明 (简体中文版) - Wow!Ubuntu"
[readme.note]: ../README.md#note "README 笔记"
[block]: #block "区块元素"
[block.paragraph]: #block.paragraph "段落"
[block.line-break]: #block.line-break "换行"
[block.header]: #block.header "标题"
[block.block-quote]: #block.block-quote "引用"
[block.list]: #block.list "列表"
[block.code]: #block.code "代码"
[block.horizontal]: #block.horizontal "分隔线"
[span]: #span "区段元素"
[span.link]: #span.link "链接"
[span.image]: #span.image "图片"
[span.emphasis]: #span.emphasis "强调"
[span.code]: #span.emphasis "代码"
[miscellaneous]: #miscellaneous "其他"
[miscellaneous.backslash]: #miscellaneous.backslash "反斜杠"
<!-- 链接 结束 -->