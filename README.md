# 祈詠よりこ ホームページ一式

HTML・CSS・JavaScript・画像を含む、公開用の静的サイトです。TOPには差し替え用の横長画像を含めています。編集は `index.html`、`works/index.html`、`profile/index.html`、`styles.css` で行えます。画像は `assets/` にあります。元のChatGPT Sitesで公開中のページは、このファイルを編集しても自動では変わりません。

## 自分のサーバーで公開

ZIPを展開し、このフォルダ内の `index.html`、`styles.css`、`site.js`、`works/`、`profile/`、`assets/` を、公開先の同じフォルダへアップロードします。サーバー上で `index.html` が開くURLから確認してください。既存ファイルを上書きする前にはバックアップを取ってください。

## GitHub Pagesで公開

新しいリポジトリを使う場合、このフォルダ**内のファイルとフォルダ**をリポジトリのルートへ置きます。GitHubのリポジトリで Settings → Pages → Build and deployment → Deploy from a branch を選び、対象ブランチの `/ (root)` を指定します。`https://ユーザー名.github.io/リポジトリ名/` の形式で公開されます。画像やHTMLもリポジトリから見えるので、公開してよい内容か確認してください。

## 確認する場所

HOME、作品、プロフィールの各ページ、メニュー、画像、外部リンク、スマホ幅の表示を確認してください。Google Fontsを読み込むため、ネット接続がない状態では代替フォントになります。
