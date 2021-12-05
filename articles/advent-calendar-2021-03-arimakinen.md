---
title: "有馬記念予想一人アドベントカレンダー3日目"
emoji: "🌟"
type: "tech" # tech: 技術記事 / idea: アイデア
	topics: [python, nodejs]
published: true
---

# データを取得するURL
データを取得できそうなURLを集めてみました。
- [JRA公式](https://www.jra.go.jp/datafile/seiseki/g1/arima/result/arima2020.html~)
  - 65回分のレース成績
  - 1984-2020年のレース画像
- [ 競馬ラボ](https://www.keibalab.jp/db/race/202012270611/past.html)
  - 過去10年分
  - 血統
  - 前走
  - ペース
- 
- [ウマニティ](https://umanity.jp/racedata/graderace/0008/past_result.php)
  - 過去10年分
- [深く考えない競馬](https://fukakukeiba.com/arima-kinen/)
  - 過去10年分
- [優馬](https://umakeiba.com/%E6%9C%89%E9%A6%AC%E8%A8%98%E5%BF%B5/dataroom/last/)
  - 1986年以降のデータ
- [netkeiba](https://db.netkeiba.com/?pid=race_list&word=%5E%CD%AD%C7%CF%B5%AD%C7%B0)
  - 1957年以降のデータ

# スクレイピング、クローリングの開発環境
スクレイピングで使うライブラリの候補をを挙げています。
最終的にはCloud FunctionsやLambdaを使ってクローラーを構成したいので、
RuntimeがありそうなPython, Node.js, Goあたりを候補に考えています。

## Scrapy
- [doc](https://docs.scrapy.org/en/latest/index.html)
- python

## Puppeteer
- [doc](https://pptr.dev/)
- node.js
