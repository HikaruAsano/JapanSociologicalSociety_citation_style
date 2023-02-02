<!--
Filename:       README.md
Author:         Hikaru Asano
e-mail          <asano-hikaru19@g.ecc.u-tokyo.ac.jp>
First-written:  <2023/02/02>

-->

jss.bst
==============================

"jss.bst"は日本社会学会用のBibTeX スタイルファイルです。以下のような特徴があります。

* 「著者（年）」形式（author-year format) で引用できます。
*  経済学でよく利用されるような参考文献（reference）の形式を実現できます（ただし、
  特定の雑誌向けというわけではないです）。
* 英語の文献だけでなく、日本語の文献も適切に処理できます。
* 他の BibTeX 用のスタイルファイルよりも表示形式のカスタマイズが簡単にできます。


## 注

* `jecon-example.tex` をコンパイルするときには LaTeX エンジンとして `lualatex`、BibTeX エンジンとしては `upbibtex` を使うようにしてください。（TeX Live 2020までの）古い upbibtex、あるいは pbibtex を使いたい場合は、[`jecon-example.pdf`](jecon-example.pdf) の「BibTeXエンジンの選択」という節を見てください。


* `bst.sei.mei.order`のデフォールト値を `#1` に変更しました。これは bibファイルにおいて日本語であっても「{姓,名}」という書き方で指定するということを意味します。これは最近の文献データベースや文献管理ソフトで、日本語であっても外国人と同様の扱いをしているものが多いためです。昔からの伝統的な書き方で指定したければ、`bst.sei.mei.order`に `#0`を指定してください。



<!--
--------------------
Local Variables:
mode: markdown
fill-column: 80
coding: utf-8-dos
End:
-->
