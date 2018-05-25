# 日本で Go言語 を利用している会社一覧

(inspired by [日本でErlang/OTPやElixirを利用している会社一覧](https://github.com/voluntas/japanese-erlang-elixir-companies))

- 日本国内版
- プルリクエストください
    - 信頼性を担保するために中の人のみでお願いします
    - 後ろに付け足していってください
    - コミットログは適当で英語でも日本語でも良いです
- カテゴリー分けは後回し
- 求人情報歓迎
- まずは適当に書いて貰えると嬉しいです
- Go言語にはすでに [GoUsers](https://github.com/golang/go/wiki/GoUsers) がありますが、本リポジトリは日本国内での利用実態の集約と、各会社のPRに利用していただけます。

こうした方が良いとかは GitHub Issue へお気軽にご連絡ください。


## テンプレート

```
### [会社名](会社 URL)
- 箇条書きで Go言語 のプロダクション利用について好きなだけ

会社のアピールや求人を好きなだけ
```

## 会社一覧

### [ヤフー株式会社](https://www.yahoo.co.jp) (Yahoo! JAPAN)

- オブジェクトストレージ [Dragon](https://techblog.yahoo.co.jp/architecture/dragon-object-storage-architecture/)
    - Amazon S3互換のWeb APIを実装した独自の大規模分散オブジェクトストレージシステムです。
    - 国内2カ所のデータセンターで稼働しており、合計で200億オブジェクト以上、11ペタバイトを格納しています (2017年10月現在)
    
- サービス間の相互送客用ターゲッティング広告選定プラットフォーム
    - サービス間の相互送客を実現するプラットフォームをGo言語を用いて実装しています。

- 高次元ベクトルデータ検索技術 [NGT](https://techblog.yahoo.co.jp/lab/searchlab/ngt-1.0.0/)
    - NGTをGoから利用できるようにしたGoバインディング [gongt](https://github.com/yahoojapan/gongt)
    - NGTをAPI経由(REST / gRPC)で利用できるようにしたNGTのサーバー実装 [ngtd](https://github.com/yahoojapan/ngtd)

Yahoo! JAPANは、100以上のサービスを提供していて、特にパフォーマンスと安定性が求められる領域において、世界的に実績のあるGo言語を利用し、大量のトラフィックを処理する高速なプラットフォームの構築を行なっています。

#### 採用情報
ヤフー株式会社では、共に働いてくれるGopherを広く募集しています！(エンジニアについてはヤフー株式会社の採用情報からご応募ください)
- https://about.yahoo.co.jp/hr/engineers/


### [株式会社エウレカ](https://eure.jp) (eureka, Inc.)

- [Pairs（ペアーズ）](https://www.pairs.lv/)
    - 国内最大級のマッチングサービスのWeb APIをGo言語で実装しています。
    - マッチングサービスは『人対人』のコミュニケーションサービスという性質上、大規模なトラフィックを迅速に捌く必要があります。

株式会社エウレカでは、Pairsに限らず、Botや内製の開発・デプロイツールについてもGo言語で開発をしており、常にナレッジを蓄積しています。

#### 採用情報

株式会社エウレカでは、大規模トラフィックに挑戦したいGopherを募集しています！
- https://recruit.eure.jp/

### [株式会社Flatt](https://flatt.tv) (Flatt, Inc.)

- [PinQul（ピンクル）](https://pinqul.tv/)
    - 国内最大規模のライブコマースアプリ APIをGo言語で実装しています。
    - ライブという形式であるため遅延をいかに少なくするか、急なトラフィックの増加にどのように対応するかなど難しい課題に対してGo言語を用いて立ち向かっています。

社内のCLIツールなども基本的にGo言語を用いて開発しています。
#### 採用情報

株式会社Flattでは次世代のコマース市場を牽引していくGopherを募集しています！
- https://flatt.tv/recruits


### [AWA株式会社](https://awa.fm) (AWA Co. Ltd.)

- 音楽配信プラットフォーム
    - 日本国内で有数の音楽配信プラットフォームの開発を内製で開発
    - GoとDockerの相性の良さを活かし、開発環境から本番環境までDockerをフル活用
    - マイクロサービスアーキテクチャを採用し、サービス間は REST or gRPC で通信を行う
    - 開発スタイルはTDDでテストカバレッジも75%を超えている
    - 一部APIを企業様・ハッカソンに提供

日々成長する音楽配信市場に携わりながらも、新しい技術を積極的に採用し、過去に構築したシステムが負債とならないよう頻繁に刷新しています。

#### 採用情報

AWA株式会社ではAPI開発からインフラ構築まで幅広く挑戦したいGopherを募集しています！
- https://mf.awa.fm/recruit


### [株式会社Nagisa](https://nagisa-inc.jp/)

- [101 LIVE！](https://itunes.apple.com/us/app/101-live-%E3%83%AF%E3%83%B3%E3%82%AA%E3%83%BC%E3%83%AF%E3%83%B3%E3%83%A9%E3%82%A4%E3%83%96/id1223833186?mt=8)
    - 国内初のペアでの同時配信生放送アプリ「101 LIVE!」のバックエンド側をGo言語で実装しています。 まだまだ始まったばかりのサービスですがペアでの生配信という新しい領域にGo言語を用いて挑戦しています。 

- [マンガZERO](https://manga-zero.coroco3.com/)
    - 国内最大級の無料マンガアプリでPHPからGo言語に乗り換えた経緯があります。
    - こちらのサービスでもGo言語を使って開発・運用してきた経験があり、以下の社内ブログで幾つか知見を紹介しています。
    [golangを使って開発したWebAPIを1年半運用して改善してきたこと-月間20億PVのマンガサービス開発の裏側](https://blog.nagisa-inc.jp/archives/1134)

#### 採用情報
株式会社NagisaではGoを使って新規サービスを開発していきたい方、大規模サービスのトラフィックを迅速に捌いていきたい方など 様々なGopherを募集しています！

- https://recruit.nagisa-inc.jp/
- https://www.wantedly.com/projects/177463


### [GROOVE X 株式会社](http://www.groove-x.com/)

`LOVE x ROBOT = LOVOT` をテーマに、人に寄り添うロボット [LOVOT](http://www.groove-x.com/#lovot) を開発しています。
外側からLOVOTを支えるクラウドのみならず、今まではC/C++の独壇場だった組み込みでもGoの能力を余すことなく活かしています。

今までとは一味違うGoを書きたくありませんか？ぜひ私たちと一緒にLOVOTを作り上げましょう！

- [Wantedly](https://www.wantedly.com/companies/groove-x)
- [Facebook](https://www.facebook.com/GROOVEX.Robot/)

