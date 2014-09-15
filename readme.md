saigoku33data-by-sparql
=======================
#DBpediaの情報をWordPressで表示させるテスト

##現状

- class="temple"にDBpediaからとってきた情報を表示させるだけ。
- 表示させる寺は、カスタムフィールドで入力することで選べる。
- データはとりあえず西国３３所のみ。特に意味はない。

##今後

- カスタムフィールドをセレクト形式にする
 - （地名）が入る寺名の入力がややこしい。
 - セレクトのオプションもSPARQLでやってしまえると理想
- SPARQLコード的に駅とか桜名所にも拡張できそうなので、そっちにも対応させる。  
多分管理画面で弄る系になる。（ショートコード？）
- ショートコード化して、表示位置とか項目をより自由にしたい。