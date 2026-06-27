# 性癖の瓶メーカー

GitHub Pagesで公開しやすい形にした一式です。

## 中身

- `index.html`：アプリ本体
- `404.html`：GitHub Pages用の予備ページ
- `.nojekyll`：GitHub Pagesでそのまま配信するための空ファイル
- `manifest.webmanifest`：スマホのホーム画面追加用
- `service-worker.js`：PWAキャッシュ用
- `icons/`：ホーム画面アイコン

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作成
2. このZIPを解凍
3. 中身をすべてリポジトリの一番上、つまりルートにアップロード
4. GitHubのリポジトリで `Settings` を開く
5. 左メニューの `Pages` を開く
6. `Build and deployment` の `Source` を `Deploy from a branch` にする
7. `Branch` を `main`、フォルダを `/ (root)` にする
8. `Save`
9. 数分待つと公開URLが表示される

## LINEで送る場合

公開された `https://ユーザー名.github.io/リポジトリ名/` のURLをLINEで送ってください。
HTMLファイルそのものではなく、URLを送るのが安定します。

## スマホでアプリ風に使う場合

### Android
ChromeでURLを開く → メニュー → ホーム画面に追加

### iPhone
SafariでURLを開く → 共有ボタン → ホーム画面に追加
