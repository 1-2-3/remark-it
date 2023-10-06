# remark-it

markdown / html 幻灯片模板，基于 remarkjs.  
markdown / html slideshow template, powered by remarkjs.

简体中文 | [English](README-en_US.md)

## Demo

[中文 Demo](https://remark-it.now.sh)

[English Demo](https://remark-it.now.sh/index-en_US.html)

## 为什么选择 remark-it 制作幻灯片

- **可以直接插入SVG矢量图片**。当我们需要插入流程图、架构图等图示的时候，使用 [visio](https://www.microsoft.com/zh-cn/microsoft-365/visio/flowchart-software/) 或 [drawio](https://github.com/jgraph/drawio) 这类专业绘图软件要比PPT自带的工具好用太多，效率也更高。可惜都2020年了，PPT居然还不支持插入SVG图片。当我们需要插入 [visio](https://www.microsoft.com/zh-cn/microsoft-365/visio/flowchart-software/) 或 [drawio](https://github.com/jgraph/drawio) 绘制的图形时候，需要先导出为 `png` 图片，插入时稍有不慎就会变模糊。实际上 visio 和 drawio 都支持将绘图保存为可编辑 `svg` 格式，不但支持无损缩放，而且需要修改时可以直接打开 `svg` 文档进行编辑。
- **漂亮且一致的排版**。PPT的文本框真是太难用了！要想得到合适的行间距、项目符号和缩进需要耗费大量的时间进行调整，要想保持整个PPT文档排版的一致性也是很难的事情。
- **直接使用 markdown 撰写文档**。markdown 让我们可以使用很少的时间写出漂亮的文档。插入代码非常方便；支持基于 [Mermaid](https://github.com/knsv/mermaid) 的绘图语法和基于 [MathJax](https://github.com/mathjax/MathJax) 的公式语法。
- **对版本管理更加友好**。既然我们的正文和图形（svg本质是个xml文档）都是文本形式的，为什么不用 Git 将它们管起来呢？
- **便于互联网分享**。需要分享的时候，只要上传到 [github](https://github.com/) 就可以了。

## 不适合使用 remark-it 的情况

- 公司明确要求特定格式的模板。

- 帮老板做的PPT，老板还要接着改。

- 布局特别复杂的情况。

- 要求有过场动画等特效。

## 特性

- 全部资源支持离线访问
- [Remarkjs](https://github.com/gnab/remark) 功能示例
- 基于 [Typo.css](https://github.com/sofish/typo.css) 的中英文排版
- 基于 [Pure.css](https://github.com/pure-css/pure) 的多列布局
- 基于 [Nord](https://github.com/arcticicestudio/nord) 的暗色、亮色主题
- 基于 [Open color](https://github.com/yeun/open-color) 的 150 个文字和背景颜色
- 基于 [Vue.js](https://cn.vuejs.org/index.html) 的组件库
- 基于 [Mermaid](https://github.com/knsv/mermaid) 的 Markdown 图表
- 基于 [pangu.js](https://github.com/vinta/pangu.js) 的自动中英文混排。

## 安装

将项目整体 Clone 至本地，直接编辑 index.html 即可。

## 使用

双击 index.html 即可进行幻灯片演示。

![](/screenshots/11.png)
![](/screenshots/22.png)

## License

MIT
