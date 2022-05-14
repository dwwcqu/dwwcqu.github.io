## 欢迎来到我的主页
该仓库主要是在学习 Web 编程过程中，在 Github 上创建属于自己的个人网站的记录。
主要记录的记录内容分别包括:HTML, CSS 和 JavaScript，最终的目标是想通过 Web 技术创建属于自己的个人博客，在里面记录工作、学习中涉及到的相关技术。
### HTML
#### 什么是 HTML?
HTML(HyperText Markup Language) 不是一门编程语言，而是一种用来告知浏览器如何组织页面的标记语言。HTML 可复杂、可简单，一切取决于开发者。它由一系列的元素(elements)组成，这些元素可以用来包围不同部分的内容，使其以某种方式呈现或者工作。 一对标签( tags)可以为一段文字或者一张图片添加超链接，将文字设置为斜体，改变字号，等等。
> 注:HTML 标签不区分大小写。也就是说，输入标签时既可以使用大写字母也可以使用小写字母。例如，标签 <title\> 写作 <title\>、<TITLE\>、<Title\>、<TiTlE\>，等等都可以正常工作。不过，从一致性和可读性来讲，最好仅使用小写字母。
#### 一个 HTML 元素包括什么？
1. 开始标签(Opening tag):包含元素的名称，被左、右角括号所包围。表示元素从这里开始或者开始起作用。 
2. 结束标签(Closing tag):与开始标签相似，只是其在元素名之前包含了一个斜杠。这表示着元素的结尾。初学者常常会犯忘记包含结束标签的错误，这可能会产生一些奇怪的结果。 
3. 内容(Content):元素的内容，本例中就是所输入的文本本身。 
4. 元素(Element):开始标签、结束标签与内容相结合，便是一个完整的元素。
例如，以下这个一个标签:
```angular2html
<p>这是一个HTML的 p 标签元素</p>
```
#### HTML 基础教程
+ [HTML 简介](https://www.w3school.com.cn/html/html_jianjie.asp)
+ [HTML 编辑器](https://www.w3school.com.cn/html/html_editors.asp)
+ [基本的 HTML 标签](https://www.w3school.com.cn/html/html_basic.asp)
+ [HTML 元素](https://www.w3school.com.cn/html/html_elements.asp)
+ [HTML 属性](https://www.w3school.com.cn/html/html_attributes.asp)
+ [HTML 标题](https://www.w3school.com.cn/html/html_headings.asp)
+ [HTML 段落](https://www.w3school.com.cn/html/html_paragraphs.asp)
+ [HTML 样式](https://www.w3school.com.cn/html/html_styles.asp)
+ [HTML 文本格式化](https://www.w3school.com.cn/html/html_formatting.asp)
+ [HTML 引用](https://www.w3school.com.cn/html/html_quotation_elements.asp)
+ [HTML 注释](https://www.w3school.com.cn/html/html_comments.asp)
+ [HTML 颜色](https://www.w3school.com.cn/html/html_colors.asp)
+ [HTML 颜色名](https://www.w3school.com.cn/html/html_colornames.asp)
+ [HTML CSS](https://www.w3school.com.cn/html/html_css.asp)
  - 外部样式表;
  - 内部样式表;
  - 内联样式;
+ [HTML 链接](https://www.w3school.com.cn/html/html_links.asp)
+ [HTML 图像](https://www.w3school.com.cn/html/html_images.asp)
+ [HTML 表格](https://www.w3school.com.cn/html/html_tables.asp)
+ [HTML 列表](https://www.w3school.com.cn/html/html_lists.asp)
+ [HTML `<div>` 和 `<span>`](https://www.w3school.com.cn/html/html_blocks.asp): 可以通过 `<div>` 和 `<span>` 将 HTML 元素组合起来
  - HTML 块元素: “块级元素”译为 block level element, 如果与 CSS 一同使用，`<div>` 元素可用于对大的内容块设置样式属性;
  - HTML 内联元素: “内联元素”译为 inline element, 当与 CSS 一同使用时, `<span>` 元素可用于为部分文本设置样式属性;
+ [HTML 类](https://www.w3school.com.cn/html/html_classes.asp)
+ [HTML id 属性](https://www.w3school.com.cn/html/html_id.asp): HTML `id` 属性用于为 HTML 元素指定唯一的 `id`, 一个 HTML 文档中不能存在多个有相同 `id` 的元素
+ [HTML Iframe](https://www.w3school.com.cn/html/html_iframe.asp): iframe 用于在网页内显示网页
+ [HTML JavaScript](https://www.w3school.com.cn/html/html_script.asp): JavaScript 使 HTML 页面更具动态性和交互性, JavaScript 的常见用途是图像处理、表单验证和内容的动态更改
+ [HTML 文件路径](https://www.w3school.com.cn/html/html_filepaths.asp)
+ [HTML 头部元素](https://www.w3school.com.cn/html/html_head.asp): 
  - `<title>`: `<title>` 标签定义文档的标题;
  - `<base>`: `<base>` 标签为页面上的所有链接规定默认地址或默认目标(target);
  - `<link>`: `<link>` 标签定义文档与外部资源之间的关系, 最常用于连接样式表;
  - `<meta>`: `<meta>` 标签提供关于 HTML 文档的元数据, 元数据不会显示在页面上, 但是对于机器是可读的, 典型的情况是，`meta` 元素被用于规定**页面的描述**、**关键词**、**文档的作者**、**最后修改时间**以及其他元数据。
  - `<script>`: `<script>` 标签用于定义客户端脚本;
  - `<style>`: `<style>` 标签用于为 HTML 文档定义样式信息;
+ [HTML 布局](https://www.w3school.com.cn/html/html_layout.asp)
  - 使用 `<div>` 元素的 HTML 布局;
  - 使用 HTML5 的网站布局;
+ [HTML 响应式 Web 设计](https://www.w3school.com.cn/html/html_responsive.asp): RWD 指的是响应式 Web 设计(Responsive Web Design), RWD 能够以可变尺寸传递网页, RWD 对于平板和移动设备是必需的
  - 创建您自己的响应式设计;
  - 使用 Bootstrap;
+ [HTML 计算机代码元素](https://www.w3school.com.cn/html/html_computercode_elements.asp)
  - HTML 键盘格式: `<kbd>` 元素定义键盘输入;
  - HTML 样本格式: `<samp>` 元素定义计算机输出示例;
  - HTML 代码格式: HTML `<code>` 元素定义编程代码示例, `<code>` 元素不保留多余的**空格**和**折行**, 如需解决该问题，您必须在 `<pre>` 元素中包围代码;
  - HTML 变量格式化: HTML `<var>` 元素定义数学变量;
+ [HTML5 语义元素](https://www.w3school.com.cn/html/html5_semantic_elements.asp): 语义元素是拥有语义的元素, 语义元素清楚地向浏览器和开发者描述其意义
  - 非语义元素的例子：`<div>` 和 `<span>` - 无法提供关于其内容的信息;
  - 语义元素的例子：`<form>`、`<table>` 以及 `<img>` - 清晰地定义其内容;
  - HTML5 `<section>` 元素: `<section>` 元素定义文档中的节;
  - HTML5 `<article>` 元素: `<article>` 元素规定独立的自包含内容;
  - HTML5 `<header>` 元素: `<header>` 元素为文档或节规定页眉;
  - HTML5 `<footer>` 元素: `<footer>` 元素为文档或节规定页脚;
  - HTML5 `<nav>` 元素: `<nav>` 元素定义导航链接集合;
  - HTML5 `<aside>` 元素: `<aside>` 元素定义页面主内容之外的某些内容（比如侧栏）;
  - HTML5 `<figure>` 和 `<figcaption>` 元素: 在 `<figure>` 元素内，`<img>` 元素定义图像，`<figcaption>` 元素定义标题;
+ [HTML 5 样式指南和代码约定](https://www.w3school.com.cn/html/html5_syntax.asp)
  - 请使用小写元素名;
  - 关闭所有 HTML 元素;
  - 关闭空的 HTML 元素;
  - 使用小写属性名;
  - 属性值加引号;
  - 必需的属性;
  - 空格和等号;
  - 避免长代码行;
  - 空行和缩进;
+ [HTML 字符实体](https://www.w3school.com.cn/html/html_entities.asp): HTML 中的预留字符必须被替换为字符实体
+ [HTML 符号](https://www.w3school.com.cn/html/html_symbols.asp): 键盘上不存在的字符也可以由实体代替
+ [在 HTML 中使用表情符号](https://www.w3school.com.cn/html/html_emoji.asp): 表情符号（Emoji）是来自 UTF-8 字符集的字符
+ [HTML 编码(字符集)](https://www.w3school.com.cn/html/html_charset.asp): 为了正确显示 HTML 页面，Web 浏览器必须知道要使用哪个字符集
+ [HTML 统一资源定位器](https://www.w3school.com.cn/html/html_url.asp)
  - `scheme://host.domain:port/path/filename`;
  - `scheme` - 定义因特网服务的类型。最常见的类型是 `https`, `http`, `ftp`, `file`;
  - `host` - 定义域主机（`http` 的默认主机是 `www`）;
  - `domain` - 定义因特网域名，比如 `w3school.com.cn`;
  - `:port` - 定义主机上的端口号(`http` 的默认端口号是 80);
  - `path` - 定义服务器上的路径(如果省略，则文档必须位于网站的根目录中);
  - `filename` - 定义文档/资源的名称;
+ [HTML 框架](https://www.w3school.com.cn/html/html_frames.asp): 通过使用框架，你可以在同一个浏览器窗口中显示不止一个页面
+ [HTML 背景](https://www.w3school.com.cn/html/html_backgrounds.asp)
+ [HTML URL 字符编码](https://www.w3school.com.cn/html/html_urlencode.asp): URL 编码会将字符转换为可通过因特网传输的格式
  URL 只能使用 ASCII 字符集来通过因特网进行发送, 由于 URL 常常会包含 ASCII 集合之外的字符，URL 必须转换为有效的 ASCII 格式, URL 编码使用 "%" 其后跟随两位的十六进制数来替换非 ASCII 字符, URL 不能包含空格。URL 编码通常使用 + 来替换空格.
+ [HTML Web Server](https://www.w3school.com.cn/html/html_webserver.asp): 如果希望向世界发布您的网站，那么您必须把它存放在 web 服务器上
+ [HTML <!DOCTYPE>](https://www.w3school.com.cn/html/html_doctype.asp)
  <!DOCTYPE> 不是 HTML 标签。它为浏览器提供一项信息（声明），即 HTML 是用什么版本编写的。
+ [HTML 快速参考](https://www.w3school.com.cn/html/html_quick.asp)
#### HTML XHTML
+ [XHTML 简介](https://www.w3school.com.cn/html/html_xhtml.asp): XHTML 是以 XML 格式编写的 HTML
  - 如何从 HTML 转换到 XHTML： 1. 向每张页面的第一行添加 XHTML <!DOCTYPE>; 2. 向每张页面的 html 元素添加 xmlns 属性; 3. 把所有元素名改为小写;4. 关闭所有空元素;5. 把所有属性名改为小写;6. 为所有属性值加引号;
+ [XHTML - 元素](https://www.w3school.com.cn/html/html_xhtml_elements.asp): XHTML 元素是以 XML 格式编写的 HTML 元素
+ [XHTML - 属性](https://www.w3school.com.cn/html/html_xhtml_attributes.asp): XHTML 属性是以 XML 格式编写的 HTML 属性
#### HTML 表单
+ [HTML 表单](https://www.w3school.com.cn/html/html_forms.asp): HTML 表单用于搜集不同类型的用户输入
  - `<form>` 元素;
  - `<input>` 元素: `type`=`text`, `submit`, `radio`;
  - `action` 属性: `action` 属性定义在提交表单时执行的动作, 向服务器提交表单的通常做法是使用提交按钮, 如果省略 `action` 属性，则 `action` 会被设置为当前页面;
  - `method` 属性: `method` 属性规定在提交表单时所用的 HTTP 方法（`GET` 或 `POST`）;`GET` 最适合少量数据的提交。浏览器会设定容量限制, `POST` 的安全性更好，因为在页面地址栏中被提交的数据是不可见的;
  - `name` 属性: 如果要正确地被提交，每个输入字段必须设置一个 `name` 属性;
  - 用 `<fieldset>` 组合表单数据: `<fieldset>` 元素组合表单中的相关数据, `<legend>` 元素为 `<fieldset>` 元素定义标题;
+ [HTML 表单属性](https://www.w3school.com.cn/html/html_forms_attributes.asp)
  - `autocomplete` 属性: `autocomplete` 属性规定表单是否应打开自动完成功能;启用自动完成功能后，浏览器会根据用户之前输入的值自动填写值;
  - `novalidate` 属性: novalidate 属性是一个布尔属性, 如果已设置，它规定提交时不应验证表单数据;
+ [HTML 表单元素](https://www.w3school.com.cn/html/html_form_elements.asp)
  - `<input>` 元素;
  - `<select>` 元素（下拉列表）;
  - `<textarea>` 元素;
  - `<button>` 元素;
  - HTML5 `<datalist>` 元素: `<datalist>` 元素为 `<input>` 元素规定预定义选项列表, `<input>` 元素的 `list` 属性必须引用 `<datalist>` 元素的 `id` 属性;
+ [HTML 输入类型](https://www.w3school.com.cn/html/html_form_input_types.asp)
  - `<input type="text">`: 定义供文本输入的单行输入字段;
  - `<input type="password"> `: 定义密码字段;
  - `<input type="submit">`: 定义提交表单数据至表单处理程序的按钮;
  - `<input type="radio"> `: 定义单选按钮;
  - `<input type="checkbox"> `: 定义复选框;
  - `<input type="button> `: 定义按钮;
  - `<input type="number"> `: 用于应该包含数字值的输入字段, 输入限制: 
  - `<input type="date">`: 用于应该包含日期的输入字段;
  - `<input type="color">`: 用于应该包含颜色的输入字段;
  - `<input type="range">`: 用于应该包含一定范围内的值的输入字段;
  - `<input type="month">`: 允许用户选择月份和年份;
  - `<input type="week">`: 允许用户选择周和年;
  - `<input type="time">`: 允许用户选择时间（无时区）;
  - `<input type="datetime">`: 允许用户选择日期和时间（有时区）;
  - `<input type="datetime-local">`: 允许用户选择日期和时间（无时区）;
  - `<input type="email">`: 用于应该包含电子邮件地址的输入字段;
  - `<input type="search">`: 用于搜索字段(搜索字段的表现类似常规文本字段);
  - `<input type="tel">`: 用于应该包含电话号码的输入字段;
  - `<input type="url">`: 用于应该包含 URL 地址的输入字段;
+ [HTML Input 属性](https://www.w3school.com.cn/html/html_form_attributes.asp)
  - `value` 属性: 规定输入字段的初始值;
  - `readonly` 属性: 规定输入字段为只读（不能修改）, `readonly` 属性不需要值。它等同于 `readonly="readonly"`;
  - `disabled` 属性: 规定输入字段是禁用的, 被禁用的元素是不可用和不可点击的, 被禁用的元素不会被提交;
  - `size` 属性: 规定输入字段的尺寸（以字符计）;
  - `maxlength` 属性: 规定输入字段允许的最大长度;
  - `autocomplete` 属性: 规定表单或输入字段是否应该自动完成, 当自动完成开启，浏览器会基于用户之前的输入值自动填写值;
  - `novalidate` 属性属于` <form>` 属性: 如果设置，则 `novalidate` 规定在提交表单时不对表单数据进行验证;
  - `autofocus` 属性: `autofocus` 属性是布尔属性, 如果设置，则规定当页面加载时 `<input>` 元素应该自动获得焦点;
  - `formaction` 属性： 规定当提交表单时处理该输入控件的文件的 URL;
  - `height` 和 `width` 属性: 属性规定 `<input>` 元素的高度和宽度;
  - `list` 属性: 引用的 `<datalist>` 元素中包含了 `<input>` 元素的预定义选项;
  - `min` 和` max` 属性: 规定 `<input>` 元素的最小值和最大值, 适用于如需输入类型：`number`、`range`、`date`、`datetime`、`datetime-local`、`month`、`time` 以及 `week`;
  - `multiple` 属性: 是布尔属性, 如果设置，则规定允许用户在 `<input>` 元素中输入一个以上的值;
  - `pattern` 属性: 规定用于检查 `<input>` 元素值的正则表达式, 适用于以下输入类型：`text`、`search`、`url`、`tel`、`email`、和 `password`;
  - `placeholder` 属性: 规定用以描述输入字段预期值的提示（样本值或有关格式的简短描述）, 适用于以下输入类型：`text`、`search`、`url`、`tel`、`email`、和 `password`;
  - `required` 属性: 是布尔属性，如果设置，则规定在提交表单之前必须填写输入字段;
  - `step` 属性: `step` 属性规定 `<input>` 元素的合法数字间隔, 适用于如需输入类型：`number`、`range`、`date`、`datetime`、`datetime-local`、`month`、`time` 以及 `week`;
+ [HTML `input` `form` 属性](https://www.w3school.com.cn/html/html_form_attributes_form.asp)
  - `input` 的 `form` 属性规定 `<input>` 元素所属的表单;
  - 此属性的值必须等于它所属的 `<form>` 元素的 `id` 属性;
  - `formaction` 属性: `input` 的 `formaction` 属性规定当提交表单时，对输入（数据）进行处理的文件的 URL, 该属性会覆盖 `<form>` 元素的 `action` 属性, 适用于以下输入类型：`submit` 和 `image`;
  - `formenctype` 属性: `input` 的 `formenctype` 属性指定提交时应如何编码表单数据（仅适用于 `method="post"` 的表单）, 此属性将覆盖 `<form>` 元素的 `enctype` 属性, 适用于以下输入类型：`submit` 和 `image`;
  - `formmethod` 属性: `input` 的 `formmethod` 属性定义了将表单数据发送到 `action` URL 的 HTTP 方法, 将覆盖 `<form>` 元素的 `method` 属性, 适用于以下输入类型：`submit` 和 `image`;
  - `formtarget` 属性: `input` 的 `formtarget` 属性指定一个名称或关键字，该名称或关键字规定在提交表单后在何处显示收到的响应, 此属性将覆盖 `<form>` 元素的 `target` 属性, 适用于以下输入类型：`submit` 和 `image`;
  - `formnovalidate` 属性: `input` 的 `formnovalidate` 属性规定提交时不应验证 `<input>` 元素, 此属性将覆盖 `<form>` 元素的 `novalidate` 属性, 适用于以下输入类型：`submit`;
  - `novalidate` 属性: `novalidate` 属性是 `<form>` 属性, 如果已设置，`novalidate` 属性规定在提交时不应验证所有表单数据;
#### HTML 图形
+ [HTML5 画布(HTML5 Canvas)](https://www.w3school.com.cn/html/html5_canvas.asp): `canvas` 元素用于在网页上绘制图形
#### HTML 媒体
+ [HTML 多媒体](https://www.w3school.com.cn/html/html_media.asp): Web 上的多媒体指的是音效、音乐、视频和动画
#### HTML5
+ [HTML5 简介](https://www.w3school.com.cn/html/html5_intro.asp)
+ [HTML5 浏览器支持](https://www.w3school.com.cn/html/html5_browsers.asp)
+ [HTML5 新元素](https://www.w3school.com.cn/html/html5_new_elements.asp)
+ [HTML5 迁移](https://www.w3school.com.cn/html/html5_migration.asp)
#### HTML5 API
+ [HTML5 地理定位](https://www.w3school.com.cn/html/html5_geolocation.asp)
#### HTML 参考手册
+ [HTML 标签参考手册](https://www.w3school.com.cn/tags/index.asp)
+ [HTML 标签参考手册 - 功能排序](https://www.w3school.com.cn/tags/html_ref_byfunc.asp)
+ [HTML 参考手册 - 浏览器支持](https://www.w3school.com.cn/tags/html_ref_html_browsersupport.asp)
+ [HTML 全局属性](https://www.w3school.com.cn/tags/html_ref_standardattributes.asp)
+ [HTML 事件参考手册](https://www.w3school.com.cn/tags/html_ref_eventattributes.asp)
+ [HTML 颜色名](https://www.w3school.com.cn/tags/html_ref_colornames.asp)
+ [HTML Canvas 参考手册](https://www.w3school.com.cn/tags/html_ref_canvas.asp)
+ [HTML 音频/视频参考手册](https://www.w3school.com.cn/tags/html_ref_audio_video_dom.asp)
+ [HTML 字符集](https://www.w3school.com.cn/tags/html_ref_charactersets.asp)
+ [HTML `<!DOCTYPE>`](https://www.w3school.com.cn/tags/html_ref_dtd.asp)
+ [HTML URL 编码参考手册](https://www.w3school.com.cn/tags/html_ref_urlencode.asp)
+ [HTML 语言代码参考手册](https://www.w3school.com.cn/tags/html_ref_language_codes.asp)
+ [HTML ISO 国家/地区代码参考手册](https://www.w3school.com.cn/tags/html_ref_country_codes.asp)
+ [HTML 状态消息](https://www.w3school.com.cn/tags/html_ref_httpmessages.asp)
+ [HTML 请求方法](https://www.w3school.com.cn/tags/html_ref_httpmethods.asp)
+ [键盘快捷键](https://www.w3school.com.cn/tags/html_ref_keyboardshortcuts.asp)
#### HTML 总要总结
+ HTML 文档是由 HTML 元素定义的, HTML 元素指的是从开始标签（start tag）到结束标签（end tag）的所有代码, HTML 文档由嵌套的 HTML 元素构成;
+ 使用空的段落标记 `<p></p>` 去插入一个空行是个坏习惯。用 `<br />` 标签代替它！(但是不要用 `<br />` 标签去创建列表。)
+ `id` 名称对大小写敏感, `id` 必须包含至少一个字符，且不能包含空白字符（空格、制表符等）;
+ 关于 GET 的注意事项：
  - 以名称/值对的形式将表单数据追加到 URL;
  - 永远不要使用 GET 发送敏感数据！（提交的表单数据在 URL 中可见！）;
  - URL 的长度受到限制（2048 个字符）;
  - 对于用户希望将结果添加为书签的表单提交很有用;
  - GET 适用于非安全数据，例如 Google 中的查询字符串;
+ 关于 POST 的注意事项：
  - 将表单数据附加在 HTTP 请求的正文中（不在 URL 中显示提交的表单数据）;
  - POST 没有大小限制，可用于发送大量数据;
  - 带有 POST 的表单提交无法添加书签;
  - 如果表单数据包含敏感信息或个人信息，请务必使用 POST;
### XML
XML 指可扩展标记语言, XML 被设计用来传输和存储数据.
#### XML 简单教程
+ [XML 简介](https://www.w3school.com.cn/xml/xml_intro.asp)
  - XML 指*可扩展标记语言*（E**X**tensible **M**arkup **L**anguage）;
  - XML 是一种**标记语言**，很类似 HTML;
  - XML 的设计宗旨是**传输数据**，而非显示数据
  - XML 标签没有被预定义。您需要**自行定义标签**;
  - XML 被设计为具有自我描述性;
  - XML 是 W3C 的推荐标准;
  - XML 不是 HTML 的替代, XML 和 HTML 为不同的目的而设计: XML 被设计为传输和存储数据，其焦点是数据的内容, HTML 被设计用来显示数据，其焦点是数据的外观, HTML 旨在显示信息，而 XML 旨在传输信息;
  - XML 是不作为的: 没有任何行为, XML 被设计用来结构化、存储以及传输信息. 它仅仅是包装在 XML 标签中的纯粹的信息。我们需要编写软件或者程序，才能传送、接收和显示出这个文档;
  - XML 仅仅是纯文本: XML 没什么特别的, 它仅仅是纯文本而已, 有能力处理纯文本的软件都可以处理 XML;
  - 通过 XML 您可以发明自己的标签: XML 没有预定义的标签, 在 HTML 中使用的标签（以及 HTML 的结构）是预定义的。HTML 文档只使用在 HTML 标准中定义过的标签（比如 `<p>` 、`<h1>` 等等）, XML 允许创作者定义自己的标签和自己的文档结构
  - XML 不是对 HTML 的替代: XML 是对 HTML 的补充, 在大多数 web 应用程序中，XML 用于传输数据，而 HTML 用于格式化并显示数据, 对 XML 最好的描述是: **XML 是独立于软件和硬件的信息传输工具**;
  - XML 无所不在: XML 是各种应用程序之间进行数据传输的最常用的工具，并且在信息存储和描述领域变得越来越流行;
+ [XML 的用途](https://www.w3school.com.cn/xml/xml_usedfor.asp): XML 应用于 web 开发的许多方面，常用于简化数据的存储和共享
  - XML 把数据从 HTML 分离: 如果你需要在 HTML 文档中显示动态数据，那么每当数据改变时将花费大量的时间来编辑 HTML, 通过 XML，数据能够存储在独立的 XML 文件中。这样你就可以专注于使用 HTML 进行布局和显示，并确保修改底层数据不再需要对 HTML 进行任何的改变. 通过使用几行 JavaScript，你就可以读取一个外部 XML 文件，然后更新 HTML 中的数据内容;
  - XML 简化数据共享: XML 数据以纯文本格式进行存储，因此提供了一种独立于软件和硬件的数据存储方法, 让创建不同应用程序可以共享的数据变得更加容易;
  - XML 简化数据传输: 通过 XML，可以在不兼容的系统之间轻松地交换数据;
  - XML 简化平台的变更;
  - XML 使您的数据更有用: 由于 XML 独立于硬件、软件以及应用程序，XML 使您的数据更可用，也更有用;
+ [XML 树结构](https://www.w3school.com.cn/xml/xml_tree.asp): XML 文档形成了一种树结构，它从“根部”开始，然后扩展到“枝叶”
  - XML 文档形成一种树结构: XML 文档必须包含根元素, 该元素是所有其他元素的父元素, XML 文档中的元素形成了一棵文档树, 这棵树从根部开始，并扩展到树的最底端;
  ```xml
    <root>
        <child>
            <subchild></subchild>
        </child>
    </root>
  ```
  <img src="images/ct_nodetree1.gif">

  ```xml
    <bookstore>
      <book category="COOKING">
        <title lang="en">Everyday Italian</title> 
        <author>Giada De Laurentiis</author> 
        <year>2005</year> 
        <price>30.00</price> 
      </book>
      <book category="CHILDREN">
        <title lang="en">Harry Potter</title> 
        <author>J K. Rowling</author> 
        <year>2005</year> 
        <price>29.99</price> 
      </book>
      <book category="WEB">
        <title lang="en">Learning XML</title> 
        <author>Erik T. Ray</author> 
        <year>2003</year> 
        <price>39.95</price> 
      </book>
    </bookstore>
  ```
+ [XML 语法规则](https://www.w3school.com.cn/xml/xml_syntax.asp)
  - 所有 XML 元素都须有关闭标签;
  - XML 标签对大小写敏感;
  - XML 必须正确地嵌套;
  - XML 文档必须有根元素;
  - XML 的属性值须加引号;
  - 实体引用;
  - XML 中的注释;
  - 在 XML 中，空格会被保留: HTML 会把多个连续的空格字符裁减（合并）为一个, 在 XML 中，文档中的空格不会被删节;
  - XML 以 LF 存储换行;
+ [XML 元素](https://www.w3school.com.cn/xml/xml_elements.asp): XML 文档包含 XML 元素
  - XML 命名规则: 可使用任何名称，没有保留的字词, 名称可以含字母、数字以及其他的字符, 名称不能以数字或者标点符号开始, 名称不能以字符 “xml”（或者 XML、Xml）开始, 名称不能包含空格;
  - 最佳命名习惯;
  - XML 元素是可扩展的: XML 元素是可扩展，以携带更多的信息;
+ [XML 属性](https://www.w3school.com.cn/xml/xml_attributes.asp): XML 元素可以在开始标签中包含属性，类似 HTML, 属性 (Attribute) 提供关于元素的额外（附加）信息
  - XML 属性必须加引号;
  - XML 元素 vs. 属性: 没有什么规矩可以告诉我们什么时候该使用属性，而什么时候该使用子元素。我的经验是在 HTML 中，属性用起来很便利，但是在 XML 中，您应该尽量避免使用属性。如果信息感觉起来很像数据，那么请使用子元素吧;
  - 避免 XML 属性: 1. 属性无法包含多重的值（元素可以）; 2. 属性无法描述树结构（元素可以）;3. 属性不易扩展（为未来的变化); 4. 属性难以阅读和维护;
  - 针对元数据的 XML 属性: 元数据（有关数据的数据）应当存储为属性，而数据本身应当存储为元素;
+ [XML 验证](https://www.w3school.com.cn/xml/xml_dtd.asp): 拥有正确语法的 XML 被称为“形式良好”的 XML, 通过 DTD 验证的 XML 是“合法”的 XML
  - 形式良好的 XML 文档;
  - 验证 XML 文档: 合法的 XML 文档是“形式良好”的 XML 文档，同样遵守文档类型定义 (DTD) 的语法规则;
  - XML DTD;
  - XML Schema
+ [XML 验证器](https://www.w3school.com.cn/xml/xml_validator.asp)
+ [查看 XML 文件](https://www.w3school.com.cn/xml/xml_view.asp)
+ [使用 CSS 显示 XML](https://www.w3school.com.cn/xml/xml_display.asp): 通过使用 CSS，可为 XML 文档添加显示信息
+ [使用 XSLT 显示 XML](https://www.w3school.com.cn/xml/xml_xsl.asp): 通过使用 XSLT，您可以向 XML 文档添加显示信息
#### XML JavaScript
+ [XMLHttpRequest 对象](https://www.w3school.com.cn/xml/xml_http.asp): `XMLHttpRequest` 对象用于在后台与服务器交换数据
+ [XML 解析器](https://www.w3school.com.cn/xml/xml_parser.asp): 所有现代浏览器都内建了供读取和操作 XML 的 XML 解析器, 解析器把 XML 转换为 XML DOM 对象 - 可通过 JavaScript 操作的对象
  - 解析 XML 文档;
  - 解析 XML 字符串;
+ [XML DOM](https://www.w3school.com.cn/xml/xml_dom.asp): DOM （Document Object Model，文档对象模型）定义了访问和操作文档的标准方法
  - XML DOM;
  - HTML DOM;
+ [XML to HTML](https://www.w3school.com.cn/xml/xml_to_html.asp): 如何把 XML 数据显示为 HTML
#### XML 高级
### CSS
CSS 是一种描述 HTML 文档样式的语言, CSS 描述应该如何显示 HTML 元素.
#### CSS 基础教程
+ [CSS 简介](https://www.w3school.com.cn/css/css_jianjie.asp)
  - CSS 指的是层叠样式表 (**C**ascading **S**tyle **S**heets);
  - CSS 描述了如何在屏幕、纸张或其他媒体上显示 HTML 元素;
  - CSS 节省了大量工作。它可以同时控制多张网页的布局;
  - 外部样式表存储在 CSS 文件中
+ [CSS 语法](https://www.w3school.com.cn/css/css_syntax.asp)
  CSS 规则集（rule-set）由选择器和声明块组成:
  <img src="images/selector.gif">
  选择器指向您需要设置样式的 HTML 元素, 声明块包含一条或多条用分号分隔的声明, 每条声明都包含一个 CSS 属性名称和一个值，以冒号分隔, 多条 CSS 声明用分号分隔，声明块用花括号括起来.
+ [CSS 选择器](https://www.w3school.com.cn/css/css_selectors.asp)
  - CSS 元素选择器: 元素选择器根据元素名称来选择 HTML 元素;
  - CSS id 选择器: id 选择器使用 HTML 元素的 id 属性来选择特定元素, 元素的 id 在页面中是唯一的，因此 id 选择器用于选择一个唯一的元素, 要选择具有特定 id 的元素，请写一个井号（＃），后跟该元素的 id(id 名称不能以数字开头);
  - CSS 类选择器: 类选择器选择有特定 class 属性的 HTML 元素, 如需选择拥有特定 class 的元素，请写一个句点（.）字符，后面跟类名;
  - CSS 通用选择器: 通用选择器（`*`）选择页面上的所有的 HTML 元素;
  - CSS 分组选择器: 分组选择器选取所有具有相同样式定义的 HTML 元素, 最好对选择器进行分组，以最大程度地缩减代码, 如需对选择器进行分组，请用逗号来分隔每个选择器;
+ [如何添加 CSS](https://www.w3school.com.cn/css/css_shiyong.asp): 当浏览器读到样式表时，它将根据样式表中的信息来格式化 HTML 文档
  - 层叠顺序: 页面中的所有样式将按照以下规则“层叠”为新的“虚拟”样式表，其中第一优先级最高: 1. 行内样式（在 HTML 元素中）;2. 外部和内部样式表（在 head 部分）;3. 浏览器默认样式. 因此，行内样式具有最高优先级，并且将覆盖外部和内部样式以及浏览器默认样式;
+ [CSS 注释](https://www.w3school.com.cn/css/css_comments.asp)
+ [CSS 颜色](https://www.w3school.com.cn/css/css_colors.asp)
  + [CSS RGB 颜色](https://www.w3school.com.cn/css/css_colors_rgb.asp)
  + [CSS HEX 颜色](https://www.w3school.com.cn/css/css_colors_hex.asp)
  + [CSS HSL 颜色 hsla(hue, saturation, lightness)](https://www.w3school.com.cn/css/css_colors_hsl.asp)
    - 色相（hue）是色轮上从 0 到 360 的度数。0 是红色，120 是绿色，240 是蓝色;
    - 饱和度（saturation）是一个百分比值，0％ 表示灰色阴影，而 100％ 是全色
    - 亮度（lightness）也是百分比，0％ 是黑色，50％ 是既不明也不暗，100％是白色
+ [CSS 背景](https://www.w3school.com.cn/css/css_background.asp): CSS 背景属性用于定义元素的背景效果;
  - CSS `background-color`;
  - 不透明度 / 透明度: `opacity`;
  - [CSS 背景图像](https://www.w3school.com.cn/css/css_background_image.asp)
  - [CSS 背景重复](https://www.w3school.com.cn/css/css_background_repeat.asp)
    - CSS `background-repeat`;
    - CSS `background-repeat: no-repeat`;
    - CSS `background-position`;
  - [CSS 背景附着](https://www.w3school.com.cn/css/css_background_attachment.asp): `background-attachment` 属性指定背景图像是应该滚动还是固定的（不会随页面的其余部分一起滚动）
  - [CSS 背景简写](https://www.w3school.com.cn/css/css_background_shorthand.asp): 在使用简写属性时，属性值的顺序为：`background-color`, `background-image`, `background-repeat`, `background-attachment`, `background-position`
+ [CSS 边框](https://www.w3school.com.cn/css/css_border.asp)
  - CSS `border` 属性允许您指定元素边框的样式、宽度和颜色;
  - CSS 边框样式: `border-style` 属性指定要显示的边框类型, 除非设置了 `border-style` 属性，否则其他 CSS 边框属性都不会有任何作用;
    - [CSS 边框宽度](https://www.w3school.com.cn/css/css_border_width.asp): `border-width` 属性可以设置一到四个值（用于上边框、右边框、下边框和左边框)
    - [CSS 边框颜色](https://www.w3school.com.cn/css/css_border_color.asp): `border-color` 属性用于设置四个边框的颜色, 如果未设置 border-color，则它将继承元素的颜色
    - [CSS 边框各边](https://www.w3school.com.cn/css/css_border_sides.asp): `border-width` 和 `border-color` 也同样适用
    - [CSS 简写边框属性](https://www.w3school.com.cn/css/css_border_shorthand.asp): `border` 属性是以下各个边框属性的简写属性: `border-width`, `border-style(必需)`, `border-color`
    - [CSS 圆角边框](https://www.w3school.com.cn/css/css_border_rounded.asp): `border-radius` 属性用于向元素添加圆角边框
+ [CSS 外边距](https://www.w3school.com.cn/css/css_margin.asp): CSS `margin` 属性用于在任何定义的边框之外，为元素周围创建空间
  - [CSS 外边距合并](https://www.w3school.com.cn/css/css_margin_collapse.asp): 外边距合并指的是，当两个垂直外边距相遇时，它们将形成一个外边距, 合并后的外边距的高度等于两个发生合并的外边距的高度中的较大者
+ [CSS 内边距](https://www.w3school.com.cn/css/css_padding.asp): CSS `padding` 属性用于在任何定义的边界内的元素内容周围生成空间
+ [CSS 高度和宽度](https://www.w3school.com.cn/css/css_dimension.asp): `height` 和 `width` 属性用于设置元素的高度和宽度, `height` 和 `width` 属性不包括内边距、边框或外边距。它设置的是元素内边距、边框以及外边距内的区域的高度或宽度
+ [CSS 框模型](https://www.w3school.com.cn/css/css_boxmodel.asp)
  - 所有 HTML 元素都可以视为方框。在 CSS 中，在谈论设计和布局时，会使用术语“盒模型”或“框模型”;
  - CSS 框模型实质上是一个包围每个 HTML 元素的框。它包括：外边距、边框、内边距以及实际的内容, 如下所示：
    <img src="images/boxmodel.gif">
  - 元素总宽度 = 宽度 + 左内边距 + 右内边距 + 左边框 + 右边框 + 左外边距 + 右外边距;
  - 元素总高度 = 高度 + 上内边距 + 下内边距 + 上边框 + 下边框 + 上外边距 + 下外边距;
+ [CSS 轮廓](https://www.w3school.com.cn/css/css_outline.asp)
  - [CSS 轮廓宽度](https://www.w3school.com.cn/css/css_outline_width.asp)
  - [CSS 轮廓颜色](https://www.w3school.com.cn/css/css_outline_color.asp)
  - [CSS 轮廓简写](https://www.w3school.com.cn/css/css_outline_shorthand.asp)
  - [CSS 轮廓偏移](https://www.w3school.com.cn/css/css_outline_offset.asp)
+ [CSS 文本](https://www.w3school.com.cn/css/css_text.asp)
  - [CSS 文本对齐](https://www.w3school.com.cn/css/css_text_align.asp)
  - [CSS 文字装饰](https://www.w3school.com.cn/css/css_text_decoration.asp)
  - [CSS 文本转换](https://www.w3school.com.cn/css/css_text_transformation.asp)
  - [CSS 文字间距](https://www.w3school.com.cn/css/css_text_spacing.asp)
  - [CSS 文本阴影](https://www.w3school.com.cn/css/css_text_shadow.asp)
+ [CSS 字体](https://www.w3school.com.cn/css/css_font.asp)
  - [CSS 字体大小](https://www.w3school.com.cn/css/css_font_size.asp)
  - [CSS 谷歌字体](https://www.w3school.com.cn/css/css_font_google.asp)
  - [CSS 字体属性](https://www.w3school.com.cn/css/css_font_shorthand.asp)
+ [CSS 图标](https://www.w3school.com.cn/css/css_icons.asp)
+ [CSS 链接](https://www.w3school.com.cn/css/css_link.asp)
+ [CSS 列表](https://www.w3school.com.cn/css/css_list.asp)
+ [CSS 表格](https://www.w3school.com.cn/css/css_table.asp)
#### CSS 中级教程

#### CSS 重点总结
+ 使用 opacity 属性为元素的背景添加透明度时，其所有子元素都继承相同的透明度。这可能会使完全透明的元素内的文本难以阅读;
+ 只有普通文档流中块框的垂直外边距才会发生外边距合并。行内框、浮动框或绝对定位之间的外边距不会合并;
+ 请记住，`height` 和 `width` 属性不包括内边距、边框或外边距！它们设置的是元素的内边距、边框和外边距内的区域的高度/宽度;
+ 
### JavaScript
#### JavaScript 简单教程
+ [数组](https://www.w3school.com.cn/js/js_arrays.asp)
  + [数组方法](https://www.w3school.com.cn/js/js_array_methods.asp)
  + [JavaScript 数组排序](https://www.w3school.com.cn/js/js_array_sort.asp)
  + [JavaScript 数组迭代](https://www.w3school.com.cn/js/js_array_iteration.asp):数组迭代方法对每个数组项进行操作。
    - `Array.forEach()`;
    - `Array.map()`;
    - `Array.filter()`;
    - `Array.reduce()`;
    - `Array.reduceRight()`;
    - `Array.every()`;
    - `Array.some()`;
    - `Array.indexOf()`;
    - `Array.lastIndexOf()`;
    - `Array.find()`;
    - `Array.findIndex()`
  + [JavaScript 数组 Const](https://www.w3school.com.cn/js/js_array_const.asp)
+ [JavaScript 日期](https://www.w3school.com.cn/js/js_dates.asp)
  + [JavaScript 日期格式](https://www.w3school.com.cn/js/js_date_formats.asp)
  + [JavaScript 日期获取方法](https://www.w3school.com.cn/js/js_date_methods.asp):日期方法允许您获取并设置日期值(年、月、日、时、分、秒、毫秒)
    - `getTime()`;
    - `getFullYear()`;
    - `getHours()`;
    - `getMonth()`;
    - `getSeconds()`;
    - `getDate()`
  + [JavaScript 日期设置方法](https://www.w3school.com.cn/js/js_date_methods_set.asp):使用“设置日期”方法可以设置日期对象的日期值(年、月、日、小时、分钟、秒、毫秒)
    - `setTime()`;
    - `setSeconds()`;
    - `setMonth()`;
    - `setMinutes()`;
    - `setMilliseconds()`;
    - `setHours()`;
    - `setFullYear()`;
    - `setDate()`
+ [JavaScript 数学](https://www.w3school.com.cn/js/js_math.asp):JavaScript `Math` 对象允许您对数字执行数学任务
  - `Math.PI`;
  - `Math.round()`;
  - `Math.pow()`;
  - `Math.sqrt()`;
  - `Math.abs()`;
  - `Math.ceil()`;
  - `Math.floor()`;
  - `Math.sin()`;
  - `Math.cos()`;
  - `Math.min()` 和 `Math.max()`;
  - `Math.random()`;
  - `Math.exp(x)`;
+ [JavaScript 随机](https://www.w3school.com.cn/js/js_random.asp)
+ [JavaScript 逻辑](https://www.w3school.com.cn/js/js_booleans.asp):JavaScript 布尔(逻辑)代表两个值之一:`true` 或 `false`
  + [JavaScript 比较](https://www.w3school.com.cn/js/js_comparisons.asp):比较和逻辑运算符用于测试 true 或 false
  + [JavaScript 条件](https://www.w3school.com.cn/js/js_if_else.asp):条件语句用于基于不同条件执行不同的动作
  + [JavaScript Switch 语句](https://www.w3school.com.cn/js/js_switch.asp):`switch` 语句用于基于不同条件执行不同动作
+ [JavaScript For 循环](https://www.w3school.com.cn/js/js_loop_for.asp):循环可多次执行代码块
  - `for` 循环;
  - `for/in` 循环;
  - `while` 循环;
  - `do/while`;
+ [JavaScript `for in`](https://www.w3school.com.cn/js/js_loop_forin.asp):JavaScript `for in` 语句循环遍历对象的属性
+ [JavaScript `for of`](https://www.w3school.com.cn/js/js_loop_forof.asp):JavaScript `for of` 语句循环遍历可迭代对象的值
+ [JavaScript `while` 循环](https://www.w3school.com.cn/js/js_loop_while.asp):只要条件为 true，循环能够一直执行代码块
+ [JavaScript `break` 和 `continue`](https://www.w3school.com.cn/js/js_break.asp):`break` 语句“跳出”循环，`continue` 语句“跳过”循环中的一个迭代
+ [JavaScript `typeof`](https://www.w3school.com.cn/js/js_typeof.asp)
  - `typeof`
    - 5 种不同的可以包含值的数据类型: `string`, `number`, `boolean`, `object`, `function` 
    - 6 种类型的对象: `String`, `Data`, `Array`, `Object`, `Number`, `Boolean`
    - 2 种不能包含值的数据类型: `null`, `undefined`
  - `constructor` 属性;
+ [JavaScript 类型转换](https://www.w3school.com.cn/js/js_type_conversion.asp)
  - `Number()` 转换数值;
  - `String()` 转换字符串;
  - `Boolean()` 转换布尔值;
  - 自动类型转换:如果 JavaScript 尝试操作一种“错误”的数据类型，它会试图将该值转换为“正确”的类型
  - 自动字符串转换:当您试图“输出”对象或变量时，JavaScript 自动调用变量的 `toString()` 函数
+ [JavaScript 位运算符](https://www.w3school.com.cn/js/js_bitwise.asp)
+ [JavaScript 正则表达式](https://www.w3school.com.cn/js/js_regexp.asp):正则表达式是构成搜索模式的字符序列，该搜索模式可用于文本搜索和文本替换操作
  - `search()`;
  - `replace()`;
  - `test()`;
  - `exec()`;
+ [JavaScript 错误 - Throw 和 Try to Catch](https://www.w3school.com.cn/js/js_errors.asp)
  - `try` 语句使您能够测试代码块中的错误;
  - `catch` 语句允许您处理错误;
  - `throw` 语句允许您创建自定义错误;
  - `finally` 使您能够执行代码，在 `try` 和 `catch` 之后，无论结果如何;
  - `EvalError` ---> `SyntaxError`
  - `RangeError`;
  - `ReferenceError`;
  - `TypeError`;
  - `URIError`;
+ [JavaScript 作用域](https://www.w3school.com.cn/js/js_scope.asp):指的是您有权访问的变量集合，作用域决定了从代码不同部分对**变量**、**对象**和**函数**的可访问性。
  - 全局作用域:全局作用域形成了完整的 JavaScript 环境，在 HTML 中，全局作用域是 window，所有全局变量均属于 window 对象;
  - 局部作用域;
  - JavaScript 函数作用域;
  - 自动全局:如果您为**尚未声明**(未使用 `var`, `let`, `const` 关键字)的变量赋值，此变量会自动成为全局变量;
+ [JavaScript Hoisting](https://www.w3school.com.cn/js/js_hoisting.asp):提升(Hoisting)是 JavaScript 将声明移至顶部的默认行为
+ [JavaScript 严格模式](https://www.w3school.com.cn/js/js_strict.asp):`use strict` 定义 JavaScript 代码应该以“严格模式”执行，例如:在严格模式中，您无法使用未声明的变量
+ [JavaScript this 关键词](https://www.w3school.com.cn/js/js_this.asp):JavaScript `this` 关键词指的是它所属的对象
  - 方法中的 `this`:指的是此方法的“拥有者”;
  - 单独的 `this`:全局对象，在浏览器窗口中，全局对象是 `[object Window]`;
  - 函数中的 `this`(默认):指的是全局对象 `[object Window]`;
  - 函数中的 `this`(严格模式):是未定义的(`undefined`);
  - 事件处理程序中的 `this`:在 HTML 事件处理程序中，`this` 指的是接收此事件的 HTML 元素;
  - 对象方法绑定;
  - 显式函数绑定;
+ [JavaScript 箭头函数](https://www.w3school.com.cn/js/js_arrow_function.asp)
+ [JavaScript 类](https://www.w3school.com.cn/js/js_classes.asp):JavaScript 类是 JavaScript 对象的模板
  - `constructor()`;
+ [JavaScript JSON(JavaScript Object Notation)](https://www.w3school.com.cn/js/js_json.asp):JSON 是存储和传输数据的格式，经常在数据从服务器发送到网页时使用
  - JSON 语法规则;
+ [JavaScript 调试](https://www.w3school.com.cn/js/js_debugging.asp)
+ [JavaScript 样式指南](https://www.w3school.com.cn/js/js_conventions.asp)
  - 变量名;
  - 运算符周围的空格;
  - 代码缩进;
  - 语句规则;
  - 对象规则;
  - 行长度小于 80;
  - 命名约定;
  - 在 HTML 中加载 JavaScript;
  - 使用小写文件名;
+ [JavaScript 常见错误](https://www.w3school.com.cn/js/js_mistakes.asp)
  - 意外使用赋值运算符;
  - 期望松散的比较:有一个常见的错误是忘记在 switch 语句中使用严格比较;
  - 令人困惑的加法和级联;
  - 令人误解的浮点;
  - 对 JavaScript 字符串换行;
  - 错位的分号;
  - 对 return 语句进行换行;
  - `undefined` 不是 `null`;
+ [JavaScript 性能](https://www.w3school.com.cn/js/js_performance.asp)
  - 减少循环中的活动;
  - 减少 DOM 访问;
  - 缩减 DOM 规模;
  - 避免不必要的变量;
  - 延迟 JavaScript 加载:请把脚本放在页面底部，使浏览器首先加载页面;
  - 避免使用 with;
+ [JavaScript 保留字](https://www.w3school.com.cn/js/js_reserved.asp)
#### [JavaScript 版本](https://www.w3school.com.cn/js/js_versions.asp)
+ [JavaScript ES5](https://www.w3school.com.cn/js/js_es5.asp)
+ [JavaScript ES6](https://www.w3school.com.cn/js/js_es6.asp)
+ [JavaScript 历史](https://www.w3school.com.cn/js/js_history.asp)
#### JavaScript 对象
+ [JavaScript 对象定义](https://www.w3school.com.cn/js/js_object_definition.asp)
  - JavaScript 原始值: string, number, boolean, null, undefined;
  - 对象是包含变量的变量:**名称 : 值**对的形式编写;
  - 对象属性:JavaScript 对象中的命名值，被称为属性;
  - 对象方法:方法是可以在对象上执行的动作;
  - 创建 JavaScript 对象
    - 使用对象字面量;
    - 使用 JavaScript 关键词 `new`:出于简易性、可读性和执行速度的考虑，请使用第一种创建方法(对象文字方法);
  - JavaScript 对象是易变的:它们通过**引用**来寻址，而非值;
+ [JavaScript 对象属性](https://www.w3school.com.cn/js/js_object_properties.asp)
  - 访问 JavaScript 属性;
  - JavaScript `for...in` 循环;
  - 添加新属性;
  - 删除属性;
+ [JavaScript 对象方法](https://www.w3school.com.cn/js/js_object_methods.asp):方法是存储为对象属性的函数。
  - 访问对象方法;
  - 使用内建方法;
  - 添加新的方法:向对象添加方法是在构造器函数内部完成的;
+ [JavaScript 显示对象](https://www.w3school.com.cn/js/js_object_display.asp)
  - 使用 `Object.values()`;
  - 使用 `JSON.stringify()`;
+ [JavaScript 对象访问器](https://www.w3school.com.cn/js/js_object_accessors.asp)
+ [JavaScript 对象构造器](https://www.w3school.com.cn/js/js_object_constructors.asp)
  - 对象类型(蓝图)(类):用大写首字母对构造器函数命名是个好习惯;
+ [JavaScript 对象原型](https://www.w3school.com.cn/js/js_object_prototypes.asp):所有 JavaScript 对象都从原型继承属性和方法
  - 原型继承:日期对象继承自 `Date.prototype`,数组对象继承自 `Array.prototype`,`Object.prototype` 位于原型继承链的顶端;
  - 使用 prototype 属性;
+ [JavaScript ES5 对象方法](https://www.w3school.com.cn/js/js_object_es5.asp)
  - 管理对象;
  - 保护对象;
  - 更改属性值;
  - 更改元数据;
  - 列出可枚举的属性;
  - 添加属性;
  - 添加 Getter 和 Setter;
+ [JavaScript `Map` 对象](https://www.w3school.com.cn/js/js_object_maps.asp)
+ [JavaScript `Set` 对象](https://www.w3school.com.cn/js/js_object_sets.asp)
#### JavaScript 函数
+ [JavaScript 函数定义](https://www.w3school.com.cn/js/js_function_definition.asp)
  - 函数声明;
  - 函数表达式;
  - Function() 构造器;
  - 函数提升;
  - 自调用函数;
  - 函数是对象;
+ [JavaScript 函数参数](https://www.w3school.com.cn/js/js_function_parameters.asp):JavaScript 函数不会对参数值进行任何检查
  - `arguments` 对象: JavaScript 函数有一个名为 arguments 对象的内置对象;
  - 参数通过值传递;
  - 对象是由引用传递的;
+ [JavaScript 函数调用](https://www.w3school.com.cn/js/js_function_invocation.asp):JavaScript 函数内部的代码会在“某物”调用它时执行
  - 以函数形式调用函数;
  - this 关键词;
  - 作为方法来调用函数;
  - 通过函数构造器来调用函数:如果函数调用的前面是 `new` 关键字，那么这是一个构造函数调用;
+ [JavaScript 函数 `call`](https://www.w3school.com.cn/js/js_function_call.asp):使用 `call()` 方法，您可以编写能够在不同对象上使用的方法
  - JavaScript `call()` 方法:它可以用来调用所有者对象作为参数的方法, 通过 `call()`，您能够使用属于另一个对象的方法;
  - 带参数的 `call()` 方法;
+ [JavaScript 函数 `apply`](https://www.w3school.com.cn/js/js_function_apply.asp):通过 apply() 方法，您能够编写用于不同对象的方法
+ [JavaScript 闭包](https://www.w3school.com.cn/js/js_function_closures.asp):全局变量能够通过闭包实现局部(私有)
#### JavaScript 类
+ [JavaScript 类的简介](https://www.w3school.com.cn/js/js_class_intro.asp)
  - JavaScript 类的语法;
+ [JavaScript 类继承](https://www.w3school.com.cn/js/js_class_inheritance.asp)
+ [JavaScript Static 方法](https://www.w3school.com.cn/js/js_class_static.asp)
#### JavaScript Async
+ [JavaScript 回调](https://www.w3school.com.cn/js/js_callback.asp)
+ [异步的 JavaScript](https://www.w3school.com.cn/js/js_asynchronous.asp)
+ [JavaScript `Promise`](https://www.w3school.com.cn/js/js_promise.asp)
  - JavaScript `Promise` 对象;
+ [JavaScript Async](https://www.w3school.com.cn/js/js_async.asp)
#### JavaScript HTML DOM
+ [DOM(**D**ocument **O**bject **M**odel, 文档对象模型)简介](https://www.w3school.com.cn/js/js_htmldom.asp):通过 HTML DOM，JavaScript 能够访问和改变 HTML 文档的所有元素, HTML DOM 是关于如何获取、更改、添加或删除 HTML 元素的标准。
  - HTML DOM 树;
    <img src="images/dom_htmltree.gif" width="1028"/>
  - JavaScript 能改变页面中的所有 HTML 元素;
  - JavaScript 能改变页面中的所有 HTML 属性;
  - JavaScript 能改变页面中的所有 CSS 样式;
  - JavaScript 能删除已有的 HTML 元素和属性;
  - JavaScript 能添加新的 HTML 元素和属性;
  - JavaScript 能对页面中所有已有的 HTML 事件作出反应;
  - JavaScript 能在页面中创建新的 HTML 事件;
+ [JavaScript - HTML DOM 方法](https://www.w3school.com.cn/js/js_htmldom_methods.asp):HTML DOM 方法是您能够(在 HTML 元素上)执行的动作, HTML DOM 属性是您能够设置或改变的 HTML 元素的值
+ [JavaScript HTML DOM 文档](https://www.w3school.com.cn/js/js_htmldom_document.asp):HTML DOM 文档对象是您的网页中所有其他对象的拥有者
  - 查找 HTML 元素;
  - 改变 HTML 元素;
  - 添加事件处理程序;
  - 查找 HTML 对象;
+ [JavaScript HTML DOM 元素](https://www.w3school.com.cn/js/js_htmldom_elements.asp):查找和访问 HTML 页面中的 HTML 元素
  - 通过 `id` 查找 HTML 元素;
  - 通过标签名查找 HTML 元素;
  - 通过类名查找 HTML 元素;
  - 通过 CSS 选择器查找 HTML 元素;
  - 通过 HTML 对象选择器查找 HTML 对象:`document.forms`, `document.images`, `document.links`, ...
+ [JavaScript HTML DOM - 改变 HTML](https://www.w3school.com.cn/js/js_htmldom_html.asp)
+ [JavaScript 表单](https://www.w3school.com.cn/js/js_validation.asp)
  - JavaScript 表单验证;
  - JavaScript 可以验证数字输入;
  - 自动 HTML 表单验证;
  - 数据验证;
  - HTML 约束验证;
+ [JavaScript HTML DOM - 改变 CSS](https://www.w3school.com.cn/js/js_htmldom_css.asp):HTML DOM 允许 JavaScript 更改 HTML 元素的样式
+ [JavaScript HTML DOM 动画](https://www.w3school.com.cn/js/js_htmldom_animate.asp):使用 JavaScript 来创建 HTML 动画
+ [JavaScript HTML DOM 事件](https://www.w3school.com.cn/js/js_htmldom_events.asp):HTML DOM 允许 JavaScript 对 HTML 事件作出反应
  - 对事件作出反应;
  - HTML 事件属性;
  - `onload` 和 `onunload` 事件;
  - `onchange` 事件;
  - `onmouseover` 和 `onmouseout` 事件;
  - `onmousedown`, `onmouseup` 以及 `onclick` 事件;
+ [JavaScript HTML DOM 事件监听程序](https://www.w3school.com.cn/js/js_htmldom_eventlistener.asp)
  - `addEventListener()` 方法;
  - 向元素添加事件处理程序;
  - 向相同元素添加多个事件处理程序;
  - 向 `window` 对象添加事件处理程序;
  - 事件冒泡还是事件捕获?
  - `removeEventListener()` 方法;
+ [JavaScript HTML DOM 导航](https://www.w3school.com.cn/js/js_htmldom_navigation.asp):通过 HTML DOM，您能够使用节点关系来导航节点树
  - DOM 节点;
  - 节点关系;
  - 在节点之间导航:`parentNode`, `childNodes[nodenumber]`, `firstChild`, `lastChild`, `nextSibling`, `previousSibling`;
  - DOM 根节点:`document.body `, `document.documentElement`;
  - `nodeName` 属性;
  - `nodeValue` 属性;
  - `nodeType` 属性;
+ [JavaScript HTML DOM 元素(节点)](https://www.w3school.com.cn/js/js_htmldom_nodes.asp):添加和删除节点(HTML 元素)
  - 创建新 HTML 元素(节点);
  - 创建新 HTML 元素 - `insertBefore()`;
  - 删除已有 HTML 元素;
  - 删除子节点;
  - 替换 HTML 元素:`replaceChild()`;
+ [JavaScript HTML DOM 集合](https://www.w3school.com.cn/js/js_htmldom_collections.asp)
  - HTMLCollection 对象:`getElementsByTagName()` 方法返回 HTMLCollection 对象, HTMLCollection 并非数组;
+ [JavaScript HTML DOM 节点列表](https://www.w3school.com.cn/js/js_htmldom_nodelist.asp)
  - HTML DOM NodeList 对象:NodeList 对象是从文档中提取的节点列表(集合);
#### JS Browser BOM(**B**rowser **O**bject **M**odel):允许 JavaScript 与浏览器对话
+ [JavaScript `window` - 浏览器对象模型](https://www.w3school.com.cn/js/js_window.asp)
  - `window` 对象:全局变量是 `window` 对象的属性, 全局函数是 `window` 对象的方法,甚至（HTML DOM 的）`document` 对象也是 `window` 对象属性;
  - 窗口尺寸;
  - 其他窗口方法:`window.open()`, `window.close()`, `window.moveTo()`, `window.resizeTo()`;
+ [JavaScript Window Screen](https://www.w3school.com.cn/js/js_window_screen.asp):`window.screen` 对象包含用户屏幕的信息
+ [JavaScript Window Location](https://www.w3school.com.cn/js/js_window_location.asp):`window.location` 对象可用于获取当前页面地址（URL）并把浏览器重定向到新页面
+ [JavaScript Window History](https://www.w3school.com.cn/js/js_window_history.asp):`window.history` 对象包含浏览器历史
+ [JavaScript Window Navigator](https://www.w3school.com.cn/js/js_window_navigator.asp):`window.navigator` 对象包含有关访问者的信息
+ [JavaScript 弹出框](https://www.w3school.com.cn/js/js_popup.asp):JavaScript 有三种类型的弹出框：警告框、确认框和提示框
+ [JavaScript Timing 事件](https://www.w3school.com.cn/js/js_timing.asp):JavaScript 可以在时间间隔内执行
  - Timing 事件:`setTimeout()` 方法, `clearTimeout()` 方法, `setInterval()` 方法, `clearInterval()` 方法
+ [JavaScript Cookies](https://www.w3school.com.cn/js/js_cookies.asp):Cookie 让您在网页中存储用户信息
#### JavaScript Web API
+ [Web API - 简介](https://www.w3school.com.cn/js/js_api_intro.asp):扩展浏览器的功能, 极大简化复杂的功能, 为复杂的代码提供简单的语法
+ [JavaScript 验证 API](https://www.w3school.com.cn/js/js_validation_api.asp)
  - 约束验证 DOM 方法;
  - 约束验证 DOM 属性;
  - 有效性属性;
+ [Web History API](https://www.w3school.com.cn/js/js_api_history.asp)
+ [Web Storage API](https://www.w3school.com.cn/js/js_api_web_storage.asp)
  - `localStorage` 对象;
  - `sessionStorage` 对象;
+ [Web Worker API](https://www.w3school.com.cn/js/js_api_web_workers.asp):Web Worker 是在后台运行的 JavaScript，不会影响页面的性能
+ [JavaScript Fetch API](https://www.w3school.com.cn/js/js_api_fetch.asp):Fetch API 接口允许 Web 浏览器向 Web 服务器发出 HTTP 请求, 不再需要 XMLHttpRequest
+ [Web Geolocation API](https://www.w3school.com.cn/js/js_api_geolocation.asp)
#### JavaScript AJAX(**A**synchronous **J**avaScript **A**nd **X**ML)
+ [AJAX 简介](https://www.w3school.com.cn/js/js_ajax_intro.asp)
+ [AJAX - `XMLHttpRequest` 对象](https://www.w3school.com.cn/js/js_ajax_http.asp)
  - 创建 `XMLHttpRequest` 对象;
  - `XMLHttpRequest` 对象方法;
  - `XMLHttpRequest` 对象属性;
+ [AJAX 请求](https://www.w3school.com.cn/js/js_ajax_http_send.asp)
+ [AJAX - 服务器响应](https://www.w3school.com.cn/js/js_ajax_http_response.asp)
#### JavaScript 的重要总结
+ 所有 JavaScript 对象都拥有 `toString()` 方法;
+ `sort()` 方法是最强大的数组方法之一，默认地，`sort()` 函数按照字符串顺序对值进行排序，对于数值排序，需要加上一个**比值函数**，按照**比值函数**的结果对数组进行特定排序;
+ JavaScript 不提供查找数组中最大或最小数组值的内建函数。不过，在对数组进行排序之后，您能够使用索引来获得最高或最低值，仅仅需要找到最高或最低值，对整个数组进行排序是效率极低的方法。
+ 您可以使用 `Math.max.apply` 来查找数组中的最高值，可以使用 `Math.min.apply` 来查找数组中的最低值，当然，你可以定义自己的查找最大、最小值函数;
+ 所有具有“真实”值的即为 `True`，所有不具有“真实”值的即为 `false`;
+ 不要创建布尔对象。它会拖慢执行速度。 `new` 关键词会使代码复杂化，并产生某些意想不到的结果。当使用 `==` 运算符时，相等的布尔是相等的，当使用 `===` 运算符时，相等的布尔是不相等的，因为 `===` 运算符需要在类型和值两方面同时相等。
+ 比较两个 JavaScript 对象将始终返回 `false`，JavaScript 对象无法进行比较;
+ `switch case` 使用严格比较(===): 值必须与要匹配的类型相同，只有操作数属于同一类型时，严格比较才能为 true;
+ 您可以检查 `constructor` 属性以确定对象是否为数组(包含 "`Array`" 一词);
+ 使用 `null` 来清除对象，使用 `undefined` 来清除原始值;
+ 为了避免 bug，请始终在每个作用域的开头声明所有变量;
+ JavaScript 类中，请始终添加 constructor() 方法;
+ 请避免**全局变量**、`new`、`===`、`eval()`(`eval()` 函数用于将文本作为代码来允许)，意识到自动类型转换，用 default 来结束 switch;
+ JavaScript 变量不是**易变**的。只有 JavaScript 对象如此;
+ 请使用对象字面量 `{}` 代替 `new Object()`;
+ 请使用字符串字面量 `""` 代替 `new String()`;
+ 请使用数值字面量代替 `new Number()`;
+ 请使用布尔字面量代替 `new Boolean()`;
+ 请使用数组字面量 `[]` 代替 `new Array()`;
+ 请使用模式字面量代替 `new RexExp()`;
+ 请使用函数表达式 `() {}` 代替 `new Function()`;
+ 大多数情况下，您可以避免在 JavaScript 中使用 new 关键词;
+ JavaScript 函数参数规则:1、JavaScript 函数定义不会为参数(`parameter`)规定数据类型;2、JavaScript 函数不会对所传递的参数(`argument`)实行类型检查;3、JavaScript 函数不会检查所接收参数(argument)的数量;
+ 不通过关键词 var 创建的变量总是全局的，即使它们在函数中创建;
+ 类中的语法必须以“严格模式”编写, 如果您不遵循“严格模式”规则，将收到错误消息;
+ static 类方法是在类本身上定义的, 您不能在对象上调用 `static` 方法，只能在对象类上调用;
+ 当网页被加载时，浏览器会创建页面的`文档对象模型`(Document Object Model);
+ 