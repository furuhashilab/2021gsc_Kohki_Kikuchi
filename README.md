# 2021gsc_Kohki_Kikuchi
菊池洸希の2020年度ゼミ論用レポジトリ
# 【2021年度ゼミ論】「Mapbox GL JS」Style Specificationの日本語訳作成と図式化
地球社会共生学部　地球社会共生学科　3年A組63番  

学籍番号：1A119059  　氏名：菊池洸希 

指導教員：古橋 大地教授   

©︎Furuhashi Laboratory/Kikuchi Kohki, CC BY 4.0

## 概要  
本研究では、「Mapbox GL JS Style Specification - Layers」の日本語訳を作成し、その概要を図式化した。

## Introduction
　1970年代、四分木（Quadtree)というデータ構造が生まれてから今日に至るまでデジタルマップは進化を続けてきた。2000年代にはタイル技術が生まれ、2005年にGoogleがラスターピラミッドの機能を持ったラスタータイルマップの完成版であるGoogleマップをリリースした。2006年、ブラウザで地図データを表示するためのJavaScriptライブラリであるOpenLayersがリリース。ライブラリを非公開にしているGoogleマップに対して、OpenLayersはオープンソースであった。さらに2011年には、これらに並んで広く使われているLeafletがVladimir Agafonkin氏によって開発される。Vladimir Agafonkin氏が２０１３年にMapboxに加入すると、翌年にベクタータイルマップに対応したオープンソースライブラリである「Mapbox GL JS」をリリースした。これは2020年に行われたv2.0への移行によって独自ライセンス化するが、この件に批判的なユーザー達が同年、MapboxGLエコシステムのフォークであるMapLibreを開始した。こうしてデジタル地図は進化を続け、現在では非常に速く、軽量で、自由な地図開発が可能になっている。しかし、地図開発において重要なドキュメントの多くは日本語対応していないのが現状である。今後、日本でより多くの人が地図開発を行えるようにこれらのドキュメントを日本語に翻訳していく必要がある。また、地図開発の学習を始める上で、ドキュメントの構造が図式化されているとより理解が深まるが、まだドキュメントの図式化は進んでいない。本研究では、国土地理院が開発している「地理院地図Vector（仮称）」にも採用されている「Mapbox GL JS」のStyle Specificationで特に重要な項目であるLayersの日本語訳を作成し、その概要を図式化した。

## Methods　　
本研究で行ったことは以下の二つである。
  
**①「Mapbox GL JS Style Specification - Layers」の日本語訳の作成**

Githubレポジトリ[「StyleSpecification4mapbox」](https://github.com/furuhashilab/StyleSpecification4mapbox)内に、「Mapbox GL JS Style Specification - Layers」の日本語訳をMarkdown形式で作成する。各タイトルやワードには原文と同様のリンクを付け、Mapboxのページに移動できるようにする。また、列挙型で用いられる"visible"や"none"のようなワード、ブルー値で用いられる"true"と"false"、文字列の配列で用いられる"OpenSans Regular"や "Arial Unicode MSRegular"等のワードは開発の際にそのまま使用することを考慮し、原文の通りに記載する。
  
**②「Mapbox GL JS Style Specification - Layers」の図式化**  

UML クラス図の形式に則り、「Mapbox GL JS Style Specification - Layers」の図式化を行う。図の作成にはCanva(グラフィックデザインプラットフォーム)を利用する。レイヤー構造が視覚的に把握できるよう、配置と配色を構造ごとに変更する。また、オプション機能にはアイコンを付け、図をシンプルに表現する。

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

列挙型で用いられるワード等、一部原文のままにしたワードがある。しかし原文にはまだ多くのコードとして記述するワードがあり、本研究の結果ではその選択に一貫性を欠いた。和訳すべきワードとそうでないものとの正しい線引きをしたい。

### 図式化について

図式化し、発見した課題は以下の３つである。

**1.情報の取捨選択**

「Mapbox GL JS Style Specification - Layers」は最も記述の多いドキュメントであり、その多くがタイプの詳細な設定についてである。本研究ではこれらを全て図にまとめるのは情報過多であるとの判断で、タイプ１０種類のみを掲載している。タイプの詳細な設定なども図式化したい。



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
