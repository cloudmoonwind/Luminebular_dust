> 标题语法
# Heading level 1
## 最多六级

段落语法
直接换行，或者空行，但块引用会按空行划分

> 块引用可以包含多个段落。为段落之间的空白行添加一个 > 符号
>
> 222


块引用可以嵌套。在要嵌套的段落前添加一个 >> 符号。
> 嵌套块引用
>
>>  ……

有序列表请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。
试试
1. aaa
  1.1. a
2. bbb

> 无序列表

- * + 均可，表示列表内的xx要在原基础上加四格缩进

代码块`反引号`,``这是转义反引号``。或者四格/一制表符缩进

超链接Markdown语法代码：[超链接显示名](超链接地址 "超链接title")

使用尖括号可以很方便地把URL或者email地址变成可点击的链接。
<https://markdown.com.cn>
<fake@example.com>

插入图片Markdown语法代码：![图片alt](图片链接 "图片title")。
对应的HTML代码：<img src="图片链接" alt="图片alt" title="图片title">

给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中。
[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)

转义字符：反斜杠字符 \ 

[内容来自markdown网页](https://markdown.com.cn/ )

防健忘，文件夹结构：
docs/
├── index.md
├── guide/
│   ├── index.md
│   ├── setup.md
│   └── img/               # 该章节专用图片
│       ├── setup-wizard.png
│       └── config-panel.png
├── reference/
│   ├── api.md
│   └── img/               # 另一个章节专用图片
│       └── endpoint-flow.png
├── shared/                # 多个章节共用的图片
│   ├── logo.png
│   └── banner.jpg
└── assets/                # 通用资源（CSS、下载文件等，可选）
    └── samples/
        └── demo.zip