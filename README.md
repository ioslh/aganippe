# aganippe

> A high-efficiency and minimal markdown editor

#### Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build

# run unit & end-to-end tests
npm test


# lint all JS/Vue component files in `src/`
npm run lint

```

---

####TODO LIST

**语法实现**

- 段落和换行，两个或两个以上的空格再敲回车，或插入一个\<br/\>
- 标题，支持 atx 形式的标题，在行首插入 1 到 6 个 #，会生成对应的 h1~6 h 标签。在敲回车后再转换成 HTML，但是在编辑标题的时候，显示会加粗。标题支持嵌套其他 markdown 样式。支持嵌套的样式包括加粗、斜体、行内代码、链接、图片。
- 区块引用 Blockquotes，每行前面都加上 > ，支持嵌套区块引用，支持嵌套其他 markdown 语法，比如标题、列表、代码区块。区块引用会生成 blockquote 标签。
- 列表，有序列表和无需列表。无序列表使用 *、+、- 作为列表标记。有序列表使用数字加一个英文句点来标记。列表支持嵌套列表。列表支持嵌套区块引用，但仅限于行首，支持嵌套代码区块，但仅限于行首，支持其他 markdown 语法嵌套。
- 代码区块，代码区块中的 markdown 语法不再被转换。
- 分割线，你可以在一行中使用三个以上的 *、-、_ 来创建分割线。
- 链接，markdown 支持两种形式的链接，行内式、参考式。
- 图片，markdown 支持两种形式的图片，行内式、参考式。
- Markdown 中使用\*、\_ 来表示强调，使用一个用 em 标签，使用两个用 strong 标签，如果\*、\_ 两边都（？）有空白的话，会被当做普通的符号。
- 代码，如果标记一小段代码，可以用反引号标记：\`。如果文字中已经有反引号，那么使用两个反引号。
- 自动连接，使用\<\>包裹的链接会被转换为a 标签。
- 反斜线 \ 可以对如下字符转义：

```
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
```

- 表格支持。


**输出**

* 输出 markdown
* 输出 pdf
* 输出 html

**顶部菜单**

// 复制、黏贴、快捷键

**右键菜单**

// TODO

**打开、编辑、保存文件**

// TODO

终端打开

