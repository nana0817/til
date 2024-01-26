# object-fitプロパティ
CSSのobject-fitプロパティは画像や動画をコンテナの中にどのようにはめ込むかを設定する。

## 用語
### 置換コンテンツ
object-fitプロパティを適用したimgタグやvideoタグの中身のこと。
### アスペクト比
画像や画面における横と縦の長さの比率のこと。一般的に「横：縦」で示される。

---
### object-fit: none;
置換コンテンツは拡大縮小されない。
[![Image from Gyazo](https://i.gyazo.com/e6d424758b5f45ef81733312881f7bfd.png)](https://gyazo.com/e6d424758b5f45ef81733312881f7bfd)


### object-fit: contain;
置換コンテンツはアスペクト比を維持したまま、要素のコンテンツボックスに**収まるように**拡大縮小される。
[![Image from Gyazo](https://i.gyazo.com/fde97a315422144b478f66b0cfbfddad.png)](https://gyazo.com/fde97a315422144b478f66b0cfbfddad)

### object-fit: cover;
置換コンテンツはアスペクト比を維持したまま、要素のコンテンツボックス**全体を埋めるように**拡大縮小される。
[![Image from Gyazo](https://i.gyazo.com/2d173a9c6aea28f1c2dab7050e4586d5.png)](https://gyazo.com/2d173a9c6aea28f1c2dab7050e4586d5)

## ???
### object-fit: fill;
置換コンテンツは、要素のコンテンツボックス全体を埋めるサイズになる。オブジェクト全体が完全にボックスの中を埋める。オブジェクトのアスペクト比がボックスのアスペクト比と合わない場合は、オブジェクトは合うように引き伸ばされます。
[![Image from Gyazo](https://i.gyazo.com/5b78bd023080ab68029f4b8c027d88f3.png)](https://gyazo.com/5b78bd023080ab68029f4b8c027d88f3)

### object-fit: scale-down;
コンテンツは **none** または **contain** を指定したかのようにサイズが決められ、オブジェクトの実際のサイズが小さいほうを採用します。
[![Image from Gyazo](https://i.gyazo.com/8f4f903d11d70b3a70d946465239c210.png)](https://gyazo.com/8f4f903d11d70b3a70d946465239c210)

[参考（object-fit）](https://developer.mozilla.org/ja/docs/Web/CSS/object-fit#%E4%BE%8B)  
[参考（アスペクト比）](https://www.android.com/intl/ja_jp/articles/342/#:~:text=%E3%82%A2%E3%82%B9%E3%83%9A%E3%82%AF%E3%83%88%E6%AF%94%E3%81%A8%E3%81%AF%E3%80%81%E7%94%BB%E5%83%8F,%E9%81%B8%E3%81%B6%E3%81%93%E3%81%A8%E3%81%8C%E3%81%A7%E3%81%8D%E3%81%BE%E3%81%99%E3%80%82)