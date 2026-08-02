# Healsalon toku LP — GitHub Pages公開用

このZIPには、GitHub Pagesで公開するために必要なファイルがすべて入っています。

## ZIPの内容

- `index.html`：LP本体
- `assets/`：CSS・JavaScript
- `images/`：LPで使用する画像
- `hero-linen.png`：ファーストビュー画像
- `favicon.svg`：ブラウザのアイコン
- `.nojekyll`：GitHub Pages用設定
- `README.md`：この説明書

## GitHubへアップロードする手順

1. ZIPを端末へ保存し、解凍します。
2. GitHubで作成済みのリポジトリを開きます。
3. 現在の`README.md`だけがある画面で、`Add file` → `Upload files`を選びます。
4. **ZIPそのものではなく、解凍したフォルダの中身をすべて**アップロードします。
5. 画面下の`Commit changes`を押します。

アップロード後、リポジトリの一番上に`index.html`が見えていれば正しく配置できています。

## GitHub Pagesを有効にする手順

1. リポジトリ上部の`Settings`を開きます。
2. 左側の`Pages`を開きます。
3. `Build and deployment`の`Source`で`Deploy from a branch`を選びます。
4. `Branch`を`main`、フォルダを`/(root)`に設定します。
5. `Save`を押します。

数分待つと、同じ画面に公開URLが表示されます。

## ご注意

- ファイル名やフォルダ構成は変更せず、そのままアップロードしてください。
- 画像や`assets`フォルダも必ず一緒にアップロードしてください。
- LP内の予約ボタンはHealsalon toku公式LINEへつながります。
