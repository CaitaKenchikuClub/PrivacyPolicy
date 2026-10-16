# PrivacyPolicy

けんちくぶ！が開発するゲームのプライバシーポリシーをまとめるリポジトリです。
GitHub Pages で公開し、各ゲームのアプリ内リンク・Google Play・AdMob の同意メッセージからこのページを使います。

## 公開中のポリシー

| ゲーム | フォルダ | 公開 URL |
|---|---|---|
| ブロッ校長！（Android） | [`burokocho/`](burokocho/) | https://caitakenchikuclub.github.io/PrivacyPolicy/burokocho/ |

## フォルダ構成

```
.nojekyll                       GitHub Pages の Jekyll 処理を止めるための空ファイル
burokocho/                      ブロッ校長！
  index.html                    プライバシーポリシー本体（日本語・英語）
  assets/fonts/                 ページで使うフォント（SIL OFL 1.1。各フォルダの OFL.txt は削除・変更しない）
  assets/icons/favicon-32.png   ブラウザのタブのアイコン
```

## 新しいゲームを追加するとき

1. ゲーム用のフォルダ（英数字の小文字。例：`newgame/`）を作り、`index.html` を置く。
2. フォルダの中のファイルは**相対パス**で参照する（ほかのゲームのフォルダに依存しない）。
3. 上の表に行を追加する。

## 書き換えるときの注意

- 公開 URL（フォルダ名）は、アプリ・Google Play・AdMob に登録しているので**変えない**。
- 内容を変えたら、ページ内の日付（制定日／改定日）も更新する。
- 外部の CDN（Google Fonts など）からフォントを読み込まない。

## フォントのライセンス

`burokocho/assets/fonts/` のフォントは、ゲーム「ブロッ校長！」と同じもの（Google Fonts 公式リポジトリ https://github.com/google/fonts の TTF を WOFF2 に形式変換しただけ）です。

| フォント | 著作権表示 | ライセンス |
|---|---|---|
| Dela Gothic One | Copyright 2020 The Dela Gothic Project Authors (https://github.com/syakuzen/DelaGothic) | SIL Open Font License 1.1（`DelaGothicOne/OFL.txt`） |
| M PLUS Rounded 1c | Copyright 2016 The Rounded M+ Project Authors. | SIL Open Font License 1.1（`MPLUSRounded1c/OFL.txt`） |
