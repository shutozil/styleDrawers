# メモ

## 2-8
- 「:nthchild(n)」は、指定された要素が含まれる子要素のうち、別の種類の要素も含めて先頭からn番目の子要素が対象

- 「:nthoftype(n)」は、指定された要素が含まれる子要素のうち、同じ種類の子要素の中で、先頭からn番目の子要素が対象

`「child」と「oftype」には、対象の要素をカウントする際に、別の種類の要素を含むか含まないかの違い`

## 2-9
### 擬似要素
- 疑似クラスと同様に、要素の状態やタイミングに対してスタイルを適用

#### `::after`
- 指定された要素の末尾にコンテンツを追加

#### `::before`
- 指定された要素の先頭にコンテンツを追加

- [この記事](https://saruwakakun.com/html-css/basic/before-after#one1)がとてもわかりやすかった。

## 2-14
- list-style-position
  - [参考](https://developer.mozilla.org/ja/docs/Web/CSS/list-style-type)
>list-style-type: disc;
>list-style-type: circle;
>list-style-type: square;
>list-style-type: decimal;
>list-style-type: georgian;
>list-style-type: trad-chinese-informal;
>list-style-type: kannada;

- list-style-type
  - 点の形
- list-style-image
  - 点を任意の画像に変更できる