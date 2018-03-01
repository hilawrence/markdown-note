# <a id="git-hub">Mastering Markdown - GitHub</a>&nbsp;&nbsp;[:point_left:][readme.note] #

* Markdown&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown]
  * 标题&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown.header]
  * 强调&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown.emphasis]
  * 列表&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown.list]
  * 图片&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown.image]
  * 链接&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown.link]
  * 引用&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown.quote]
  * 代码&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][markdown.code]
* GitHub Flavored Markdown&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm]
  * 高亮&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.highlight]
  * 任务&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.task]
  * 表格&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.table]
  * SHA&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.SHA]
  * Issue&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.issue]
  * @&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.mention]
  * 删除线&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.strikethrough]
  * emoji&nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][gfm.emoji]

## <a id="markdown"></a>Markdown&nbsp;&nbsp;[:point_up:][git-hub] ##

### <a id="markdown.header"></a>标题&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
# header1
###### header6
```

# header1
###### header6

### <a id="markdown.emphasis"></a>强调&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
*italic* _italic_  
**bold** __bold__
```

*italic* _italic_  
**bold** __bold__

### <a id="markdown.list"></a>列表&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
* Item 1
* Item 2
  * Item 2a
  * Item 2b
1. Item 1
1. Item 2
    1. Item 2a
    1. Item 2b
```

* Item 1
* Item 2
  * Item 2a
  * Item 2b
1. Item 1
1. Item 2
    1. Item 2a
    1. Item 2b

### <a id="markdown.image"></a>图片&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
![markdown](../image/markdown.jpg)
```

![markdown](../image/markdown.jpg)

### <a id="markdown.link">链接</a>&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
http://github.com  
[GitHub](http://github.com)
```

http://github.com  
[GitHub](http://github.com)

### <a id="markdown.quote"></a>引用&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
> quote
```

> quote

### <a id="markdown.code"></a>代码&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
`<h1>header1</h1>`
```

`<h1>header1</h1>`

## <a id="gfm"></a>GitHub Flavored Markdown&nbsp;&nbsp;[:point_up:][git-hub] ##

### <a id="gfm.highlight"></a>高亮&nbsp;&nbsp;[:point_up:][git-hub] ###

    ```javascript
    function doSomething() {
        do something ...
    }
    ```

```markdown
     function doSomething() {
        do something ...
    }
```

```javascript
function doSomething() {
    do something ...
}
```

    function doSomething() {
        do something ...
    }

### <a id="gfm.task"></a>任务&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
- [x] task1
- [] task
```

- [x] task1
- [] task

### <a id="gfm.table"></a>&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
| table header 1  |   table header 2  |   table header 3 |
|-----------------|:-----------------:|-----------------:|
| table cell left | table cell center | table cell right |
```

| table header 1  |   table header 2  |   table header 3 |
|-----------------|:-----------------:|-----------------:|
| table cell left | table cell center | table cell right |

### <a id="gfm.sha"></a>SHA&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
16c999e8c71134401a78d4d46435517b2271d6ac  
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac  
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```

16c999e8c71134401a78d4d46435517b2271d6ac  
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac  
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

### <a id="gfm.issue"></a>Issue&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
#1  
mojombo#1  
mojombo/github-flavored-markdown#1
```

#1  
mojombo#1  
mojombo/github-flavored-markdown#1

### <a id="gfm.mention"></a>@&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
@benjaminrencn
```

@benjaminrencn

### <a id="gfm.strikethrough"></a>删除线&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
~~strikethrough~~
```

~~strikethrough~~

### <a id="gfm.emoji"></a>Emoji&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown
:smiley_cat:
```

:smiley_cat:

<!--
* &nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][]
  * &nbsp;&nbsp;&nbsp;&nbsp;[:point_down:][]

## <a id=""></a>&nbsp;&nbsp;[:point_up:][git-hub] ##
### <a id=""></a>&nbsp;&nbsp;[:point_up:][git-hub] ###

```markdown

```

[]: # ""
-->

<!-- 链接 开始 -->
[git-hub]: #git-hub "Mastering Markdown - GitHub"
[readme.note]: ../README.md#note "README 笔记"
[markdown]: #markdown "Markdown"
[markdown.header]: #markdown.header "标题"
[markdown.emphasis]: #markdown.emphasis "强调"
[markdown.list]: #markdown.list "列表"
[markdown.image]: #markdown.image "图片"
[markdown.link]: #markdown.link "链接"
[markdown.quote]: #markdown.quote "引用"
[markdown.code]: #markdown.code "代码"
[gfm]: #gfm "GitHub Flavored Markdown"
[gfm.highlight]: #gfm.highlight "高亮"
[gfm.task]: #gfm.task "任务"
[gfm.table]: #gfm.table "表格"
[gfm.sha]: #gfm.sha "SHA"
[gfm.issue]: #gfm.issue "Issue"
[gfm.mention]: #gfm.mention "@"
[gfm.strikethrough]: #gfm.strikethrough "删除线"
[gfm.emoji]: #gfm.emoji "Emoji"
<!-- 链接 结束 -->