# justify-contentsの値　比較
justify-contentsプロパティの値がいろいろたくさんあり、紛らわしいので整理する。 (特に"space-between", "space-around", "space-evenly"が紛らわしい)

### start
デフォルトの状態。要素を先頭に寄せている。
[![start](https://i.gyazo.com/d15e7985c9fccf4667308b1dabd2efae.png)](https://gyazo.com/d15e7985c9fccf4667308b1dabd2efae)

### space-between
各要素を均等に配置。先頭と末尾の要素は端に寄せている。
[![space-between](https://i.gyazo.com/339da8729ce37de2918e04a54bbe62c6.png)](https://gyazo.com/339da8729ce37de2918e04a54bbe62c6)
### space-around
各要素を均等に配置。  
要素間の間隔は先頭・末尾の要素と端の間隔の２倍。
[![space-around](https://i.gyazo.com/8add69ae52d7c3595955815d9498bcd3.png)](https://gyazo.com/8add69ae52d7c3595955815d9498bcd3)

### space-evenly
各要素を均等に配置。  
先頭・末尾の要素と端の間、要素間の間隔は全て等しい。
[![space-evenly](https://i.gyazo.com/e85f2d387741df1774e4b946f77a07bf.png)](https://gyazo.com/e85f2d387741df1774e4b946f77a07bf)

[参考記事](https://developer.mozilla.org/ja/docs/Web/CSS/justify-content#%E4%BE%8B)