# markdown 書式

![bizen](https://fs.bon-soleil.com/img/BizenNFT.jpg)

# Markdown とは

> Markdown（マークダウン）は、文書を記述するための軽量マークアップ言語のひとつである。本来はプレーンテキスト形式で手軽に書いた文書から HTML を生成するために開発されたものである。しかし、現在では HTML のほかパワーポイント形式や LATEX 形式のファイルへ変換するソフトウェア（コンバータ）も開発されている。各コンバータの開発者によって多様な拡張が施されるため、各種の方言が存在する。
> [Markdown - Wikipedia](https://ja.wikipedia.org/wiki/Markdown)  より

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#-block-elements)🎁 Block elements

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E8%A6%8B%E5%87%BA%E3%81%97---headers)💎 見出し - Headers

example.md

```
# This is an H1
## This is an H2
###### This is an H6
```

**🎉 結果**

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#this-is-an-h1)This is an H1

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#this-is-an-h2)This is an H2

###### [](https://qiita.com/oreo/items/82183bfbaac69971917f#this-is-an-h6)This is an H6

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E5%BC%95%E7%94%A8---blockquotes)💎 引用 - Blockquotes

example.md

```
> 引用引用引用引用
引用引用
> 引用本文引用本文
>> 入れ子
```

**🎉 結果**

> `>`によって引用をすることができます
>
> > ダブルクォーテーション内は途中で改行されません

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E3%83%AA%E3%82%B9%E3%83%88---lists)💎 リスト - Lists

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#disc%E5%9E%8B)Disc 型

example.md

```
* リスト1
  * リスト1-2
* リスト2
```

**🎉 結果**

- リスト 1
  - リスト 1-2
- リスト 2

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#decimal%E5%9E%8B)Decimal 型

example.md

```
1. リスト1
    1. リスト1-1
    2. リスト1-2
2. リスト2
```

**🎉 結果**

1. リスト 1
   1. リスト 1-1
   2. リスト 1-2
2. リスト 2

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#definition%E5%9E%8B)Definition 型

example.md

```
<dl>
  <dt>オレオ</dt>
  <dd>クッキー&クリーム</dd>
  <dt>リッツ</dt>
  <dd>プレーンクラッカー</dd>
</dl>
```

**🎉 結果**

オレオ

クッキー&クリーム

リッツ

プレーンクラッカー

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#checkbox%E5%9E%8B)Checkbox 型

example.md

```
- [ ] リスト1
- [x] リスト2
```

**🎉 結果**

- [ ] リスト 1
- [x] リスト 2

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E6%B0%B4%E5%B9%B3%E7%B7%9A---horizontal-rules)💎 水平線 - Horizontal Rules

3 つ以上のハイフン、アスタリスクを記述することで水平線を出力できます。

example.md

```
**** * *
--- - - -
```

**🎉 結果**

---

---

---

---

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#-span-elements)🎁 Span Elements

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E3%83%AA%E3%83%B3%E3%82%AF---links)💎 リンク - Links

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#%E8%87%AA%E5%8B%95%E3%83%AA%E3%83%B3%E3%82%AF)自動リンク

example.md

```
<http://qiita.com>
http://qiita.com
```

**🎉 結果**
[http://qiita.com](http://qiita.com/)
[http://qiita.com](http://qiita.com/)

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#%E3%82%A4%E3%83%B3%E3%83%A9%E3%82%A4%E3%83%B3%E3%83%AA%E3%83%B3%E3%82%AF)インラインリンク

example.md

```
[Qiita](http://qiita.com)
[Qiita](http://qiita.com "Qiita")
```

**🎉 結果**
[Qiita](http://qiita.com/)
[Qiita](http://qiita.com/ "Qiita") (タイトル付き)

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E5%BC%B7%E8%AA%BF---emphasis)💎 強調 - Emphasis

example.md

```
*強調*
**強調**
***強調***
```

**🎉 結果**

| アスタリスク | 書体               | 表示           |
| ------------ | ------------------ | -------------- |
| 1 つ         | イタリック体       | _サンプル_     |
| 2 つ         | Bold 体            | **サンプル**   |
| 3 つ         | イタリック&Bold 体 | **_サンプル_** |

アスタリスク(\*)だけでなくアンダースコア(\_)でも同様の機能が使えます

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E7%94%BB%E5%83%8F---images)💎 画像 - images

example.md

```
![ダミー画像](https://via.placeholder.com/150)
![ダミー画像](https://via.placeholder.com/150 "ダミー画像")
```

**🎉 結果**
[![ダミー画像](https://qiita-user-contents.imgix.net/https%3A%2F%2Fvia.placeholder.com%2F150?ixlib=rb-4.0.0&auto=format&gif-q=60&q=75&s=9b5f54dfa7880f6b972328a688c54796)](https://camo.qiitausercontent.com/ab532ec789448df648be4de04e42909e27499a3b/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f313530)
[![ダミー画像](https://qiita-user-contents.imgix.net/https%3A%2F%2Fvia.placeholder.com%2F100?ixlib=rb-4.0.0&auto=format&gif-q=60&q=75&s=31365bc75a8a88557b2e2593ddf0fa16 "ダミー画像")](https://camo.qiitausercontent.com/2752e7015ef8ac87e5c771b698475cf4fba2c3b6/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f313030) (タイトル付き)

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E6%89%93%E3%81%A1%E6%B6%88%E3%81%97)💎 打ち消し

example.md

```
~~打ち消し~~
```

**🎉 結果**
~~打ち消し~~

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E6%B3%A8%E9%87%88)💎 注釈

example.md

```
　　　　本文本文本文\[^注釈]
　　　　\[^注釈]:注釈テキスト注釈テキスト注釈テキスト
```

**🎉 結果**
現実と理想は良く見れば隣り合わせ、いつだって自分次第でどっちにも手が届く。[1](https://qiita.com/oreo/items/82183bfbaac69971917f#fn-1)

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#-code)🎁 Code

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E3%82%B3%E3%83%BC%E3%83%89%E8%A1%A8%E7%A4%BA)💎 コード表示

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#%E3%82%A4%E3%83%B3%E3%83%A9%E3%82%A4%E3%83%B3)インライン

example.md

```
`$hoge = 1`
`.md`
```

**🎉 結果**
`$hoge = 1`
`.md`

### [](https://qiita.com/oreo/items/82183bfbaac69971917f#%E3%82%B7%E3%83%B3%E3%82%BF%E3%83%83%E3%82%AF%E3%82%B9%E3%83%8F%E3%82%A4%E3%83%A9%E3%82%A4%E3%83%88)シンタックスハイライト

example.md

````
```html:sample
   <div class="radioWave">      <p>迷いの中あてなく見上げた空彩る星たちが</p>      <p>嘘みたいに晴れた朝に繋がることを教えてくれた</p>   </div>
```/
````

**🎉 結果**

example

```
<div class="radioWave">
  <p>迷いの中あてなく見上げた空彩る星たちが</p>
  <p>嘘みたいに晴れた朝に繋がることを教えてくれた</p>
</div>
```

# [](https://qiita.com/oreo/items/82183bfbaac69971917f#-extra)🎁 Extra

## [](https://qiita.com/oreo/items/82183bfbaac69971917f#-%E3%83%86%E3%83%BC%E3%83%96%E3%83%AB%E8%A8%98%E6%B3%95)💎 テーブル記法

example.md

```
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |
```

**🎉 結果**

| 左寄せ         | 右寄せ           | 中央         |
| -------------- | ---------------- | ------------ |
| コロンの位置で | テキストの位置を | 指定できます |
| `コード記法や` | **強調表示も**   | 使用可能です |
| 要素の前後には | 必ずスペースを   | 入れましょう |

#🔗 参考にしたサイト等
