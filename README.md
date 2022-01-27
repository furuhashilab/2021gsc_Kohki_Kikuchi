# 2021gsc_Kohki_Kikuchi
菊池洸希の2020年度ゼミ論用レポジトリ
# 【2021年度ゼミ論】国連ベクトルタイルツールキット普及のための「Mapbox GL JS Style Specification」和訳と図式化
地球社会共生学部　地球社会共生学科　3年A組63番  

学籍番号：1A119059  　氏名：菊池洸希 

指導教員：古橋 大地教授   

©︎Furuhashi Laboratory/Kikuchi Kohki, CC BY 4.0

## 概要  
本研究では、UNVT（国連ベクトルタイルツールキット）が日本でより幅広く活用されるために、そのスタイリングにおいて重要である「Mapbox GL JS Style Specification」のLeyersの項目を翻訳し、概要を図式化した。


## Introduction
　古橋研究室では、ゼミ生全員がグラフィックレコーディング（以下グラレコ）の作成が必須である。しかし、新型コロナウイルスの影響によりグラレコを対面で学ぶ機会がなくなり、グラレコ部以外のゼミ生からグラレコの描き方が分からず、「時間がかかる。うまくかけない。」といった声を聞くことが多かった。そこで、対象を古橋研究室のゼミ生、新しく入ってくる新ゼミ生としたオンラインでも使用できるグラレコ補助アプリの制作を考えた。グラレコ初心者やグラレコに苦手意識がある人には「グラレコの基礎を学べる用」・「レイアウトやイラストに困ったときのお助け用」として、グラレコ部やグラレコに慣れてきた人には「自分のグラレコやイラストなどをまとめる用」としての使用を目的とする。　　

## Methods　　
本研究で行ったことは以下の二つである。
  
**①「Mapbox GL JS Style Specification - Layers」の和訳**

「Mapbox GL JS Style Specification - Layers」の和訳を作成した。各タイトルやワードに原文と同様のリンクを付け、Mapboxのページに移動できるようにした。また、"visible"や"none"のような列挙型で用いられるワードなどは、原文のまま使用する。

  
**②「Mapbox GL JS Style Specification - Layers」の図式化**  

UML クラス図の形式に則り、「Mapbox GL JS Style Specification - Layers」の図式化を行った。レイヤー構造が視覚的に把握できるよう、配置と配色を構造ごとに変更した。また、オプション機能にはアイコンを付け、図のシンプル化を目指した。


## Results　　

### 「Mapbox GL JS Style Specification - Layers」日本語版 　Githubレポジトリ
https://github.com/furuhashilab/StyleSpecification4mapbox/blob/ed5cd80c0f0872f9057f81ea1e251339c9d272d4/Layers.md

![GithubレポジトリのQRコード](https://github.com/furuhashilab/2021gsc_Kohki_Kikuchi/blob/da23dbb02244ca8086951ecbc5ff525f8961203b/qr_StyleSpecification4mapbox:Layers.png) 

### UML クラス図
![UMLクラス図](https://github.com/furuhashilab/2021gsc_Kohki_Kikuchi/blob/cafef41c5575c89a10a37f6e00c804a0881971e4/uml_layers_01.png)

## Discussion　
### 和訳について

和訳を作成し、発見した課題は以下の３つである。

**1.翻訳の一貫性**

列挙型で用いられるワード等、一部原文のままにしたワードがある。しかし原文にはまだ多くのコードとして記述するワードがあり、本研究の結果ではその選択に一貫性を欠いた。和訳すべきワードとそうでないものとの正しい線引きはどこであるか議論すべきである。

### 図式化について

図式化し、発見した課題は以下の３つである。

**1.情報の取捨選択**

「Mapbox GL JS Style Specification - Layers」は最も記述の多いドキュメントであり、その多くがタイプの詳細な設定についてである。本研究ではこれらを全て図にまとめるのは情報過多であるとの判断で、タイプ１０種類のみを掲載している。今後はタイプの詳細な設定に関しても図式化すべきである。



## Conclusion　　　
今後の課題としては、以下の二つが挙げられる。　　    
- コンテンツの充実度（グラレコの描き方、グラレコとは、デジタル版について）　　　　    
- Templateが再考の余地あり　　　　　　　　　    
　　    
また、グラレコは組織だけでなく、個人の思考力を助けることを改めて学び、研究を通してグラレコの可能性、有効性を知ることができた。グラレコではイラストとキーワードを主に使用していることから、言語や文化を超えての意思疎通に有効性があると考える。今後ますます発展していくと考えられるグラレコにおいて、グラレコ専用アプリが増加していくのではないかと考えられる。

## Reference/参考文献

## Acknowledgements/謝辞
本研究を進めるにあたり地球社会共生学部の古橋大地教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。
 
## 資料
**進捗管理用プロジェクト**  
https://github.com/furuhashilab/2021gsc_Kohki_Kikuchi/projects/2  
**最終プレゼン資料**  
https://docs.google.com/presentation/d/13QyPYV9XP0rMW9lBEhvvMw2V1saTevBbOVW-3ukvOms/edit?usp=sharing    
**参考文献リスト**   
https://docs.google.com/spreadsheets/d/1XJQ7ZuN18UEj8fmp4vFUclrJZ3TLgDixdDmo9DB-RRg/edit#gid=0　  
**「Mapbox GL JS Style Specification」日本語版　Githubレポジトリ**  
https://github.com/furuhashilab/StyleSpecification4mapbox/blob/ed5cd80c0f0872f9057f81ea1e251339c9d272d4/Layers.md
