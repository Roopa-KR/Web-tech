# HTML Tags: Definition + Example

This is a practical reference of HTML tags with a short definition and a basic example for each.

## Document and metadata tags

| Tag | Definition | Example |
|---|---|---|
| `<html>` | Root element of an HTML document. | `<html lang="en">...</html>` |
| `<head>` | Container for metadata, links, scripts, and title. | `<head><meta charset="UTF-8"></head>` |
| `<title>` | Sets the page title shown in the browser tab. | `<title>My Page</title>` |
| `<base>` | Sets base URL/target for relative links. | `<base href="https://example.com/">` |
| `<link>` | Links external resources (CSS, icons). | `<link rel="stylesheet" href="styles.css">` |
| `<meta>` | Provides metadata (charset, viewport, SEO). | `<meta name="viewport" content="width=device-width, initial-scale=1.0">` |
| `<style>` | Embeds CSS in the document. | `<style>body{font-family:sans-serif;}</style>` |
| `<body>` | Holds all visible page content. | `<body><h1>Hello</h1></body>` |

## Sectioning and layout tags

| Tag | Definition | Example |
|---|---|---|
| `<header>` | Intro/header area for page or section. | `<header><h1>Site Name</h1></header>` |
| `<nav>` | Section containing navigation links. | `<nav><a href="/">Home</a></nav>` |
| `<main>` | Main unique content of the page. | `<main><article>...</article></main>` |
| `<section>` | Thematic grouping of related content. | `<section><h2>Features</h2></section>` |
| `<article>` | Self-contained independent content unit. | `<article><h2>News</h2><p>...</p></article>` |
| `<aside>` | Side content, related but not central. | `<aside>Related links</aside>` |
| `<footer>` | Footer for page or section. | `<footer>&copy; 2026</footer>` |
| `<h1>` | Top-level heading. | `<h1>Main Heading</h1>` |
| `<h2>` | Second-level heading. | `<h2>Sub Heading</h2>` |
| `<h3>` | Third-level heading. | `<h3>Topic</h3>` |
| `<h4>` | Fourth-level heading. | `<h4>Detail</h4>` |
| `<h5>` | Fifth-level heading. | `<h5>Minor Detail</h5>` |
| `<h6>` | Sixth-level heading. | `<h6>Small Heading</h6>` |
| `<hgroup>` | Groups multiple headings as one heading block. | `<hgroup><h1>Title</h1><p>Subtitle</p></hgroup>` |
| `<address>` | Contact information for author/owner. | `<address>Email: a@example.com</address>` |
| `<div>` | Generic block-level container. | `<div class="card">Card content</div>` |

## Text content tags

| Tag | Definition | Example |
|---|---|---|
| `<p>` | Paragraph of text. | `<p>This is a paragraph.</p>` |
| `<hr>` | Thematic break (horizontal rule). | `<hr>` |
| `<pre>` | Preformatted text (preserves spaces/newlines). | `<pre>line 1\n  line 2</pre>` |
| `<blockquote>` | Block quotation from another source. | `<blockquote cite="https://example.com">Quote</blockquote>` |
| `<ol>` | Ordered (numbered) list. | `<ol><li>Step 1</li></ol>` |
| `<ul>` | Unordered (bulleted) list. | `<ul><li>Item</li></ul>` |
| `<li>` | List item in `ol`, `ul`, or `menu`. | `<li>Milk</li>` |
| `<dl>` | Description list container. | `<dl><dt>HTML</dt><dd>Markup language</dd></dl>` |
| `<dt>` | Term/name in a description list. | `<dt>CPU</dt>` |
| `<dd>` | Description/value in a description list. | `<dd>Central Processing Unit</dd>` |
| `<figure>` | Self-contained media/content unit. | `<figure><img src="cat.jpg" alt="cat"></figure>` |
| `<figcaption>` | Caption for a `figure`. | `<figcaption>Figure 1: Cat</figcaption>` |

## Inline text semantics tags

| Tag | Definition | Example |
|---|---|---|
| `<a>` | Hyperlink to another URL/fragment. | `<a href="https://example.com">Visit</a>` |
| `<em>` | Emphasized text (stress emphasis). | `<em>Important</em>` |
| `<strong>` | Strong importance. | `<strong>Warning</strong>` |
| `<small>` | Side comments/small print. | `<small>Terms apply.</small>` |
| `<s>` | No longer accurate/relevant text. | `<s>$20</s> $15` |
| `<cite>` | Title/reference of a creative work. | `<cite>The Odyssey</cite>` |
| `<q>` | Inline short quotation. | `<q>Practice daily.</q>` |
| `<dfn>` | Defining instance of a term. | `<dfn>API</dfn>` |
| `<abbr>` | Abbreviation or acronym. | `<abbr title="HyperText Markup Language">HTML</abbr>` |
| `<ruby>` | Ruby annotation container (East Asian text). | `<ruby>漢<rt>kan</rt></ruby>` |
| `<rt>` | Ruby text annotation. | `<rt>kan</rt>` |
| `<rp>` | Fallback parentheses for ruby annotation. | `<rp>(</rp><rt>kan</rt><rp>)</rp>` |
| `<data>` | Content with machine-readable value. | `<data value="978">Book ID</data>` |
| `<time>` | Time/date value. | `<time datetime="2026-04-13">April 13, 2026</time>` |
| `<code>` | Short code fragment. | `<code>npm run dev</code>` |
| `<var>` | Variable name in math/programming context. | `<var>x</var> = 10` |
| `<samp>` | Sample program output. | `<samp>Build succeeded</samp>` |
| `<kbd>` | User input (keyboard/command). | `<kbd>Ctrl</kbd>+<kbd>C</kbd>` |
| `<sub>` | Subscript text. | `H<sub>2</sub>O` |
| `<sup>` | Superscript text. | `x<sup>2</sup>` |
| `<i>` | Alternate voice/mood/technical term. | `<i>Homo sapiens</i>` |
| `<b>` | Attention-drawing text without importance. | `<b>New</b>` |
| `<u>` | Non-textual annotation styling. | `<u>speling</u>` |
| `<mark>` | Highlighted/marked text. | `<mark>Matched text</mark>` |
| `<bdi>` | Isolates text direction from surrounding text. | `<bdi>مرحبا</bdi>` |
| `<bdo>` | Overrides text direction. | `<bdo dir="rtl">abc</bdo>` |
| `<span>` | Generic inline container. | `<span class="badge">New</span>` |
| `<br>` | Line break. | `Line 1<br>Line 2` |
| `<wbr>` | Optional line break opportunity. | `verylong<wbr>word` |

## Edit tracking tags

| Tag | Definition | Example |
|---|---|---|
| `<ins>` | Inserted text. | `<ins>New sentence</ins>` |
| `<del>` | Deleted text. | `<del>Old sentence</del>` |

## Media and embedded content tags

| Tag | Definition | Example |
|---|---|---|
| `<picture>` | Responsive image container with sources. | `<picture><source srcset="img.webp" type="image/webp"><img src="img.jpg" alt="sample"></picture>` |
| `<source>` | Media source for `picture`, `audio`, or `video`. | `<source src="movie.mp4" type="video/mp4">` |
| `<img>` | Embeds an image. | `<img src="photo.jpg" alt="A photo">` |
| `<iframe>` | Embeds another HTML page. | `<iframe src="https://example.com" title="Example"></iframe>` |
| `<embed>` | Embeds external content/application. | `<embed src="file.pdf" type="application/pdf">` |
| `<object>` | General external resource container. | `<object data="movie.swf"></object>` |
| `<param>` | Parameters for an `object`. | `<param name="autoplay" value="true">` |
| `<video>` | Embeds video player/content. | `<video controls><source src="movie.mp4" type="video/mp4"></video>` |
| `<audio>` | Embeds audio player/content. | `<audio controls src="song.mp3"></audio>` |
| `<track>` | Timed text tracks for media (captions). | `<track kind="subtitles" src="sub.vtt" srclang="en">` |
| `<map>` | Image map definition. | `<map name="m1">...</map>` |
| `<area>` | Clickable area in an image map. | `<area shape="rect" coords="0,0,100,100" href="/a">` |
| `<svg>` | Inline SVG graphics container. | `<svg width="100" height="100"></svg>` |
| `<math>` | Mathematical formulas (MathML). | `<math><mi>x</mi><mo>+</mo><mn>1</mn></math>` |
| `<canvas>` | Scriptable drawing surface. | `<canvas id="chart" width="300" height="150"></canvas>` |

## Table tags

| Tag | Definition | Example |
|---|---|---|
| `<table>` | Table container. | `<table><tr><td>A</td></tr></table>` |
| `<caption>` | Table title/caption. | `<caption>Sales Report</caption>` |
| `<colgroup>` | Groups columns for shared styling. | `<colgroup><col span="2"></colgroup>` |
| `<col>` | Defines a single column's properties. | `<col style="background:#eee">` |
| `<thead>` | Header row group. | `<thead><tr><th>Name</th></tr></thead>` |
| `<tbody>` | Body row group. | `<tbody><tr><td>Ana</td></tr></tbody>` |
| `<tfoot>` | Footer row group. | `<tfoot><tr><td>Total</td></tr></tfoot>` |
| `<tr>` | Table row. | `<tr><td>Cell</td></tr>` |
| `<th>` | Header cell. | `<th scope="col">Price</th>` |
| `<td>` | Data cell. | `<td>120</td>` |

## Form tags

| Tag | Definition | Example |
|---|---|---|
| `<form>` | Form container for user input controls. | `<form action="/submit" method="post"></form>` |
| `<label>` | Label for a form control. | `<label for="email">Email</label>` |
| `<input>` | Single-line input control. | `<input id="email" type="email" required>` |
| `<button>` | Clickable button control. | `<button type="submit">Send</button>` |
| `<select>` | Drop-down list control. | `<select><option>One</option></select>` |
| `<datalist>` | Suggested options for an input. | `<datalist id="browsers"><option value="Chrome"></datalist>` |
| `<optgroup>` | Group of options in a select list. | `<optgroup label="Cars"><option>BMW</option></optgroup>` |
| `<option>` | Selectable option in `select`/`datalist`. | `<option value="1">One</option>` |
| `<textarea>` | Multi-line text input. | `<textarea rows="4" cols="30"></textarea>` |
| `<output>` | Result of a calculation/form action. | `<output name="total">42</output>` |
| `<progress>` | Progress bar for task completion. | `<progress value="70" max="100">70%</progress>` |
| `<meter>` | Scalar measurement within known range. | `<meter value="0.7">70%</meter>` |
| `<fieldset>` | Groups related form controls. | `<fieldset><legend>Profile</legend>...</fieldset>` |
| `<legend>` | Caption/title for a fieldset. | `<legend>Contact Info</legend>` |

## Interactive and scripting tags

| Tag | Definition | Example |
|---|---|---|
| `<details>` | Expand/collapse disclosure widget. | `<details><summary>Read more</summary>Hidden text</details>` |
| `<summary>` | Summary/label for a `details` element. | `<summary>FAQ</summary>` |
| `<dialog>` | Dialog box/modal container. | `<dialog open>Hello</dialog>` |
| `<menu>` | Group/list of commands (limited use). | `<menu><li><button>Save</button></li></menu>` |
| `<script>` | Embeds or references JavaScript. | `<script src="app.js"></script>` |
| `<noscript>` | Fallback content if scripts are disabled. | `<noscript>Please enable JavaScript.</noscript>` |
| `<template>` | Inert HTML template for cloning with JS. | `<template id="rowTpl"><tr><td>Row</td></tr></template>` |
| `<slot>` | Placeholder in Web Components shadow DOM. | `<slot name="title"></slot>` |

## Obsolete/deprecated tags (avoid in modern HTML)

| Tag | Definition | Example |
|---|---|---|
| `<acronym>` | Old acronym tag (use `abbr`). | `<acronym title="World Health Organization">WHO</acronym>` |
| `<applet>` | Old Java applet embed tag. | `<applet code="App.class"></applet>` |
| `<basefont>` | Old base font settings tag. | `<basefont size="3">` |
| `<bgsound>` | Old IE background sound tag. | `<bgsound src="sound.mid">` |
| `<big>` | Old larger text tag (use CSS). | `<big>Big text</big>` |
| `<blink>` | Blinking text (non-standard). | `<blink>Alert</blink>` |
| `<center>` | Center alignment tag (use CSS). | `<center>Centered</center>` |
| `<content>` | Old shadow DOM insertion point. | `<content select=".item"></content>` |
| `<dir>` | Old directory list tag (use `ul`). | `<dir><li>Item</li></dir>` |
| `<font>` | Old font styling tag (use CSS). | `<font color="red">Text</font>` |
| `<frame>` | Frame in frameset layout. | `<frame src="menu.html">` |
| `<frameset>` | Container for frames (obsolete). | `<frameset cols="25%,75%"></frameset>` |
| `<image>` | Non-standard alias of image tag. | `<image src="photo.jpg">` |
| `<keygen>` | Old key pair generator control. | `<keygen name="security">` |
| `<marquee>` | Scrolling text tag (non-standard). | `<marquee>Breaking News</marquee>` |
| `<menuitem>` | Old menu command item. | `<menuitem label="Refresh"></menuitem>` |
| `<nobr>` | Prevent line breaks (use CSS). | `<nobr>No line break</nobr>` |
| `<noembed>` | Fallback for unsupported embed. | `<noembed>Plugin required</noembed>` |
| `<noframes>` | Fallback when frames unsupported. | `<noframes>Your browser does not support frames.</noframes>` |
| `<plaintext>` | Renders everything as plain text. | `<plaintext>This is plain text` |
| `<rb>` | Ruby base text element (limited support). | `<ruby><rb>漢</rb><rt>kan</rt></ruby>` |
| `<rtc>` | Ruby text container (limited support). | `<rtc><rt>kan</rt></rtc>` |
| `<shadow>` | Old shadow DOM content insertion. | `<shadow></shadow>` |
| `<spacer>` | Old layout spacer tag. | `<spacer width="20" height="20">` |
| `<strike>` | Strikethrough text (use `s`/CSS). | `<strike>Old</strike>` |
| `<tt>` | Teletype/monospace text tag. | `<tt>Monospace</tt>` |
| `<xmp>` | Raw text markup example tag. | `<xmp><p>Not parsed</p></xmp>` |

---

If you want, I can also convert this into:

1. A smaller "most-used tags" cheat sheet.
2. A printable one-page revision sheet.
3. A version grouped by beginner/intermediate/advanced level.