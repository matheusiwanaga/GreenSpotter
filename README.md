# [GreenSpotter（グリーンスポッター）]

## サービス概要

GreenSpotter（グリーンスポッター）は、自然の中でエンターテイメント
を検索するためのウェブサービスです。そのエンターテイメントとは：夏での川遊びスポット、自然の近くでデイキャンプできる場所、デートに良い自然ウォーキングできる所、自然での綺麗な写真が撮れる所、自然の中で色々な楽しみ方ができるスポットを共有出来るサービス。

##　想定されるユーザー層

このサービスは、自然が好きで自然で遊べる所を探したり、共有したりしたいユーザーが目的です。


## サービスの差別化ポイント・推しポイント

GreenSpotterの特徴は、あまり知られていない、地元の人だけが知るような特別な場所を共有して、一般的な旅行ガイドには載っていないユニークで隠れた自然の宝物を発見し、体験できること。多くのサイトでは、有料の自然観光スポットが紹介されていますが、日本には無料で楽しめる美しくユニークな場所がたくさんあります。

もう一点は、多くのサイトでは、視覚的に情報過多でデザインが貧弱な傾向がありますが、GreenSpotterは目的に焦点を当てたクリアでモダンなデザインを採用しています。私たちの目標は、ユーザーが自然の中で遊び、訪れる場所を簡単に見つけることができるようにすることであり、そのために必要な情報のみを提供します。

クリアでモダンなデザインとは：

1.クリアで直感的なレイアウト： サイトはシンプルで直感的なレイアウトを採用し、ユーザーが新しい場所を発見しやすいようにします。情報は論理的に整理され、発見を容易にすることに重点を置いています。
2. 読みやすくエレガントなタイポグラフィ： 読みやすさと同時にモダンでエレガントなタイポグラフィーを使用します。テキストが視覚的なコンテンツから気を逸らさず、アクセスしやすく楽しめるようにすることが目的です。
3. 高品質の画像： 自然の場所の高品質の画像をページの主要なフォーカスとして使用します。これらの画像はユーザーにさらなる探索へのインスピレーションを与えます。
4. ミニマリストなインタラクティブ要素： ボタンやアイコンなどのインタラクティブ要素はミニマリストなデザインを採用し、インターフェースを過剰にしないようにします。直感的なインタラクションにより、ユーザーエクスペリエンスをスムーズで楽しいものにします。
簡単でアクセスしやすいナビゲーション： ナビゲーションバーはシンプルで理解しやすいものにし、カテゴリーを明確に定義して、ユーザーがすぐに必要なものを見つけられるようにします。
5. レスポンシブデザイン： サイトは完全にレスポンシブで、モバイルデバイスとデスクトップの両方で素晴らしい体験を提供します。



## Why You?

私は自然が大好きです。いつも新しい場所を訪れるために車で探検をしています。私がソーシャルメディアに写真を投稿すると、人々はいつも「それはどこですか？」「とても綺麗ですね！私も行きたい！」と聞いてきます。それが私に、人々が自然の中の場所を共有し、そこがどのような場所で、どうやって行くのかを記述する場所があればいいという思いを抱かせました。自然の中でのお気に入りの場所や、あまり人が訪れない秘密の場所を共有する場所が欲しいと思いました。

## 実装を予定している機能
### MVP
* 会員登録　（ユーザー登録）
* ログイン
* スポット登録
    ー　スポットに付いての記述　（自分の経験や、そこにたどり着くまでの説明）
    ー　その場所の写真アップロード　（画像加工・合成）
    ー　GoogleMapでその所をピンポイント　（ユーザーがピンポイントを自分のマップに保存して、いつでも行けるようにする）
* 全スポット一覧　（登録している前スポット一覧）
* カスタマイズ検索フィルター　（　例えば：　'川遊び'　と検索すると、その内容と関係するスポットのみを表示する。）
* インタラクティブマップ　（　サイトに登録してある全スポットをマップで表示する　）
* 新規スポットのアラートをLINE通知

### その後の機能
* 評価とコメント
* ローカルガイドとのパートナーシップ

## 使用する技術

バックエンド
 Ruby on Rails
フロントエンド
	* HTML、CSS、およびJavaScript : サイトの基本的な構造とインタラクティビティのために、HTML、CSS、およびJavaScriptを使用します。
	* Vue.js : Vue.jsを使用することを検討しています。
	* Bootstrap : レスポンシブデザインとスタイリングのために　Bootstrapを使用する予定です。
データベース
	PostgreSQL
追加ツール
	GitとGithub : コードのバージョン管理とコラボレーションのために、GitとGitHubを使用します。
	Heroku: アプリケーションのホスティングとデプロイメント
	Figma: インターフェースのデザインとプロトタイピング
テストとメンテナンス
	RSpec (Rails用)

## 画面遷移図リンク：　https://www.figma.com/file/UtBdnhtsx9uMhcIHFNBdSq/GreenSpotted?type=design&node-id=0%3A1&mode=design&t=XLE7mK5qjN3T0gGJ-1

##　ER図
https://app.diagrams.net/#Hmatheusiwanaga%2FGreenSpotter%2FDevelop%2FGreenSpotterER%E5%9B%B3.drawio.png