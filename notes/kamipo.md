# Railsdm Podcast \#7

## 収録日時

2018-12-19 (水) 19:00-21:00 @ 永和システムマネジメント

## Guest

@kamipo

## 聞き手

@yahonda

## わいわい担当

@koic, @y_yagi, @mtsmfm, @ota42y

## 進行補助・制作

@yhirano55

## Contents

### Introduction by yhirano55

* Railsdmとは?
* 収録日・収録場所の紹介

### ゲスト紹介

* ゲスト紹介（自己紹介）
    * kamipoさん: Railsコミッター, Arm Treasure Data
* 共演者紹介

## Topics

- Railsコミュニティとのかかわり
  - Rails Developer Meetup
    - https://www.youtube.com/watch?v=cxLvumKp-0M&t=1458s
    - https://railsdm.herokuapp.com/issues/1
  - OSSパッチ会
    - 参加されている理由を教えてください
- Ruby 2.6とRails
  - Ruby 2.6(dev)中の変更をどのタイミングでRails(master)に対応するのがいいとおもいますか
    - BigDecimal.newが最終的には復活した(Ruby 2.6 rc2時点)
    - Ruby 2.6の変更で行われたRailsの変更
      - BigDecimal
        - https://github.com/rails/rails/pull/31452
        - https://github.com/ruby/bigdecimal/commit/5337373
      - Range
        - https://svn.ruby-lang.org/cgi-bin/viewvc.cgi?revision=63453&view=revision
        - https://github.com/rails/rails/pull/32938
      - “Real” keyword argument
        - https://bugs.ruby-lang.org/issues/14183
  - Ruby 2.6が「サポート」するRailsバージョンは
    - http://koic.hatenablog.com/entry/exclude-rails-4-2-with-ruby-2-6
  - Rails 6がサポートするRuby
    - Rails 6は2.4.1以上の予定 https://github.com/rails/rails/pull/32034
    - 2.5にあげる計画などありますか
    - Rails 5は2.2以上でスタートし、Rubyが毎年リリースされる一方、Rails 5.0がJune 30, 2016、Rails 6.0はsometime in 2019と3年あり、Rails 5がサポートされている間にRuby 2.2はEOLした
      - https://www.ruby-lang.org/en/news/2018/06/20/support-of-ruby-2-2-has-ended/
- Railsのリリースサイクル
  - alpha, beta, rcの段階が何を意図しているのか
  - Railsアプリケーション開発者、3rd party gem開発者に期待していること
    - alpha, beta, rcの段階でやってほしいこと
- 仕事のRailsアプリケーションのバージョンとその機能がリリースされるまでの距離
  - pull requestが開かれる前から準備を進めていたとすると、だいぶ長い時間かかってRailsで利用できるようになった印象がある
  - これらの新機能に対応するのは、中長期的な投資なのか、すでにユースケースがあったのか、新機能だから対応したのかなど理由を教えてください
  - Virtual column support for MySQL 5.7
    - https://github.com/rails/rails/pull/22589
      - Opened on 2015/12/15
      - Merged on 2017/2/2
      - Released on 2017/4/27 as Rails 5.1.0
  - Expression index support for MySQL 8.0.13
    - https://github.com/rails/rails/pull/34307
    - Opened on 2018/10/15
    - Merged on 2018/10/17
    - Will be released as Rails 6.0 in 2019
- 仕事で使っているRailsのバージョン、独自forkされていますか(もしよろしければ)
- MySQL サポートについて
  - 5.5と5.6対応はこのままだとomakase感がないので、`ROW_FORMAT=DYNAMIC`追加される予定はありますか
  - Rails 6でのMySQL 5.5以上サポート https://github.com/rails/rails/pull/33853
  - デフォルトキャラクタセットがutf8mb4 https://github.com/rails/rails/pull/33608
    - Rails DM https://www.youtube.com/watch?v=cxLvumKp-0M&t=1458s 22:21頃
    - https://github.com/rails/rails/issues/33596 by DHH
  - MariaDBについて
    - いつまでmysql2 adapterとして対応し続けられそうですか(感覚的なもので)
- rails/railsメンテナーとして
  - pull requestやissueをどのくらい読んでいますか
    - pull requestはアサインされていないものでもレビューしている印象
  - マージしやすいpull requestというものはありますか
  - レビューの際に心がけていること
  - 直接masterにpushするときとpull requestを開くときのちがい
  - もしRails committerが推薦制なら誰を推薦しますか
- RuboCop
  - 仕事でRuboCop使ってますか
  - Railsのpull requestで指摘した比較的cosmeticな変更が.rubocop.ymlに入り、カバーしきれないfalse negative(見逃し)などがHeartbeat.rbでkoicさんにフィードバックされるループについて知りたいです
- オフトピック
  - 土日の時間の使い方
  - いつ寝てますか
  - Heartbeat.rbについて

* 参加者質問タイム
* Railsdmへの要望

## 注意事項

* 事前に確認していただいた後、NGな話題についてはスキップします。予めお知らせください。
* トーク内容は事後で編集することは可能です。
* 内容は脱線し、変更されることがあります。
* 会話したいことがあれば、話題を振っていただいて構いません。
* 上記をすべてトークで網羅する必要はありません。
