# remark-it

markdown / html slideshow template, powered by remarkjs.

English | [简体中文](README.md)

## Demo

[中文 Demo](https://remark-it.now.sh)

[English Demo](https://remark-it.now.sh/index-en_US.html)

## Why should you choose remark-it

- **Support for direct use of SVG images.** When we need to insert flow chart or architecture diagram, use [visio](https://www.microsoft.com/zh-cn/microsoft-365/visio/flowchart-software/) or [drawio](https://github.com/jgraph/drawio) this kind of professional drawing software is more effective. Unfortunately, until 2020, PPT doesn't even support inserting SVG images. If we need to insert images produced by [visio](https://www.microsoft.com/zh-cn/microsoft-365/visio/flowchart-software/) or [drawio](https://github.com/jgraph/drawio), we need export `PNG` images first,  when inserting into PPT, a little carelessness will cause the picture to be blurred. In fact, both Visio and Drawio support saving drawings to editable `SVG` format, which not only supports lossless scaling, but also allows you to directly open the `SVG` document for editing when changes are needed.

- **Beautiful and consistent typography.** Powerpoint text boxes are so hard to use! Getting the right line spacing, bullet points, and indentation takes a lot of time, and it's hard to keep the layout consistent throughout the whole presentation.

- **Write down your points directly by markdown.** Markdown allows us to write beautiful documents in very little time, and inserting code is very convenient. And drawing syntax of [Mermaid](https://github.com/knsv/mermaid) and  formula based on [MathJax](https://github.com/mathjax/MathJax) is supported.

- **More version-friendly.** Since both the doc and the graphics (`SVG`is essentially an XML document) are textual, why not manage them with `Git`?

- **Easy to share on the Internet**. When you need to share your slides, just upload it to [github](https://github.com/).

## Why shouldn't you choose remark-it

- Your company explicitly require templates in a specific format.

- When you help your boss with the powerpoint presentation, he has to change it.

- When the layout is particularly complex.

- Special effects such as cut scenes are required.

## Features

- All resources support offline access
- [Remarkjs](https://github.com/gnab/remark) Samples
- English and Chinese typography, powered by [Typo.css](https://github.com/sofish/typo.css)
- Multi-column layouts, powered by [Pure.css](https://github.com/pure-css/pure)
- Dark ann light theme, powered by [Nord](https://github.com/arcticicestudio/nord)
- 150 text and background colors, powered by [Open color](https://github.com/yeun/open-color)
- Components powered by [Vue.js](https://cn.vuejs.org/index.html)
- Markdown Diagrams powered by [Mermaid](https://github.com/knsv/mermaid)
- Automatic mixing typesetting in both English and Chinese powered by [pangu.js](https://github.com/vinta/pangu.js)

## Installation

Clone the whole project and edit index.html.

## Usage

Double-click on index.html for a slide presentation.

![](/screenshots/111.png)
![](/screenshots/222.png)

## License

MIT
