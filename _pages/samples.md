---
layout: single
title: "Sample Page"
permalink: /sample
author_profile: true
header:
  overlay_image: /assets/images/headerc-unsplash-cc0.jpg
  overlay_filter: rgba(0, 0, 128, 0.5)
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "Useless button"
  cta_url: ""
---

## About Samples

This is a page for testing minimal-mistakes features.  See also /test directory in original theme.  Includes:

```markdown
header:
  overlay_image: /assets/images/headerc-unsplash-cc0.jpg
  overlay_filter: rgba(0, 0, 128, 0.5)
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "Useless button"
  cta_url: ""
```

Header colors:
<div style="width:200 px; height:200 px; background-color:#662E8D;">#662E8D rgb(102, 46, 141) purple</div>
<div style="width:200 px; height:200 px; background-color:#E97826;">#E97826  rgb(233, 120, 38) orange </div>
<div style="width:200 px; height:200 px; background-color:#BE202E;">#BE202E  rgb(190, 32, 46) red1  rgba(190, 32, 46, 1.0)</div>
<div style="width:200 px; height:200 px; background-color:#C92037;">#C92037  red2</div>
<div style="width:200 px; height:200 px; background-color:#CD2032;">#CD2032  red3 </div>

Multi line blockquote with a cite reference:

> People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying no to 1,000 things.

<cite>Steve Jobs</cite> --- Apple Worldwide Developers' Conference, 1997
{: .small}

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

## Buttons

Make any link standout more when applying the `.btn` class.

```html
<a href="#" class="btn--success">Success Button</a>
```

[Primary Button](#){: .btn}
[Success Button](#){: .btn .btn--success}
[Warning Button](#){: .btn .btn--warning}
[Danger Button](#){: .btn .btn--danger}
[Info Button](#){: .btn .btn--info}
[Inverse Button](#){: .btn .btn--inverse}
[Light Outline Button](#){: .btn .btn--light-outline}

```markdown
[Primary Button Text](#link){: .btn}
[Success Button Text](#link){: .btn .btn--success}
[Warning Button Text](#link){: .btn .btn--warning}
[Danger Button Text](#link){: .btn .btn--danger}
[Info Button Text](#link){: .btn .btn--info}
[Inverse Button](#link){: .btn .btn--inverse}
[Light Outline Button](#link){: .btn .btn--light-outline}
```

[X-Large Button](#){: .btn .btn--x-large}
[Large Button](#){: .btn .btn--large}
[Default Button](#){: .btn}
[Small Button](#){: .btn .btn--small}

```markdown
[X-Large Button](#link){: .btn .btn--x-large}
[Large Button](#link){: .btn .btn--large}
[Default Button](#link){: .btn}
[Small Button](#link){: .btn .btn--small}
```

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://apple.com "Apple").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
	margin: 0 0 5px;
	font-weight: bold;
	font-size: 38px;
	line-height: 1.2;
	and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Sub/Super/Script Variables

Getting our science styling on with H<sub>2</sub>O, and E = MC<sup>2</sup> with <var>variables</var>.

## images

```html
<figure class="third"> <!-- Also: class="half" for two img -->
	<img src="/images/image-filename-1.jpg">
	<img src="/images/image-filename-2.jpg">
	<img src="/images/image-filename-3.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
```


### Make changes

This site is in a <a href="https://github.com/{{ site.repository }}">GitHub repository</a>, and the original theme's testing files are [viewable](https://mmistakes.github.io/minimal-mistakes/layout/uncategorized/layout-header-overlay-image/) and [codeable](https://github.com/mmistakes/minimal-mistakes/tree/master/test/_posts).

To discuss the Apache Way or learn more about how best to work with any Apache project, please see the [Apache Community Development project](//community.apache.org/), and participate in the [dev@community mailing list](https://lists.apache.org/list.html?dev@community.apache.org).
