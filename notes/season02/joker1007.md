# Railsdm Podcast: Season 2-5
## 収録日時
2019年6月27日(木)

## 収録時間
19:00 〜 20:30 ごろ
東京都千代田区神田須田町2-3-1 NBF神田須田町ビル 7F 永和システムマネジメント 東京支社

## 出演者

- ゲスト: @joker1007
- 聞き手: @unasuke, @okuramasafumi

## イントロダクション
- 本日は6/27日木曜日、永和システムマネジメントさんの会議室をお借りして収録しています。
- 本日のゲストはRepro(リプロ)株式会社 CTO であるジョーカーさんです、よろしくお願いします。

## どのような人か
- それではまず、jokerさんについて紹介させていただきますと……
  - パーフェクトRubyの著者の一人
  - Repro株式会社 CTO
    - CTO オブ・ザ・イヤー2016[^cto]
  - インターネットカラオケマン
  - Gentoo Linux使い
  - RubyでRubyをhackする、黒魔術の使い手

## 黒魔術について
- jokerさんがAWSからインタビューされた記事が先日公開されました。記事ではReproがどのようにAWSを活用しているか、という内容にフォーカスしていました。
- なので、このpodcastではRubyという言語とjokerさんとの関わりについて掘り下げていこうかと考えています。
- jokerさんといえば、Rubyの言語機能を拡張してアクロバティックなことをやる、いわゆる「黒魔術」の使い手と言われることも多いですが……
- 例えば
  - [Pragmatic Monadic Programming in Ruby - Speaker Deck](https://speakerdeck.com/joker1007/pragmatic-monadic-programming-in-ruby)
    - モナドをRubyで使えるようにするもの
      - 「モナド」とはどういうtものなのか
  - [†Ruby黒魔術経典† - Speaker Deck](https://speakerdeck.com/joker1007/rubyhei-mo-shu-jing-dian)
- そのような、言語機能をハックする熱意はどこからくるのでしょうか？
  - > 「有用なアイデアをRubyの機能だけを使って実現してみる」
    - by tagomoris https://tagomoris.hatenablog.com/entry/2018/06/05/132931
- アイデアの出所はどこにあるのでしょうか？
  - Pragmatic Monadic Programming in Ruby ではモナドをRubyでどう実装するかの話だった
    - > Ruby黒魔術師として、自分が良いなと思っているデザインパターンであるモナドを、Rubyの世界で理想的に表現するならどうなるかということを考えて発表テーマとしました[^monad]
    - Ruby以外に触れてきたプログラミング言語について
      - 上ではScalaが挙げられている
- それを踏まえて最近のRubyについてどういう感情をお持ちでしょうか？
  - Pipe operator `|>`
  - numbered parameters `@1`

## 仕事の環境について
- 実は僕はjokerさんのブログを見てから仕事をLinuxでするようになったのですが [^linux1]
  - 仕事でLinuxで困ったことはないのですか？
    - 特にコードを書く以外のところで不便なことがないか[^linux2]
    - そういう僕はあまり無いかな……
- > archと悩んだがそれなりにgentoo党なので慣れてる方にした
  - とのことだが、その2つのdistributionのどのような点が気に入ってますか？(だいたいわかるけど……)
    - ローリングリリースがお好みということ？

## 働き方について
- jokerさんは「出社する意欲が減退した」的なことをTwitterでたびたび発言しています
  - 以前、「そもそも自分の仕事は出社したから仕事している・家にいるから仕事していない的なものではない」との趣旨の発言を聞いたことがある
    - 「シャワー中が一番ひらめく」旨の発言もあったと思うが、実際どういうときに仕事が進むあるいは進まないと思うか
    - 会社・自宅の作業環境はどんな感じ？
  - CTO含め社員が出社しなくても済むよう、会社として工夫していることがあったりするのか

## CTOという職種について
- CTOとして技術的なリーダーシップを発揮しているjokerさんですが、
  - CTOとして心がけていることはどんなことですか？
  - CTOに向いている人・向いていない人について
  - 理想のCTO像

## 著作について
- jokerさんは『パーフェクトRuby』『パーフェクトRuby on Rails』を執筆し、同人誌もいくつか執筆されていますが、
  - 今後何か本を書く予定はありますか？
    - 特に既存の本の改訂版
      - (甚六さんからおたよりが来ているので後回しでもいいかも)
    - 同人誌のアイデア

## 好きなものについて
- お気に入りの技術書（かその他ジャンルの本）
- 好きな日本酒の銘柄
  - 日本酒についてはイベントを主催するほどですが、いつごろから嗜むようになったのですか
  - 日本酒を飲むときは何をアテにしますか
- 好きな音楽
- jokerさんといえば「インターネットカラオケマン」としても知られていますが
  - 今でも下記のようなシステムを用いてカラオケをしているのか？
  - [我こそがインターネットカラオケマン - Speaker Deck](https://speakerdeck.com/joker1007/wo-kosogaintanetutokaraokeman)
  - [闇rubykaigi2011 「カラオケとRailsと私」](https://www.slideshare.net/joker1007/rubykaigi2011-rails)
- カラオケに行く頻度はどのくらいになりましたか？
- 機種のこだわりはあるのか


## おたよりコーナー
- ラジオネーム「馬美肉オブザイヤー」さん「じょーかーさんと言えばやはり黒魔術というイメージですが、黒魔術なコードを書こうと思うタイミングはどういったときの起きるのでしょうか?また最近飲んで美味しかった日本酒などあったら教えてください。」
- ラジオネーム「甚六」さん「うなすけさん、jokerさん、こんばんは。風の噂で「パーフェクトRubyの続編が出る」と耳にしたのですが、実際のところどうなのでしょうか？まだ噂レベルの話である場合は、リクエスト曲「ルビーの指輪」を熱唱してください。」
  - 熱唱しなくていいと思いますけども……
- ラジオネーム「白魔術師」さん「jokerさんは黒魔術師として有名ですが、黒魔術を詠唱していた中で気づいた、「こんな機能がRuby本体にあったらなぁ」というものはありますか？もしなければ好きなゲームを教えてください。」
- ラジオネーム「MasaruTech」(まさるテック)さん「・アプリケーションの全体像を把握しようと思ったときにどういったところを見てますか？（規模にもよると思いますが1週間くらいでざっと把握しようと思った時に）・今関心のあるテクニカルなトピックは何ですか？・一番好きな日本酒の銘柄は何ですか？」
  - 3つあるので1つずつ聞く
- ラジオネーム「coe（しーおーいー）」さん「ジョーカーさんといえば、いつもRubyへの飽くなき探求心を発揮されている印象ですが、その一方ではCTOとしてご活躍されている様子も伺います。ご多忙な中、業務で必要な知識はどんな風にインプットされているのか教えて下さい！」
- 以上5通でした。おたよりを送っていただいたみなさん、ありがとうございました。

## おわりに
- 今回、この番組にゲストで出演してみて、どんな感想を持ちましたか?
- 今後、この番組のゲストで登場してトークしてほしいゲストはどなたですか? 何名でも構わないのですけども。
- 本日は、Repro株式会社のjokerさんを迎えて、黒魔術や働き方の話についていろいろお伺いさせていただきました。番組の感想は Twitter 「#unasukefm」にてツイートしてください。
- 本日はどうもありがとうございました🎉


参考リンク集
- [RubyConf 2018 - Hijacking Ruby Syntax in Ruby by Satoshi "Moris" Tagomori & Tomohiro Hashidate - YouTube](https://www.youtube.com/watch?v=ZPaxvU7dMBU&list=PLE7tQUdRKcyZEjH3kIyvIN0eZ4tuVEkBD&index=21&t=0s)
- https://github.com/joker1007/pasokara_player3
- [【前編】Amazon ECS と Spot インスタンスを使いこなす Repro 株式会社 CTO 橋立さん に、開発体制や Repro ならではのシステム要求、AWS の活用方法をお伺いしました | AWS Startup ブログ](https://aws.amazon.com/jp/blogs/startup/tech-interview-repro/)
- [【後編】「やるべきことをちゃんとやる」- Amazon ECS と Spot インスタンスを使いこなす Repro 株式会社 CTO 橋立さん に、開発体制や Repro ならではのシステム要求、AWS の活用方法をお伺いしました | AWS Startup ブログ](https://aws.amazon.com/jp/blogs/startup/tech-interview-repro-2/)

[^cto]: [\\ CTO オブ・ザ・イヤー2016を勝ち取りました！🏆// | Repro Inc.](https://www.wantedly.com/companies/repro/post_articles/43281)
[^linux1]: [MacBook Proを捨ててThinkpad T460sを買ってgentooを入れた - joker1007’s diary](http://joker1007.hatenablog.com/entry/20161125/1480069437)
[^linux2]: [開発環境がLinuxに戻ってそれなりにこなれてきたので現在の環境について書く - joker1007’s diary](http://joker1007.hatenablog.com/entry/20170202/1486056211)
[^monad]: [RubyKaigi 2019で登壇してきました #rubykaigi - joker1007’s diary](http://joker1007.hatenablog.com/entry/2019/04/22/204441)
