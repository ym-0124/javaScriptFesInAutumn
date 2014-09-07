# @ampersand_xyz
- jQuerry Differdでネストが深くなるのを回避する
- → CSSでもかけるよ!  
- 
CSSのTransitionsモジュール
hoverセレクタを使って終点を指定
色の線形変化はjQueryUIのプラグインで実現できるが...

ANimation モジュール
キーフレーム(途中のキキーとなるアニメーションのフレーム)による動きの定義
Webkit Keyframes
rotate3D

ブラウザBender Prefix 必要

## CSS3でjQuery使わなくてもアニメーションなんとかなる？
→ JSとCSSの連携したい

JSでTransitonの終点を書き換えてやりゃJSで処理可能

## 複数の要素を順番に動作させたい
→ アにメーションイベント
CSS3によるアニメーションイベント

Transitionend
animationstart
animationend
animationiteration
- Transitonend
TOPとLEFTの移動それぞれTransitonendがはしるので，2回イベント発火する

## Animationモジュール
$(".block_1").bin('WebkitAnimationStart'){}
$('.block_1').bind('webkitAnmiationEnd'){};
$('.block_1').bind('webkitAnmiationIterator'){};
## まとめ
要素の動きはCSSで十分じゃないの？
複雑な動きはなおさら
タイミングの調整だけJavascript
Differとか，Javascriptで数値設定を，CSSでアニメーションの表現を．
BenderPrefixは今だに問題

# KDDIWebコミュニケーションズ 阿部正幸
CPI エバンジェリスト
Material Design
→ Evernote で採用

## Material Desingn
Googleが提供するユーザにわかりやすいデザイン提供指標
紙とデジタルの融合のデザイン

## ガイドライン
animation
Style
レイアウト
コンポーネント

## 指標はいいけど
どうやってどうやって実装するの？
→ Polymerをつかう

## Polymer
JavascriptのUIフレームワーク
Webこんポーネンツは標準になる予定の技術
必要なUIはこんポーネンツとして登録されている
カスタムエレメントを作るか，コンポーネントを呼び込んで使う

## platformJSとpolymerJSを
<Polymer-element 
  <template

カプセル化されているので，指定した変更部のみが変更される

## まとめ
Web ICON のように，エレメントを読み込んでWEbを構築，再利用，複数人での作業がしやすい
WebComponentが標準になるんで，作り方気をつけてね

# D3.jS
http://www.slideshare.net/YoshinoriKoba/d3js-38787078?qid=9a5a0191-05c3-4c83-a633-1e539275589d&v=qf1&b=&from_search=2

＃	