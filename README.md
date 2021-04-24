# linebot-hinachan

避難をサポートするLINE Bot「避難場所確認Bot 安心ひなちゃん」（Python3, Flask, Heroku）のコードです。

### Botの説明
http://www.lovemysoulsoul.com/entry/2019/10/24/040250

### コードの説明
https://qiita.com/lovemysoul/items/5ad818220d65b74351a5

### 備考

__使用データ__
- 避難情報の確認には以下のデータを使用しています。  
出典：国土地理院ウェブサイト（http://www.gsi.go.jp/bousaichiri/hinanbasho.html）  
加工：「指定緊急避難場所データ」（国土地理院）（http://www.gsi.go.jp/bousaichiri/hinanbasho.html）を一般社団法人社会基盤情報流通推進協議会（AIGID） が加工して作成  
AIGIDによる更新日：2019年5月13日  
（各市町村長による指定緊急避難場所の指定日とは異なります。）

__免責事項__
- 本サービスで提供する情報については、正確な情報を提供することに努めますが、情報の完全性を保証するものではありません。
- 本アカウント管理者の故意または重過失による場合を除き、本サービスの利用または利用不能により生じる損害について、一切の責任を負いません。
- 本サービスの内容を予告なく変更・終了することがあります。
