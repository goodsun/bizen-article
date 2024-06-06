# markdown format

![bizen](https://fs.bon-soleil.com/img/BizenNFT.jpg)

# What is Markdown

> Markdown is a lightweight markup language for writing documents. It was originally developed to generate HTML from documents written easily in plain text format. However, software (converters) have now been developed to convert files into PowerPoint and LATEX formats in addition to HTML. Various dialects exist because various extensions are made by the developers of each converter.
> From [Markdown - Wikipedia](https://ja.wikipedia.org/wiki/Markdown)

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#-block-elements)🎁 Block elements

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E8%A6%8B%E5%87%BA%E3%81%97---headers)💎 Headings - Headers

example.md

```
# This is an H1
## This is an H2
###### This is an H6
```

**🎉 Result**

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#this-is-an-h1)This is an H1

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#this-is-an-h2)This is an H2

###### [](https://qiita.com/oreo/items/82183bfbaac69971917f#this-is-an-h6)This is an H6

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E5%BC%95%E7%94%A8---blockquotes)💎 Quotes - Blockquotes

example.md

```
> QuoteQuoteQuoteQuote
QuoteQuoteQuote
> Quote bodyQuote body>> Nesting
```

**🎉 Result**

> `>` can be used to quote
>
> > Double quotes do not break lines in the middle

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E3%83%AA%E3%82%B9%E3%83%88---lists)💎 Lists - Lists

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#disc%E5%9E%8B)Disc type

example.md

```
* List 1
* List 1-2
* List 2
```

**🎉 Result**

- List 1
- List 1-2
- List 2

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#decimal%E5%9E%8B)Decimal type

example.md

```
1. List 1
1. List 1-1
2. List 1-2
2. List 2
```

**🎉 Result**

1. List 1
1. List 1-1
1. List 1-2
1. List 2

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#definition%E5%9E%8B)Definition type

example.md

```
<dl>
<dt>Oreo</dt>
<dd>Cookies & Cream</dd>
<dt>Ritz</dt>
<dd>Plain Crackers</dd>
</dl>
```

**🎉 Results**

Oreo

Cookies & Cream

Ritz

Plain Crackers

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#checkbox%E5%9E%8B)Checkbox type

example.md

```
- [ ] List 1
- [x] List 2
```

**🎉 Results**

- [ ] List 1
- [x] List 2

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E6%B0%B4%E5%B9%B3%E7%B7%9A---horizontal-rules)💎 Horizontal Rules

You can output horizontal lines by writing three or more hyphens or asterisks.

example.md

```
**** * *
--- - - -
```

**🎉 Results**

---

---

---

---

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#-span-elements)🎁 Span Elements

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E3%83%AA%E3%83%B3%E3%82%AF---links)💎 Links - Links

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#%E8%87%AA%E5%8B%95%E3%83%AA%E3%83%B3%E3%82%AF)Automatic link

example.md

```
<http://qiita.com>
http://qiita.com
```

**🎉 Results**
[http://qiita.com](http://qiita.com/)
[http://qiita.com](http://qiita.com/)

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#%E3%82%A4%E3%83%B3%E3%83%A9%E3%82%A4%E3%83%B3%E3%83%AA%E3%83%B3%E3%82%AF)Inline link

example.md

```
[Qiita](http://qiita.com)
[Qiita](http://qiita.com "Qiita")
```

**🎉 Results**
[Qiita](http://qiita.com/)
[Qiita](http://qiita.com/ "Qiita") (With title)

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E5%BC%B7%E8%AA%BF---emphasis)💎 Emphasis - Emphasis

example.md

```
*Emphasis*
**Emphasis**
***Emphasis***
```

**🎉 Result**

| Asterisk | Font          | Display      |
| -------- | ------------- | ------------ |
| 1        | Italic        | _Sample_     |
| 2        | Bold          | **Sample**   |
| 3        | Italic & Bold | **Sample\_** |

The same function can be used not only with asterisks (\*) but also with underscores (\_)

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E7%94%BB%E5%83%8F---images)💎 Images - images

example.md

```
![Dummy image](https://via.placeholder.com/150)
![Dummy image](https://via.placeholder.com/150 "Dummy image")
```

**🎉 Result**
[![Dummy image](https://qiita-user-contents.imgix.net/https%3A%2F%2Fvia.placeholder.com%2F150?ixlib=rb-4.0.0&auto=format&gif-q=60&q=75&s=9b5f54dfa7880f6b972328a688c54796)](https://camo.qiitausercontent.com/ab532ec789448df648be4de04e42909 e27499a3b/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f313530)
[![Dummy image](https://qiita-user-contents.imgix.net/https%3A%2F%2Fvia.placeholder.com%2F100?ixlib=rb-4.0.0&auto=format&gif-q=60&q=75&s=31365bc75a8a88557b2e2593ddf0fa16 "Dummy image")](https://camo.qiitausercontent.com/2752e7015ef8ac87e5c771b698475cf4fba2c3b6/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f313030) (With title)

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E6%89%93%E3%81%A1%E6%B6%88%E3%81%97)💎 Cancellation

example.md

```
~~ Cancellation ~~
```

**🎉 Result**
~~ Cancellation ~~

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E6%B3%A8%E9%87%88)💎 Annotation

example.md

```

Main text Main text Main text \[^Annotation]

\[^Annotation]:Annotation text Annotation text Annotation text
```

**🎉 Result**
Reality and ideals are side by side if you look closely, and you can always reach either one depending on yourself. [1](https://qiita.com/oreo/items/82183bfbaac69971917f#fn-1)

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#-code)🎁 Code

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E3%82%B3%E3%83%BC%E3%83%89%E8%A1%A8%E7%A4%BA)💎 Show code

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#%E3%82%A4%E3%83%B3%E3%83%A9%E3%82%A4%E3%83%B3
