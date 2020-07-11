# HTML 标签

* [注释](#注释)
* [a](#a)
* [abbr](#abbr)
* [address](#address)
* [area](#area)
* [article](#article)
* [aside](#aside)
* [audio](#audio)
* [b](#b)
* [base](#base)
* [bdi](#bdi)
* [bdo](#bdo)
* [blockquote](#blockquote)
* [body](#body)
* [br](#br)
* [button](#button)
* [canvas](#canvas)
* [caption](#caption)
* [cite](#cite)
* [code](#code)
* [col](#col)
* [colgroup](#colgroup)
* [datalist](#datalist)
* [dd](#dd)
* [del](#del)
* [details](#details)
* [dfn](#dfn)
* [dialog](#dialog)
* [div](#div)
* [dl](#dl)
* [dt](#dt)
* [em](#em)
* [embed](#embed)
* [fieldset](#fieldset)
* [figcaption](#figcaption)
* [figure](#figure)
* [footer](#footer)
* [form](#form)
* [h1](#h1)
* [h2](#h2)
* [h3](#h3)
* [h4](#h4)
* [h5](#h5)
* [h6](#h6)
* [head](#head)
* [header](#header)
* [hgroup](#hgroup)
* [hr](#hr)
* [html](#html)
* [i](#i)
* [iframe](#iframe)
* [img](#img)
* [input](#input)
* [ins](#ins)
* [kbd](#kbd)
* [label](#label)
* [legend](#legend)
* [li](#li)
* [link](#link)
* [main](#main)
* [map](#map)
* [mark](#mark)
* [meta](#meta)
* [meter](#meter)
* [nav](#nav)
* [noscript](#noscript)
* [object](#object)
* [ol](#ol)
* [optgroup](#optgroup)
* [option](#option)
* [output](#output)
* [p](#p)
* [param](#param)
* [pre](#pre)
* [progress](#progress)
* [q](#q)
* [rp](#rp)
* [rt](#rt)
* [ruby](#ruby)
* [s](#s)
* [samp](#samp)
* [script](#script)
* [section](#section)
* [select](#select)
* [small](#small)
* [source](#source)
* [span](#span)
* [strong](#strong)
* [style](#style)
* [sub](#sub)
* [summary](#summary)
* [sup](#sup)
* [table](#table)
* [tbody](#tbody)
* [td](#td)
* [textarea](#textarea)
* [tfoot](#tfoot)
* [th](#th)
* [thead](#thead)
* [time](#time)
* [title](#title)
* [tr](#tr)
* [track](#track)
* [u](#u)
* [ul](#ul)
* [var](#var)
* [video](#video)
* [wbr](#wbr)

## 注释

> 注释标签用来在源文档中插入注释，注释不会在浏览器中显示，可以使用注释对代码进行解释，这样做有助于在以后的时间对代码的编辑，特别是代码量很大的情况下很有用。

语法：

```html
<!-- 这是一段注释，注释不会在浏览器中显示。 -->
<p>这是一段普通的段落。</p>
```

效果：

<section>
    <!-- 这是一段注释，注释不会在浏览器中显示。 -->
    <p>这是一段普通的段落。</p>
</section>

## a

> a 标签用于定义超链接，作用是从一个页面链接到另一个页面。

语法：

```html
<a href="https://github.com/">GitHub</a>
```

效果：

<section>
    <a href="https://github.com/">GitHub</a>
</section>

## abbr

> abbr 标签用来表示一个缩写词或者首字母缩略词。

语法：

```html
The <abbr title="People's Republic of China">PRC</abbr> was founded in 1949.
```

效果：

<section>
    The <abbr title="People's Republic of China">PRC</abbr> was founded in 1949.
</section>

## address

> 使用 address 标签来定义地址，签名或者文档的作者身份。

语法：

```html
<address>Written by <a href="mailto:example@example.com">Kuriv Vesti</a> .</address>
```

效果：

<section>
    <address>Written by <a href="mailto:example@example.com">Kuriv Vesti</a> .</address>
</section>

## area

> area 标签定义图像映射内部的区域。

语法：

```html
<img src="planets.jpg" alt="planets" usemap="#planets">

<map name="planets">
    <area shape="rect" coords="0,0,110,260" href="planets_sun.gif" alt="Sun">
    <area shape="circle" coords="129,161,10" href="planets_merglobe.gif" alt="Mercury">
    <area shape="circle" coords="180,139,14" href="planets_venus.gif" alt="Venus">
</map>
```

效果：

<section>
    <img src="planets.jpg" alt="planets" usemap="#planets">

    <map name="planets">
        <area shape="rect" coords="0,0,110,260" href="planets_sun.gif" alt="Sun">
        <area shape="circle" coords="129,161,10" href="planets_merglobe.gif" alt="Mercury">
        <area shape="circle" coords="180,139,14" href="planets_venus.gif" alt="Venus">
    </map>
</section>

## article

> article 标签规定独立的自包含内容。

语法：

```html
<article>
    <h1>GitHub</h1>
    <p>GitHub is a development platform inspired by the way you work.</p>
</article>
```

效果：

<section>
    <article>
        <h1>GitHub</h1>
        <p>GitHub is a development platform inspired by the way you work.</p>
    </article>
</section>

## aside

> aside 标签定义其所处内容之外的内容。

语法：

```html
<h1>GitHub</h1>
<aside>
    <p>GitHub is a development platform inspired by the way you work.</p>
</aside>
```

效果：

<section>
    <h1>GitHub</h1>
    <aside>
        <p>GitHub is a development platform inspired by the way you work.</p>
    </aside>
</section>

## audio

> audio 标签定义声音，比如音乐或其他音频流。

语法：

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
</audio>
```

效果：

<section>
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
    </audio>
</section>

## b

> b 标签规定粗体文本。

语法：

```html
<p>这是一段普通的段落。</p>
<p>
    <b>这是一段加粗的段落。</b>
</p>
```

效果：

<section>
    <p>这是一段普通的段落。</p>
    <p>
        <b>这是一段加粗的段落。</b>
    </p>
</section>

## base

> base 标签为页面上的所有的相对链接规定默认 URL 或默认目标。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <base href="https://github.com/" target="_blank">
    </head>
    <body>
        <img src="fluidicon.png" alt="GitHub">
    </body>
</html>
```

## bdi

> bdi 标签允许设置一段文本，使其脱离其父元素的文本方向设置，在发布用户评论或其他无法完全控制的内容时，该标签很有用。

语法：

```html
<ul>
    <li>Username <bdi>Bill</bdi> ： 80 points</li>
    <li>Username <bdi>Steve</bdi> ： 78 points</li>
</ul>
```

效果：

<section>
    <ul>
        <li>Username <bdi>Bill</bdi> ： 80 points</li>
        <li>Username <bdi>Steve</bdi> ： 78 points</li>
    </ul>
</section>

## bdo

> bdo 标签用来覆盖默认的文本方向。

语法：

```html
<bdo dir="rtl">Here is some text.</bdo>
```

效果：

<section>
    <bdo dir="rtl">Here is some text.</bdo>
</section>

## blockquote

> blockquote 标签定义摘自另一个源的块引用。

语法：

```html
<blockquote>GitHub is a development platform inspired by the way you work.</blockquote>
```

效果：

<section>
    <blockquote>GitHub is a development platform inspired by the way you work.</blockquote>
</section>

## body

> body 标签定义文档的主体内容。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <title>HTML 手册</title>
    </head>
    <body>
        <p>文档内容...</p>
    </body>
</html>
```

## br

> br 标签插入一个简单的换行符。

语法：

```html
<p>使用 br 标签<br>在文本中换行。</p>
```

效果：

<section>
    <p>使用 br 标签<br>在文本中换行。</p>
</section>

## button

> button 标签定义一个按钮。

语法：

```html
<button type="button">提交</button>
```

效果：

<section>
    <button type="button">提交</button>
</section>

## canvas

> canvas 标签是一个画布标签，必须通过使用脚本来绘制图形。

语法：

```html
<canvas id="testCanvas"></canvas>

<script type="text/javascript">
    let testCanvas = document.getElementById('testCanvas');
    let canvasContext = testCanvas.getContext('2d');
    canvasContext.fillStyle = '#FF0000';
    canvasContext.fillRect(0,0,80,100);
</script>
```

效果：

<section>
    <canvas id="testCanvas"></canvas>

    <script type="text/javascript">
        let testCanvas = document.getElementById('testCanvas');
        let canvasContext = testCanvas.getContext('2d');
        canvasContext.fillStyle = '#FF0000';
        canvasContext.fillRect(0,0,80,100);
    </script>
</section>

## caption

> caption 标签定义表格的标题。

语法：

```html
<table>
    <caption>Monthly savings</caption>
    <tr>
        <th>Month</th>
        <th>Savings</th>
    </tr>
    <tr>
        <td>January</td>
        <td>$100</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <caption>Monthly savings</caption>
        <tr>
            <th>Month</th>
            <th>Savings</th>
        </tr>
        <tr>
            <td>January</td>
            <td>$100</td>
        </tr>
    </table>
</section>

## cite

> cite 标签表示它所包含的文本是对某个参考文献的引用。

语法：

```html
<p>
    <cite>The Scream</cite> by Edward Munch. Painted in 1893.
</p>
```

效果：

<section>
    <p>
        <cite>The Scream</cite> by Edward Munch. Painted in 1893.
    </p>
</section>

## code

> code 标签是一个短语标签，用来定义计算机代码文本。

语法：

```html
<code>一段代码</code>
```

效果：

<section>
    <code>一段代码</code>
</section>

## col

> col 标签规定了 colgroup 元素内部的每一列的列属性。

语法：

```html
<table>
    <colgroup>
        <col span="2" style="background-color:red;">
        <col style="background-color:yellow;">
    </colgroup>
    <tr>
        <th>ISBN</th>
        <th>Title</th>
        <th>Price</th>
    </tr>
    <tr>
        <td>3476896</td>
        <td>My first HTML</td>
        <td>$53</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <colgroup>
            <col span="2" style="background-color:red;">
            <col style="background-color:yellow;">
        </colgroup>
        <tr>
            <th>ISBN</th>
            <th>Title</th>
            <th>Price</th>
        </tr>
        <tr>
            <td>3476896</td>
            <td>My first HTML</td>
            <td>$53</td>
        </tr>
    </table>
</section>

## colgroup

> colgroup 标签用于对表格中的列进行组合，以便对其进行格式化。

语法：

```html
<table>
    <colgroup>
        <col span="2" style="background-color:red;">
        <col style="background-color:yellow;">
    </colgroup>
    <tr>
        <th>ISBN</th>
        <th>Title</th>
        <th>Price</th>
    </tr>
    <tr>
        <td>3476896</td>
        <td>My first HTML</td>
        <td>$53</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <colgroup>
            <col span="2" style="background-color:red;">
            <col style="background-color:yellow;">
        </colgroup>
        <tr>
            <th>ISBN</th>
            <th>Title</th>
            <th>Price</th>
        </tr>
        <tr>
            <td>3476896</td>
            <td>My first HTML</td>
            <td>$53</td>
        </tr>
    </table>
</section>

## datalist

> datalist 标签规定了 input 标签可能的选项列表。

语法：

```html
<input list="browsers">

<datalist id="browsers">
    <option value="Internet Explorer"></option>
    <option value="Firefox"></option>
    <option value="Chrome"></option>
    <option value="Opera"></option>
    <option value="Safari"></option>
</datalist>
```

效果：

<section>
    <input list="browsers">

    <datalist id="browsers">
        <option value="Internet Explorer"></option>
        <option value="Firefox"></option>
        <option value="Chrome"></option>
        <option value="Opera"></option>
        <option value="Safari"></option>
    </datalist>
</section>

## dd

> dd 标签被用来对一个描述列表中的项目进行描述。

语法：

```html
<dl>
    <dt>Coffee</dt>
    <dd>Black hot drink</dd>
    <dt>Milk</dt>
    <dd>White cold drink</dd>
</dl>
```

效果：

<section>
    <dl>
        <dt>Coffee</dt>
        <dd>Black hot drink</dd>
        <dt>Milk</dt>
        <dd>White cold drink</dd>
    </dl>
</section>

## del

> del 标签定义文档中已删除的文本。

语法：

```html
<p>My favorite color is <del>blue</del> <ins>red</ins> !</p>
```

效果：

<section>
    <p>My favorite color is <del>blue</del> <ins>red</ins> !</p>
</section>

## details

> details 标签规定了用户可见的或者隐藏的需求的补充细节。

语法：

```html
<details>
    <summary>Copyright 2020.</summary>
    <p> - by Kuriv Vesti. All Rights Reserved.</p>
</details>
```

效果：

<section>
    <details>
        <summary>Copyright 2020.</summary>
        <p> - by Kuriv Vesti. All Rights Reserved.</p>
    </details>
</section>

## dfn

> dfn 标签是一个短语标签，用来定义特殊术语或短语。

语法：

```html
<dfn>定义项目</dfn>
```

效果：

<section>
    <dfn>定义项目</dfn>
</section>

## dialog

> dialog 标签定义对话框或窗口。

语法：

```html
<table>
    <tr>
        <th>January <dialog open>This is an open dialog window!</dialog></th>
        <th>February</th>
        <th>March</th>
    </tr>
    <tr>
        <td>31</td>
        <td>28</td>
        <td>31</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <tr>
            <th>January <dialog open>This is an open dialog window!</dialog></th>
            <th>February</th>
            <th>March</th>
        </tr>
        <tr>
            <td>31</td>
            <td>28</td>
            <td>31</td>
        </tr>
    </table>
</section>

## div

> div 标签定义 HTML 文档中的一个分隔区块或者一个区域部分。

语法：

```html
<div>
    <h3>This is a header.</h3>
    <p>This is a paragraph.</p>
</div>
```

效果：

<section>
    <div>
        <h3>This is a header.</h3>
        <p>This is a paragraph.</p>
    </div>
</section>

## dl

> dl 标签定义一个描述列表。

语法：

```html
<dl>
    <dt>Coffee</dt>
    <dd>Black hot drink</dd>
    <dt>Milk</dt>
    <dd>White cold drink</dd>
</dl>
```

效果：

<section>
    <dl>
        <dt>Coffee</dt>
        <dd>Black hot drink</dd>
        <dt>Milk</dt>
        <dd>White cold drink</dd>
    </dl>
</section>

## dt

> dt 标签定义一个描述列表的项目。

语法：

```html
<dl>
    <dt>Coffee</dt>
    <dd>Black hot drink</dd>
    <dt>Milk</dt>
    <dd>White cold drink</dd>
</dl>
```

效果：

<section>
    <dl>
        <dt>Coffee</dt>
        <dd>Black hot drink</dd>
        <dt>Milk</dt>
        <dd>White cold drink</dd>
    </dl>
</section>

## em

> em 标签是一个短语标签，用来呈现为被强调的文本。

语法：

```html
<em>强调文本</em>
```

效果：

<section>
    <em>强调文本</em>
</section>

## embed

> embed 标签定义了一个容器，用来嵌入外部应用或者互动程序。

语法：

```html
<embed src="embed.swf"></embed>
```

效果：

<section>
    <embed src="embed.swf"></embed>
</section>

## fieldset

> fieldset 标签可以将表单内的相关元素分组。

语法：

```html
<form>
    <fieldset>
        <legend>个人信息:</legend>
        姓名: <input type="text" size="30"><br>
        邮箱: <input type="text" size="30">
    </fieldset>
</form>
```

效果：

<section>
    <form>
        <fieldset>
            <legend>个人信息:</legend>
            姓名: <input type="text" size="30"><br>
            邮箱: <input type="text" size="30">
        </fieldset>
    </form>
</section>

## figcaption

> figcaption 标签为 figure 标签定义标题。

语法：

```html
<figure>
    <img src="https://github.com/fluidicon.png" alt="GitHub">
    <figcaption>GitHub</figcaption>
</figure>
```

效果：

<section>
    <figure>
        <img src="https://github.com/fluidicon.png" alt="GitHub">
        <figcaption>GitHub</figcaption>
    </figure>
</section>

## figure

> figure 标签规定独立的流内容，包括图像、图表、照片、代码等等。

语法：

```html
<figure>
    <img src="https://github.com/fluidicon.png" alt="GitHub">
</figure>
```

效果：

<section>
    <figure>
        <img src="https://github.com/fluidicon.png" alt="GitHub">
    </figure>
</section>

## footer

> footer 标签定义文档或者文档的一部分区域的页脚。

语法：

```html
<footer>
    <p>Posted by： Kuriv Vesti.</p>
    <p><time datetime="2020-01-01"></time></p>
</footer>
```

效果：

<section>
    <footer>
        <p>Posted by： Kuriv Vesti.</p>
        <p><time datetime="2020-01-01"></time></p>
    </footer>
</section>

## form

> form 标签用于创建供用户输入的 HTML 表单。

语法：

```html
<form>
    First name： <input type="text" name="first_name"><br>
    Last name： <input type="text" name="last_name">
</form>
```

效果：

<section>
    <form>
        First name： <input type="text" name="first_name"><br>
        Last name： <input type="text" name="last_name">
    </form>
</section>

## h1

> h1 标签被用来定义 HTML 标题， h1 标签定义重要等级最高的标题。

语法：

```html
<h1>这是标题 1</h1>
```

效果：

<section>
    <h1>这是标题 1</h1>
</section>

## h2

> h2 标签被用来定义 HTML 标题。

语法：

```html
<h2>这是标题 2</h2>
```

效果：

<section>
    <h2>这是标题 2</h2>
</section>

## h3

> h3 标签被用来定义 HTML 标题。

语法：

```html
<h3>这是标题 3</h3>
```

效果：

<section>
    <h3>这是标题 3</h3>
</section>

## h4

> h4 标签被用来定义 HTML 标题。

语法：

```html
<h4>这是标题 4</h4>
```

效果：

<section>
    <h4>这是标题 4</h4>
</section>

## h5

> h5 标签被用来定义 HTML 标题。

语法：

```html
<h5>这是标题 5</h5>
```

效果：

<section>
    <h5>这是标题 5</h5>
</section>

## h6

> h6 标签被用来定义 HTML 标题， h6 标签定义重要等级最低的标题。

语法：

```html
<h6>这是标题 6</h6>
```

效果：

<section>
    <h6>这是标题 6</h6>
</section>

## head

> head 标签是所有头部元素的容器，主要包含关于 HTML 文档的一般信息。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <title>HTML 手册</title>
    </head>
    <body>
        <p>文档内容...</p>
    </body>
</html>
```

## header

> header 标签定义文档或者文档的一部分区域的页眉。

语法：

```html
<header>
    <h1>GitHub</h1>
    <p>GitHub is a development platform inspired by the way you work.</p>
</header>
```

效果：

<section>
    <header>
        <h1>GitHub</h1>
        <p>GitHub is a development platform inspired by the way you work.</p>
    </header>
</section>

## hgroup

> hgroup 标签被用来对标题元素进行分组。

语法：

```html
<hgroup>
    <h1>GitHub</h1>
    <h2>GitHub is a development platform inspired by the way you work.</h2>
</hgroup>
```

效果：

<section>
    <hgroup>
        <h1>GitHub</h1>
        <h2>GitHub is a development platform inspired by the way you work.</h2>
    </hgroup>
</section>

## hr

> hr 标签被用来分隔 HTML 页面中的内容，并且显示为一条水平线。

语法：

```html
<p>HTML</p>
<hr>
<p>CSS</p>
```

效果：

<section>
    <p>HTML</p>
    <hr>
    <p>CSS</p>
</section>

## html

> html 标签用于创建一个 HTML 文档。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <title>HTML 手册</title>
    </head>
    <body>
        <p>文档内容...</p>
    </body>
</html>
```

## i

> i 标签定义与文本中其余部分不同的部分，并把这部分文本呈现为斜体文本。

语法：

```html
<p>He named his car <i>The lightning</i> , because it was very fast.</p>
```

效果：

<section>
    <p>He named his car <i>The lightning</i> , because it was very fast.</p>
</section>

## iframe

> iframe 标签规定一个内联框架，用来在当前 HTML 文档中嵌入另一个文档。

语法：

```html
<iframe src="https://github.com/"></iframe>
```

## img

> img 标签定义 HTML 页面中的图像。

语法：

```html
<img src="https://github.com/fluidicon.png" alt="GitHub">
```

效果：

<section>
    <img src="https://github.com/fluidicon.png" alt="GitHub">
</section>

## input

> input 标签规定了用户可以在其中输入数据的输入字段， input 标签在 form 标签中使用，用来声明允许用户输入数据的 input 控件。

语法：

```html
<form>
    First name： <input type="text" name="first_name"><br>
    Last name： <input type="text" name="last_name">
</form>
```

效果：

<section>
    <form>
        First name： <input type="text" name="first_name"><br>
        Last name： <input type="text" name="last_name">
    </form>
</section>

## ins

> ins 标签定义已经被插入文档中的文本。

语法：

```html
<p>My favorite color is <del>blue</del> <ins>red</ins> !</p>
```

效果：

<section>
    <p>My favorite color is <del>blue</del> <ins>red</ins> !</p>
</section>

## kbd

> kbd 标签定义键盘文本。

语法：

```html
<kbd>键盘输入</kbd>
```

效果：

<section>
    <kbd>键盘输入</kbd>
</section>

## label

> label 标签为 input 标签定义标注。

语法：

```html
<form>
    <label for="male">Male</label>
    <input type="radio" name="sex" id="male" value="male"><br>
    <label for="female">Female</label>
    <input type="radio" name="sex" id="female" value="female">
</form>
```

效果：

<section>
    <form>
        <label for="male">Male</label>
        <input type="radio" name="sex" id="male" value="male"><br>
        <label for="female">Female</label>
        <input type="radio" name="sex" id="female" value="female">
    </form>
</section>

## legend

> legend 标签为 fieldset 标签定义标题。

语法：

```html
<form>
    <fieldset>
        <legend>个人信息:</legend>
        姓名: <input type="text" size="30"><br>
        邮箱: <input type="text" size="30">
    </fieldset>
</form>
```

效果：

<section>
    <form>
        <fieldset>
            <legend>个人信息:</legend>
            姓名: <input type="text" size="30"><br>
            邮箱: <input type="text" size="30">
        </fieldset>
    </form>
</section>

## li

> li 标签定义列表项目。

语法：

```html
<ul>
    <li>咖啡</li>
    <li>茶</li>
    <li>牛奶</li>
</ul>
```

效果：

<section>
    <ul>
        <li>咖啡</li>
        <li>茶</li>
        <li>牛奶</li>
    </ul>
</section>

## link

> link 标签定义文档与外部资源的关系， link 标签最常见的用途是链接样式表。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <p>文档内容...</p>
    </body>
</html>
```

## main

> main 标签规定文档的主要内容。

语法：

```html
<main>
    <article>
        <h1>Internet Explorer</h1>
        <p>Internet Explorer 是由微软开发的一款免费的 Web 浏览器，发布于 1995 年。</p>
    </article>
    <article>
        <h1>Chrome</h1>
        <p>Google Chrome 是由 Google 开发的一款免费的开源 Web 浏览器，发布于 2008 年。</p>
    </article>
    <article>
        <h1>Mozilla Firefox</h1>
        <p>Firefox 是一款来自 Mozilla 的免费的开源 Web 浏览器，发布于 2004 年。</p>
    </article>
</main>
```

效果：

<section>
    <main>
        <article>
            <h1>Internet Explorer</h1>
            <p>Internet Explorer 是由微软开发的一款免费的 Web 浏览器，发布于 1995 年。</p>
        </article>
        <article>
            <h1>Chrome</h1>
            <p>Google Chrome 是由 Google 开发的一款免费的开源 Web 浏览器，发布于 2008 年。</p>
        </article>
        <article>
            <h1>Mozilla Firefox</h1>
            <p>Firefox 是一款来自 Mozilla 的免费的开源 Web 浏览器，发布于 2004 年。</p>
        </article>
    </main>
</section>

## map

> map 标签用于客户端图像映射，图像映射指带有可点击区域的一幅图像。

语法：

```html
<img src="planets.jpg" alt="planets" usemap="#planets">

<map name="planets">
    <area shape="rect" coords="0,0,110,260" href="planets_sun.gif" alt="Sun">
    <area shape="circle" coords="129,161,10" href="planets_merglobe.gif" alt="Mercury">
    <area shape="circle" coords="180,139,14" href="planets_venus.gif" alt="Venus">
</map>
```

效果：

<section>
    <img src="planets.jpg" alt="planets" usemap="#planets">

    <map name="planets">
        <area shape="rect" coords="0,0,110,260" href="planets_sun.gif" alt="Sun">
        <area shape="circle" coords="129,161,10" href="planets_merglobe.gif" alt="Mercury">
        <area shape="circle" coords="180,139,14" href="planets_venus.gif" alt="Venus">
    </map>
</section>

## mark

> mark 标签定义带有记号的文本。

语法：

```html
<p>今天别忘了买 <mark>牛奶</mark> 。</p>
```

效果：

<section>
    <p>今天别忘了买 <mark>牛奶</mark> 。</p>
</section>

## meta

> meta 标签提供了 HTML 文档的元数据，元数据不会显示在客户端，但是会被浏览器解析， meta 标签通常用于指定网页的关键词，描述，文件的最后修改时间，作者及其他元数据等，元数据可以被浏览器，搜索引擎，或其他 Web 服务调用。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <meta charset="utf-8">
        <meta name="keywords" content="关键词">
        <meta name="description" content="描述">
        <meta name="author" content="kuriv">
    </head>
    <body>
        <p>文档内容...</p>
    </body>
</html>
```

## meter

> meter 标签定义已知范围或分数值内的标量测量。

语法：

```html
<meter min="0" max="10" value="2">2 out of 10</meter>
<meter value="0.6">60%</meter>
```

效果：

<section>
    <meter min="0" max="10" value="2">2 out of 10</meter>
    <meter value="0.6">60%</meter>
</section>

## nav

> nav 标签定义导航链接的部分。

语法：

```html
<nav>
    <a href="#">HTML</a> |
    <a href="#">CSS</a> |
    <a href="#">JavaScript</a>
</nav>
```

效果：

<section>
    <nav>
        <a href="#">HTML</a> |
        <a href="#">CSS</a> |
        <a href="#">JavaScript</a>
    </nav>
</section>

## noscript

> noscript 标签用来定义在脚本未被执行时的替代内容，此标签用于可识别 noscript 标签但无法支持其中的脚本的浏览器。

语法：

```html
<script type="text/javascript">
    document.write('Hello World!');
</script>
<noscript>Your browser does not support JavaScript!</noscript>
```

## object

> object 标签定义一个嵌入的对象，此标签可以插入 HTML 文档中的对象的数据和参数，以及可用来显示和操作数据的代码。

语法：

```html
<object data="object.mp3"></object>
```

效果：

<section>
    <object data="object.mp3"></object>
</section>

## ol

> ol 标签定义了一个有序列表，列表排序以数字来显示。

语法：

```html
<ol>
    <li>咖啡</li>
    <li>茶</li>
    <li>牛奶</li>
</ol>
```

效果：

<section>
    <ol>
        <li>咖啡</li>
        <li>茶</li>
        <li>牛奶</li>
    </ol>
</section>

## optgroup

> optgroup 标签经常用于把相关的选项组合在一起，当使用一个较长的选项列表时，对相关的选项进行组合会使处理更加容易。

语法：

```html
<select>
    <optgroup label="Swedish Cars">
        <option value="Volvo">Volvo</option>
        <option value="Saab">Saab</option>
    </optgroup>
    <optgroup label="German Cars">
        <option value="Mercedes">Mercedes</option>
        <option value="Audi">Audi</option>
    </optgroup>
</select>
```

效果：

<section>
    <select>
        <optgroup label="Swedish Cars">
            <option value="Volvo">Volvo</option>
            <option value="Saab">Saab</option>
        </optgroup>
        <optgroup label="German Cars">
            <option value="Mercedes">Mercedes</option>
            <option value="Audi">Audi</option>
        </optgroup>
    </select>
</section>

## option

> option 标签定义下拉列表中的一个选项。

语法：

```html
<select>
    <option value="Volvo">Volvo</option>
    <option value="Saab">Saab</option>
    <option value="Mercedes">Mercedes</option>
    <option value="Audi">Audi</option>
</select>
```

效果：

<section>
    <select>
        <option value="Volvo">Volvo</option>
        <option value="Saab">Saab</option>
        <option value="Mercedes">Mercedes</option>
        <option value="Audi">Audi</option>
    </select>
</section>

## output

> output 标签作为计算结果输出显示。

语法：

```html
<form oninput="x.value = parseInt(range.value) + parseInt(number.value)">
    0<input type="range" id="range" value="50">100
    +
    <input type="number" id="number" value="50">
    =
    <output name="x">100</output>
</form>
```

效果：

<section>
    <form oninput="x.value = parseInt(range.value) + parseInt(number.value)">
        0<input type="range" id="range" value="50">100
        +
        <input type="number" id="number" value="50">
        =
        <output name="x">100</output>
    </form>
</section>

## p

> p 标签定义段落，段落通常在可视媒体中表示为文本块，是块级元素。

语法：

```html
<p>这是一段普通的段落。</p>
```

效果：

<section>
    <p>这是一段普通的段落。</p>
</section>

## param

> param 标签为包含它的 object 标签定义参数。

语法：

```html
<object data="object.mp3">
    <param name="autoplay" value="true">
</object>
```

效果：

<section>
    <object data="object.mp3">
        <param name="autoplay" value="true">
    </object>
</section>

## pre

> pre 标签可定义预格式化的文本，被包围在 pre 标签中的文本通常会保留空格和换行符，而文本也会呈现为等宽字体。

语法：

```html
<pre>
    此例演示如何使用 pre 标签
    对空行和     多个空格进行控制
</pre>
```

效果：

<section>
    <pre>
        此例演示如何使用 pre 标签
        对空行和     多个空格进行控制
    </pre>
</section>

## progress

> progress 标签定义运行中的任务进度。

语法：

```html
<progress max="100" value="22"></progress>
```

效果：

<section>
    <progress max="100" value="22"></progress>
</section>

## q

> q 标签定义一个短的引用，它是一个行内元素，在浏览器中显示为使用引号包含的内容。

语法：

```html
<p>
    <h1>GitHub</h1>
    <q>GitHub is a development platform inspired by the way you work.</q>
</p>
```

效果：

<section>
    <p>
        <h1>GitHub</h1>
        <q>GitHub is a development platform inspired by the way you work.</q>
    </p>
</section>

## rp

> rp 标签需要在 ruby 标签中使用，主要用来放置括弧。

语法：

```html
<ruby>
    漢 <rp>(</rp><rt>Han</rt><rp>)</rp>
    字 <rp>(</rp><rt>Zi</rt><rp>)</rp>
</ruby>
```

效果：

<section>
    <ruby>
        漢 <rp>(</rp><rt>Han</rt><rp>)</rp>
        字 <rp>(</rp><rt>Zi</rt><rp>)</rp>
    </ruby>
</section>

## rt

> 如果在 ruby 标签中需要对某些字符作出解释或者标记其发音，那么请使用 rt 标签来提供相关的信息， rt 标签必须始终包含在 ruby 标签中。

语法：

```html
<ruby>
    漢 <rt> ㄏㄢˋ </rt>
</ruby>
```

效果：

<section>
    <ruby>
        漢 <rt> ㄏㄢˋ </rt>
    </ruby>
</section>

## ruby

> ruby 标签是当作注释使用的，可以对文本进行注音或者字符。

语法：

```html
<ruby>
    汉 <rp>(</rp><rt>Han</rt><rp>)</rp>
    字 <rp>(</rp><rt>Zi</rt><rp>)</rp>
</ruby>
```

效果：

<section>
    <ruby>
        汉 <rp>(</rp><rt>Han</rt><rp>)</rp>
        字 <rp>(</rp><rt>Zi</rt><rp>)</rp>
    </ruby>
</section>

## s

> s 标签中的文本会以贯穿一条线呈现给用户，可以用作删除线。

语法：

```html
<p>我的新车是银色的。</p>
<p>
    <s>我的新车是蓝色的。</s>
</p>
```

效果：

<section>
    <p>我的新车是银色的。</p>
    <p>
        <s>我的新车是蓝色的。</s>
    </p>
</section>

## samp

> samp 标签是一个短语标签，用来定义计算机程序的样本文本。

语法：

```html
<samp>计算机样本</samp>
```

效果：

<section>
    <samp>计算机样本</samp>
</section>

## script

> script 标签用于定义客户端脚本，比如 JavaScript ，也可以包含脚本语句。

语法：

```html
<script type="text/javascript">
    document.write('Hello World!');
</script>
```

## section

> section 标签定义了文档的某个区域。

语法：

```html
<section>
    <h1>GitHub</h1>
    <p>GitHub is a development platform inspired by the way you work.</p>
</section>
```

效果：

<section>
    <h1>GitHub</h1>
    <p>GitHub is a development platform inspired by the way you work.</p>
</section>

## select

> select 元素用来创建下拉列表， select 元素中的 option 标签定义了列表中的可用选项， select 元素可创建单选或多选菜单，当提交表单时，浏览器会提交选定的项目，或者收集用逗号分隔的多个选项，将其合成一个单独的参数列表，并且在将 select 表单数据提交给服务器时将包含 name 属性。

语法：

```html
<select>
    <option value="Volvo">Volvo</option>
    <option value="Saab">Saab</option>
    <option value="Mercedes">Mercedes</option>
    <option value="Audi">Audi</option>
</select>
```

效果：

<section>
    <select>
        <option value="Volvo">Volvo</option>
        <option value="Saab">Saab</option>
        <option value="Mercedes">Mercedes</option>
        <option value="Audi">Audi</option>
    </select>
</section>

## small

> small 标签可以使显示在浏览器中的文本变为较小号的字体。

语法：

```html
<p>Copyright 2020 by Kuriv Vesti.</p>
<p>
    <small>Copyright 2020 by Kuriv Vesti.</small>
</p>
```

效果：

<section>
    <p>Copyright 2020 by Kuriv Vesti.</p>
    <p>
        <small>Copyright 2020 by Kuriv Vesti.</small>
    </p>
</section>

## source

> source 标签为媒体元素定义媒体资源。

语法：

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
</audio>
```

效果：

<section>
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
    </audio>
</section>

## span

> span 标签用于对文档中的行内元素进行组合， span 标签没有固定的格式表现，当对它应用样式时，它才会产生视觉上的变化，如果不对 span 标签应用样式，那么 span 标签中的文本与其他文本不会任何视觉上的差异。

语法：

```html
<p>我有一双 <span style="color: blue;">蓝色</span> 的眼睛。</p>
```

效果：

<section>
    <p>我有一双 <span style="color: blue;">蓝色</span> 的眼睛。</p>
</section>

## strong

> strong 标签用来强调某些文本的重要性，这意味着这些文本会以加粗的形式呈现在浏览器中。

语法：

```html
<strong>加粗文本</strong>
```

效果：

<section>
    <strong>加粗文本</strong>
</section>

## style

> style 标签定义 HTML 文档的样式信息，在 style 标签中，可以规定在浏览器中如何呈现 HTML 文档。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <style type="text/css">
            h1 {
                color: red;
            }
            p {
                color: blue;
            }
        </style>
    </head>
    <body>
        <h1>A heading</h1>
        <p>A paragraph.</p>
    </body>
</html>
```

## sub

> sub 标签定义下标文本，下标文本将会显示在当前文本流中字符高度的一半为基准线的下方，但是与当前文本流中文字的字体和字号都是一样的。

语法：

```html
<p>This text contains <sub>subscript</sub> text.</p>
```

效果：

<section>
    <p>This text contains <sub>subscript</sub> text.</p>
</section>

## summary

> summary 标签作为 details 标签的标题，该标签可以包含详细的信息，但是默认情况下不显示，需要单击才能显示详细信息。

语法：

```html
<details>
    <summary>Copyright 2020.</summary>
    <p> - by Kuriv Vesti. All Rights Reserved.</p>
</details>
```

效果：

<section>
    <details>
        <summary>Copyright 2020.</summary>
        <p> - by Kuriv Vesti. All Rights Reserved.</p>
    </details>
</section>

## sup

> sup 标签定义上标文本，上标文本将会显示在当前文本流中字符高度的一半为基准线的上方，但是与当前文本流中文字的字体和字号都是一样的。

语法：

```html
<p>This text contains <sup>superscript</sup> text.</p>
```

效果：

<section>
    <p>This text contains <sup>superscript</sup> text.</p>
</section>

## table

> table 标签定义 HTML 表格。

语法：

```html
<table>
    <tr>
        <th>Month</th>
        <th>Savings</th>
    </tr>
    <tr>
        <td>January</td>
        <td>$100</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <tr>
            <th>Month</th>
            <th>Savings</th>
        </tr>
        <tr>
            <td>January</td>
            <td>$100</td>
        </tr>
    </table>
</section>

## tbody

> tbody 标签用于组合 HTML 表格的主体内容。

语法：

```html
<table>
    <thead>
        <tr>
            <th>Month</th>
            <th>Savings</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>January</td>
            <td>$100</td>
        </tr>
        <tr>
            <td>February</td>
            <td>$80</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Sum</td>
            <td>$180</td>
        </tr>
    </tfoot>
</table>
```

效果：

<section>
    <table>
        <thead>
            <tr>
                <th>Month</th>
                <th>Savings</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>January</td>
                <td>$100</td>
            </tr>
            <tr>
                <td>February</td>
                <td>$80</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>Sum</td>
                <td>$180</td>
            </tr>
        </tfoot>
    </table>
</section>

## td

> td 标签定义 HTML 表格中的标准单元格。

语法：

```html
<table>
    <tr>
        <td>Cell A</td>
        <td>Cell B</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <tr>
            <td>Cell A</td>
            <td>Cell B</td>
        </tr>
    </table>
</section>

## textarea

> textarea 标签定义一个多行的文本输入控件，用户可在其文本区域中写入文本。

语法：

```html
<textarea rows="10" cols="30">我是一个文本框。</textarea>
```

效果：

<section>
    <textarea rows="10" cols="30">我是一个文本框。</textarea>
</section>

## tfoot

> tfoot 标签用于组合 HTML 表格的页脚内容。

语法：

```html
<table>
    <thead>
        <tr>
            <th>Month</th>
            <th>Savings</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>January</td>
            <td>$100</td>
        </tr>
        <tr>
            <td>February</td>
            <td>$80</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Sum</td>
            <td>$180</td>
        </tr>
    </tfoot>
</table>
```

效果：

<section>
    <table>
        <thead>
            <tr>
                <th>Month</th>
                <th>Savings</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>January</td>
                <td>$100</td>
            </tr>
            <tr>
                <td>February</td>
                <td>$80</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>Sum</td>
                <td>$180</td>
            </tr>
        </tfoot>
    </table>
</section>

## th

> th 标签定义 HTML 表格中的表头单元格，该标签中的内容会以粗体显示。

语法：

```html
<table>
    <tr>
        <th>Month</th>
        <th>Savings</th>
    </tr>
    <tr>
        <td>January</td>
        <td>$100</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <tr>
            <th>Month</th>
            <th>Savings</th>
        </tr>
        <tr>
            <td>January</td>
            <td>$100</td>
        </tr>
    </table>
</section>

## thead

> thead 标签用于组合 HTML 表格的表头内容。

语法：

```html
<table>
    <thead>
        <tr>
            <th>Month</th>
            <th>Savings</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>January</td>
            <td>$100</td>
        </tr>
        <tr>
            <td>February</td>
            <td>$80</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Sum</td>
            <td>$180</td>
        </tr>
    </tfoot>
</table>
```

效果：

<section>
    <table>
        <thead>
            <tr>
                <th>Month</th>
                <th>Savings</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>January</td>
                <td>$100</td>
            </tr>
            <tr>
                <td>February</td>
                <td>$80</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>Sum</td>
                <td>$180</td>
            </tr>
        </tfoot>
    </table>
</section>

## time

> time 标签用来表示 HTML 网页中的日期和时间，让搜索引擎等程序更容易的提取这些信息。

语法：

```html
<p>We open at <time>10:00</time> every morning.</p>
<p>I have a date on <time datetime="2020-02-14">Valentines</time> day.</p>
```

效果：

<section>
    <p>We open at <time>10:00</time> every morning.</p>
    <p>I have a date on <time datetime="2020-02-14">Valentines</time> day.</p>
</section>

## title

> title 标签定义 HTML 文档的标题，通常体现了网页的主题内容，浏览器会以特殊的方式来使用标题，并且显示在浏览器窗口的标题栏或状态栏上。

语法：

```html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
    <head>
        <title>HTML 手册</title>
    </head>
    <body>
        <p>文档内容...</p>
    </body>
</html>
```

## tr

> tr 标签定义 HTML 表格中的一行单元格，它应该是成对出现的。

语法：

```html
<table>
    <tr>
        <th>Month</th>
        <th>Savings</th>
    </tr>
    <tr>
        <td>January</td>
        <td>$100</td>
    </tr>
</table>
```

效果：

<section>
    <table>
        <tr>
            <th>Month</th>
            <th>Savings</th>
        </tr>
        <tr>
            <td>January</td>
            <td>$100</td>
        </tr>
    </table>
</section>

## track

> track 标签为媒体元素规定外部文本轨道。

语法：

```html
<video width="400" controls>
    <source src="video.mp4" type="video/mp4">
    <track src="subtitles.vtt" kind="subtitles">
</video>
```

效果：

<section>
    <video width="400" controls>
        <source src="video.mp4" type="video/mp4">
        <track src="subtitles.vtt" kind="subtitles">
    </video>
</section>

## u

> u 标签可以用来对标签内的文本实现下划线样式。

语法：

```html
<p>This is a <u>parragraph</u> .</p>
```

效果：

<section>
    <p>This is a <u>parragraph</u> .</p>
</section>

## ul

> ul 标签表示 HTML 页面中项目的无序列表，一般会以项目符号列表呈现。

语法：

```html
<ul>
    <li>咖啡</li>
    <li>茶</li>
    <li>牛奶</li>
</ul>
```

效果：

<section>
    <ul>
        <li>咖啡</li>
        <li>茶</li>
        <li>牛奶</li>
    </ul>
</section>

## var

> var 标签表示数学表达式或编程上下文中的变量。

语法：

```html
<var>变量</var>
```

效果：

<section>
    <var>变量</var>
</section>

## video

> video 标签定义视频，比如电影片段或其他视频流。

语法：

```html
<video width="400" controls autoplay>
    <source src="video.mp4" type="video/mp4">
</video>
```

效果：

<section>
    <video width="400" controls autoplay>
        <source src="video.mp4" type="video/mp4">
    </video>
</section>

## wbr

> wbr 标签规定在文本中的何处适合添加换行符，如果浏览器窗口的宽度足够，则不换行，如果浏览器窗口的宽度不足，则在添加了 wbr 标签的位置进行换行。

语法：

```html
<p>To learn AJAX, you must be familiar with the XML<wbr>Http<wbr>Request Object.</p>
```

效果：

<section>
    <p>To learn AJAX, you must be familiar with the XML<wbr>Http<wbr>Request Object.</p>
</section>