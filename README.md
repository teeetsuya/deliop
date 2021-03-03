# 目的：初回ポートフォリオを作成する

## メンバー：teeetsuya

## 1.哲学 : 好きなことを楽しむ、無駄なものを省く

## 2.習慣分析・課題・アイデア
### 2-1. 
- 料理と美味いものを食べるのが好き
- ただ、最近太ってきたから対策が必要
- 食費が嵩んでる
- 食材購入は１週間に1度まとめ買い
- 食事は毎食欠かさない
- 外食や中食は週1程度
- 冷凍食品はうどんくらしか食べない
- それでも食費が2人で月60,000円以上
- どうやら食べすぎている
- 気付くと冷蔵庫の中に賞味期限近いもの、古くなりそうな食材がある
- 食材を無駄にしたくないので腐らせる前に一気に使う
- 気づいたら夕食が、高頻度で豪華になる
- 作ったものを食べ切ってしまう
- 無意識に豪華に大量に高頻度に食材を大量消費している
- 毎食献立を考えるのも、最適な量を作るのも大変だわ・・・
  - 1週間のうち1つ、どうしても食べたいものを選んで、そのメニューを中心に献立を作成
  - まずは1品ずつ、品目を投稿できる機能を作る
  - 画像も投稿できる
  - 必要な食材と量をデータ入力できる
  - 調理手順はテキストにする
  - PULS1：食材から品目を検索、品目から食材を検索できるようにデータ紐付けもしたい
  - PULS1：ジャンル、カロリー、嗜好、所要時間など各品目と結びつけたい
  - PULS1：食べる人数と材料の必要量を相関させる
  - PULS1：作った食事の履歴を作成
  - PULS1：料理を採点、できるだけ色々な食事を楽しめるようにレコメンドには新しいメニューを表示
  - PULS1：カレンダーに食事履歴を表示、普段使ってるカレンダーと同期出来たら嬉しいな
  - PULS1：食材は名前が多いので、曖昧検索できるようにしたい
  - ほか

## 3.テーマ
食事、習慣、時短、節約、ロス削減、フードロス・SDGs、在庫管理

## 4.コンセプト
美味いものを毎日簡単に無駄なく作って好きなことを楽しむ
### Deli
- 食事：おいしい食事 = Fine Food = Delicatessen
- 美味：おいしい料理 = Delicious
- 良質：間違いない結果(食事)を届けられる = Deliverable
- 最適：買い物( = Delivery)を無駄なく
### op
- 公開：情報がオープン = Open
- 楽観：美味いものを安心して、時間に追われることなく = Optimizm
- 選択：食事の選択肢が多い = Optional
- 最適：食事を簡単に、食材を無駄なく = Optimization

## 5.名前 デリオプ：Deliop

## 6.デザイン
温かみがあり食欲の湧く暖色を中心にシンプルなデザイン

## 7.内部設計
- CRUD操作
- リソース設計
- ER図　：　Entity Relationship Deagram
   > https://it-koala.com/entity-relationship-diagram-1897#ER　
- クラス図
　 > https://cacoo.com/ja/blog/how-to-write-class-diagram/#:~:text=%E3%82%AF%E3%83%A9%E3%82%B9%E5%9B%B3%E3%81%AFUML%EF%BC%88%E7%B5%B1%E4%B8%80,%E5%9B%B3%E3%80%8D%E3%81%A7%E3%81%82%E3%82%8B%E3%81%93%E3%81%A8%E3%81%A7%E3%81%99%E3%80%82
- URI設計：
  - URI：Uniform Resource Identifier 
    > https://ferret-plus.com/4637
  - API設計：Application Program Interface
  
## 8.実装
- WAF：
- PHP：Laravel & Laravel/ui
  - Laravel基礎：https://coinbaby8.com/laravel-php-dekirukoto.html
  - (*CSS：Bootstrap)
- JavaScript：React
  - Front End：Node.js/npm、webpack、babel
    > https://coinbaby8.com/laravel-frontend.html
### MVC
#### Model作成
- ORM：Laravel：Eloquent
 > https://corporate.inter-edu.com/developper/1458
#### View作成
- Webサーバ設定：Laravel
 > https://qiita.com/sskmy1024y/items/c2e434941400bd4ee82c
#### フォント
- FontAwesome
　> https://fontawesome.com/

## 9.マーケティング
### PEST
- Poiltics：栄養、人材、科学的根拠、SDGs、アレルギー、ハラール、脱炭素、廃プラ、フードロス
　> https://www.mhlw.go.jp/content/000587161.pdf
### Economy：2人以上世帯食費約950,000円/年
　> https://www.stat.go.jp/data/kakei/longtime/index.html#time
### Society：健康志向、簡便指向、美食指向、経済指向
　> https://honote.macromill.com/report/20200709/
### Technology：スマートキッチン、デリバリーサービス、ウェアラブルなど

###3C
#### Customer：
- 夫婦共働き20代後半
- 健康節約指向
- 時間ない
- 実家が遠い
- 自分の時間と二人の時間も大切にしたい
#### Competitor：
- クックパッド
- ミーニュー
- Eレシピ
- タベリー
- 今日の献立
- DELISH KITCHEN
- コンダッテ
- Pecco
- Racook
- Amarimo
- 楽天レシピ
- e食材辞典
- ソラレピ
- シェフごはん
- 食リズム
　> https://smartlog.jp/170505
#### Company：
- いまNULL
- 伸びしろ
### STP：
#### 細分化：Segmentation
#### ターゲット：Targeting
- 人口動態軸：20台半ば〜30代半ば、男女、既婚、2人家族
　> 夫婦世帯数増加傾向：約1,300万世帯／全国
　> https://news.yahoo.co.jp/byline/fuwaraizo/20190726-00134170/
- 地理軸：都心部
- 社会心理学軸：平日フルタイムワーク、子作り検討、節約指向、時折贅沢したくなる
- 行動軸：必要なタイミングで必要なものを購入、預金は定額管理、余剰金額は預金・投資に充てる
- マーケティング手法：集中型
#### ポジション：Positioning
- X軸：コスト
- Y軸：使い勝手（指標：品数、UI/UXを数値化)
### 4P
- Product： 投稿サイト
- Price： Free
- Place： Web
- Promotion：Twitter、ブログ(ゆくゆく)、Wantedly(転活用)

## 10.運用
### パフォーマンスアップ
- Google PageSpeed Insight
　> https://developers.google.com/speed/pagespeed/insights/?hl=ja
- ベンチマークテスト
　> ApacheBench http://dev.classmethod.jp/tool/ab-tutorial/
- サーバー構成の見直し、分散環境の構築
- フロントエンドWebサーバ
　- HTMLやJSON等の静的ページの配信担当。
　- 動的な配信が必要だったらアプリケーションサーバに渡す。
　　> nginxがおすすめ。高速かつ設定記述がシンプル。
- アプリケーションサーバ
- キャッシュサーバ
- CDN

## 参考資料：
- Git運用
 > https://qiita.com/gumimin/items/63dcb36d4730213bd63a
