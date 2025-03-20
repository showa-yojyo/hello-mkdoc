---
date: 2025-03-19 (Wed) 15:23:45
---
# Extensions

ここは Python Markdown の拡張を試すページだ。

[TOC]

## Abbreviations

略語とその脚注を自動リンクさせる。

The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium

## Admonition

Sphinx 使いならこの拡張は入れたい。

* attention
* caution
* danger
* error
* hint
* important
* note
* tip
* warning

```text
!!! type "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.
```

!!! attention
    Notice taken of someone or something; the regarding of someone or something
    as interesting or important.

!!! caution
    Care taken to avoid danger or mistakes.

!!! danger
    A cause or likely cause of harm or injury.

!!! error
    An error is a deviation from accuracy or correctness.

!!! hint
    A hint is an indirect, disguised, or helpful suggestion.

!!! important
    Of great significance or value.

!!! note
    A notice or pay particular attention to.

!!! tip
    A useful piece of information or advice.

!!! warning
    A warning is something that makes us aware of possible danger.

## Definition Lists

Apple
:   Pomaceous fruit of plants of the genus Malus in the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.

## Fenced Code Blocks

A paragraph before the code block.

``` text
a one-line code block
```

A paragraph after the code block.

``` { .text title="An Example Code Block" }
A truncated code block...
```

## Footnotes

Footnotes[^1] have a label[^@#$%] and the footnote's content.

[^1]: This is a footnote content.
[^@#$%]: A footnote on the label: "@#$%".

## Meta Data

TBW

## New-Line-to-Break

日本語を
書く。

## Table of Contents

このページの上の方に `[TOC]` と挿れておいたから、そこが目次に置き換わる。

## Tables

拡張方式：

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

標準 Markdown 方式：

| First Header  | Second Header |
|---------------|---------------|
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
