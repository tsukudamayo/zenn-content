---
title: "有馬記念予想一人アドベントカレンダー1日目"
emoji: "🐙"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [GCP]
published: true
---

# これは何ですか？
この記事は@tsukudamayo(わたし)が機械学習などをいかして、集められそうな
データを使って有馬記念をしゃぶりつくそうとする一人アドベントカレンダーです。
予想を当てることもそうですが、競馬とデータで何かおもしろいことが出来な
いかを考えていきたいです。

# 目的
なぜ、このようなアドベントカレンダーをやろうとしているのかは以下の理由
です。
- 競馬が好き
- MLOpsやりたい
- Vertex AI Pipelinesを使いたい

## 競馬が好き
単純に競馬が好きです。最初にちゃんと見たレースはマヤノトッガンが勝った
天皇賞春です。マヤノトップガンがサクラローレルやマーベラスサンデーを
差し切ったレースです。当時のライスシャワーのレコードを3秒近く更新し
たレースでした。このレースでマヤノトップガンのファンになりました。(こ
のレースを最後にマヤノトップガンは屈腱炎で引退してしまいましたが...)
これ以降競馬はテレビを中心に見ています。馬券を買ったりもしますが、あま
り当たったりはしません。唯一当たった万馬券はヒシミラクルーサンライズジェ
ガーで決まった天皇賞春です。そういえばミラクルおじさんが話題になりまし
たね...

- マヤノトップガンが勝った天皇賞春
<iframe id="ytplayer" type="text/html" width="640" height="360"
  src="https://www.youtube.com/embed/82pP6N6GAas?autoplay=1&origin=http://example.com"
  frameborder="0"></iframe>
- ヒシミラクルが勝った天皇賞春
<iframe id="ytplayer" type="text/html" width="640" height="360"                              src="https://www.youtube.com/embed/2iy6BoD03Vo?autoplay=1&origin=http://example.com"       frameborder="0"></iframe> 

## MLOpsやりたい, Vertex AI Pipelinesを使いたい
- MLOpsの知見をためたいです

# 構成
競馬を分析するシステムとしては以下のように現在は考えています。
- インフラ(GCP, Vertex AI Pipelines)
- クローラ(Scrapy? Puppeteer?)
- データ分析基盤(BigQuery)
- モデル構築,推論(Vertex AI)

# スケジュール
だいたい以下のようなスケジュールで進めたいです。
- 12/1~12/8 データのクローリング、前処理
- 12/9~12/17 データの分析
- 12/18~12/25 モデル構築、推論

明日から有馬記念を予想するためにはどのようなデータが必要なのかを検討し
ていきたいと思います。
