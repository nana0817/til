# opacityプロパティ
CSSのopacityプロパティは要素 (画像)の不透明度を設定する。不透明度とは要素の裏にあるコンテンツが隠れる度合いのことであり、「透明度」の逆。   
逆に言えば、不透明度を下げることで、画像などを透過させることができる。

## opacityプロパティの値
値には**数値** (number)と**割合** (percentage)をとることができ、それぞれ範囲は数値は0以上1以下、割合は0%以上100％以下

## それぞれの値の意味
**0または0%**  
要素は完全に透明になる。  
要素が全く見えず、裏にあるコンテンツがそのまま見えている状態。
[![Image from Gyazo](https://i.gyazo.com/ef3dee2b5609758768127c0af396f5f2.png)](https://gyazo.com/ef3dee2b5609758768127c0af396f5f2)

**0<数値<1 または 0%<割合<100%**  
要素は半透明になる。  
指定した値によって、要素の不透明度が変わる。  
30%  
[![Image from Gyazo](https://i.gyazo.com/a1a0b3131404fa652c91d054d0dbc899.png)](https://gyazo.com/a1a0b3131404fa652c91d054d0dbc899)  
50%  
[![Image from Gyazo](https://i.gyazo.com/b29375a8dc8c03cf0246cb9a7da517f8.png)](https://gyazo.com/b29375a8dc8c03cf0246cb9a7da517f8)  
80%  
[![Image from Gyazo](https://i.gyazo.com/c3c07b0b3e5635f19743fb77d9eccad3.png)](https://gyazo.com/c3c07b0b3e5635f19743fb77d9eccad3)  

**1 または 100%**  
要素は完全に不透明になる。  
裏にあるコンテンツが全く見えない状態。
[![Image from Gyazo](https://i.gyazo.com/918d3964ec1c9802b2a1cde526b90904.png)](https://gyazo.com/918d3964ec1c9802b2a1cde526b90904)  

[参考 (opacityプロパティ)](https://developer.mozilla.org/ja/docs/Web/CSS/opacity#%E4%BE%8B)