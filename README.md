# 2021gsc_Kohki_Kikuchi
菊池洸希の2020年度ゼミ論用レポジトリ
# 【2021年度ゼミ論】国連ベクトルタイルツールキット普及のための「Mapboox GL JS tyle　Specification」和訳と図式化
地球社会共生学部　地球社会共生学科　3年A組63番  

学籍番号：1A119059  　氏名：菊池洸希 

指導教員：古橋 大地教授   

©︎Furuhashi Laboratory/Kikuchi Kohki, CC BY 4.0

## 概要  
本研究では、UNVT（国連ベクトルタイルツールキット）が日本でより幅広く活用されるために、そのスタイリングにおいて重要である「Mapboox GL JS Style　Specification」のLeyersを翻訳し、概要を図式化した。

**対象者**   
- 既に所属しているグラレコ部以外のゼミ生  
- 新しく古橋ゼミに入ってきたゼミ生  
- グラレコをやってみようかなと思っている人  
  
**対象環境**  
- 人数：1人  
- 方法：アナログ  
- グラレコ対象：オンライン会議やイベント、動画  

## Introduction
　古橋研究室では、ゼミ生全員がグラフィックレコーディング（以下グラレコ）の作成が必須である。しかし、新型コロナウイルスの影響によりグラレコを対面で学ぶ機会がなくなり、グラレコ部以外のゼミ生からグラレコの描き方が分からず、「時間がかかる。うまくかけない。」といった声を聞くことが多かった。そこで、対象を古橋研究室のゼミ生、新しく入ってくる新ゼミ生としたオンラインでも使用できるグラレコ補助アプリの制作を考えた。グラレコ初心者やグラレコに苦手意識がある人には「グラレコの基礎を学べる用」・「レイアウトやイラストに困ったときのお助け用」として、グラレコ部やグラレコに慣れてきた人には「自分のグラレコやイラストなどをまとめる用」としての使用を目的とする。　　

## Methods　　
グラレコ補助アプリの制作にあたって、①現状を分析、②必要なものを作成し、最終的にGlideを使用しアプリを開発した。　　
  
**①現状を分析**    
グラレコ作成で課題に感じていることをゼミ生に聞き取りを行った。グラレコ部以外のゼミ生がグラレコ作成時にどんなことを難しく感じているのか質問したところ、最も多かった意見はレイアウトについてだった。続いて使用する道具、似顔絵の描き方に課題を感じていることがわかった。また、以前から試行錯誤をしてきたアナロググラレコのデジタル化手法についてまとめた。  
  
**②必要なものを作成**  
(1) 現状分析の結果により、必要だと考えられる道具の種類、似顔絵の描き方、アナロググラレコのデジタル化の方法を説明するスライドを作成した。  
道具のスライド： https://speakerdeck.com/ayaka0324/dao-ju-hahe-gabi-yao   
似顔絵のスライド： https://speakerdeck.com/ayaka0324/si-yan-hui-falseshu-kifang　  　  
デジタル化のスライド： https://speakerdeck.com/ayaka0324/memowoshi-tutatesitaruhua-falseshi-fang　　  
(2) 最も多かった意見である「レイアウト」については、タイトルの位置（7種）、似顔絵の位置（5種）、レイアウト（4種）提案し、テンプレートを考えた。　　

**③Glideを使ってアプリを開発**  
Glideとは、「無料でGoogleスプレッドシートから5分アプリを作成する」というキャッチコピーを掲げるノーコードでアプリを作成できるツールである。  
Googleスプレッドシートには、②の(1)を含む「How To’s」、(2)を含む「Template」、イラストをまとめられる「Illustrations」、完成したグラレコを保存できる「My Grareco」の4つのタブを作成した。   
  
使用したGoogle Slide：https://docs.google.com/spreadsheets/d/1LnEmHl9IM6kedw12KFqJvQC5k6oSyGxur40ATxVma04/edit?usp=sharing　　

## Results　　
GithubレポジトリURL：https://github.com/furuhashilab/StyleSpecification4mapbox/blob/ed5cd80c0f0872f9057f81ea1e251339c9d272d4/Layers.md
![GithubレポジトリのQRコード](https://github.com/furuhashilab/2021gsc_Kohki_Kikuchi/blob/da23dbb02244ca8086951ecbc5ff525f8961203b/qr_StyleSpecification4mapbox:Layers.png)  

## Discussion　
**1.アプリの内容について**   

1)似顔絵やテンプレート    
似顔絵やテンプレートについてはすでに書籍でまとまられている。  
→Graphic Recorder 議論を可視化するグラフィックレコーディングの教科書（清水純子）  
はじめてのグラフィックレコーディング 考えを図にする、会議を絵にする。（久保田 麻美 ）  

2)道具  
道具は自由度が高く、特にこれでなくてはダメというものがない。  

3)デジタル化   
アナロググラレコをデジタル化する手法に言及されたものは、探した範囲では見つからない。（スキャナアプリの特集などはある)  

4)イラスト・グラレコをまとめる機能     
グラレコ作成後は共有するだけなのか。グラレコの1番の目的は「議論を可視化すること」     
しかし、まとめてみれるものがあってもいいのでは?      
　　    
**2.Glideについて**  　    
個人利用ではなく、全員のお気に入りやイラストが反映される。　　    
メリット：　全員のものが反映されるとイラスト語彙が増える　　    
デメリット：自分だけのお気に入りやMy Grarecoを作成できない。　    　　　

個人利用むけには　　    
①今回作成したものをtemplateに投稿する。　        　  
②Githubなどで連絡してもらえれば、こちらで同じアプリを作成しQRコードを共有する。　           　
　　     
        
**3.グラフィックレコーディングを「書く」か「描く」、どちらなのか**　　    
Graphic Recorder 議論を可視化するグラフィックレコーディングの教科書」（清水純子）、「はじめてのグラフィックレコーディング 考えを図にする、会議を絵にする。」（久保田 麻美 ）を読んだところ「描く」が一般的だった。　　

## Conclusion　　　
今後の課題としては、以下の二つが挙げられる。　　    
- コンテンツの充実度（グラレコの描き方、グラレコとは、デジタル版について）　　　　    
- Templateが再考の余地あり　　　　　　　　　    
　　    
また、グラレコは組織だけでなく、個人の思考力を助けることを改めて学び、研究を通してグラレコの可能性、有効性を知ることができた。グラレコではイラストとキーワードを主に使用していることから、言語や文化を超えての意思疎通に有効性があると考える。今後ますます発展していくと考えられるグラレコにおいて、グラレコ専用アプリが増加していくのではないかと考えられる。

## Reference/参考文献

## Acknowledgements/謝辞
本研究を進めるにあたり地球社会共生学部の古橋大地教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。
 
## 資料
**2020年度ゼミ論本文**  
https://docs.google.com/document/d/1dErgCbpDEs70XE7SZqAjZeJUcafG9hP3JCBMGZNyc0E/edit?usp=sharing　　  
**進捗管理用プロジェクト**  
https://github.com/furuhashilab/sotsuron2020/projects/15　　  
**最終プレゼン資料**  
https://docs.google.com/presentation/d/18dggqIuMX8O4rC9_XHh7Mr6lhmqKkXITzkOzVNiXjcs/edit?usp=sharing    
**参考文献リスト**   
https://docs.google.com/spreadsheets/d/1XJQ7ZuN18UEj8fmp4vFUclrJZ3TLgDixdDmo9DB-RRg/edit#gid=0　  
**Githubレポジトリ**  
https://github.com/furuhashilab/StyleSpecification4mapbox/blob/ed5cd80c0f0872f9057f81ea1e251339c9d272d4/Layers.md
