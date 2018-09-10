# WebSiteBuilders
※必ずindex.htmlをダウンロードしてください．
## ファイル構成
|フォルダ名 |説明                         |
|:--        |:--                          |
|top.html |トップベージ．様々なページにリンクする．|
|event.html |翔鴎祭2日間の各会場のタイムテーブル． |
|group.html |翔鴎祭参加団体の紹介． |
|access.html |最寄り駅情報とGoogleMap．|

## top.html
### 内容
* 文化祭の開催日時
* 文化祭の紹介文
* 学校の連絡先
* 学校のサイトへのリンク
* Twitterの埋め込み
* 各ページへのリンク

## event.html
### 内容
* タイムテーブル
* 企画団体の紹介

タイムテーブルは広報係から入手する．

## group.html
### 内容
* 参加団体の紹介

### アイコンの形式
```
<div class="panel">
   <img class="icon" src="images/food/food_01.png">
   <div class="explanation">
      <p class="title">Cross Dresstar Cafe</p>
      <p>活動場所:703</p>
      <p>活動日:1日目 2日目</p>
   </div>
</div>
```
団体の紹介文とアイコンは広報係から入手する．

## access.html
### 内容
* 地図
* 最寄り駅
* 学校の連絡先

地図の埋め込み方は以下の通り．

```
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3248.932782448659!2d139.62640581573652!3d35.48120688024137!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60185c1f0cbcbd89%3A0x2bd0055a8cb0e85b!2z56We5aWI5bed55yM56uL56We5aWI5bed57eP5ZCI6auY562J5a2m5qCh!5e0!3m2!1sja!2sjp!4v1536565163238" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
```
大きさの変更は
```
width="600" 
height="450"
```
の値をピクセルで指定．

最寄り駅は，
* 東急東横線 「東白楽駅」下車 徒歩3分
* ＪＲ京浜東北線・横浜線 「東神奈川駅」下車 徒歩9分
* 京浜急行線 「仲木戸駅」下車 徒歩10分





