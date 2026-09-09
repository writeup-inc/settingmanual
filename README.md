# 初期設定マニュアル

ライトアップの各AI SaaSについて、導入後にお客様ご自身で進めていただく初期設定マニュアルを置くリポジトリ。
商材ごとにフォルダを分け、単一HTMLを配置する。

- 公開URL: https://writeup-inc.github.io/settingmanual/
- 単一HTML。外部依存はGoogle Fontsと説明動画（Vimeo）の埋め込みのみ
- 各ページに `noindex` を入れている。検索結果には出ないが、URLを知っていれば誰でも読める

## 収録

| フォルダ | ページ | 公開URL |
|---|---|---|
| `supermanager/` | スーパーマネージャー 初期設定マニュアル | https://writeup-inc.github.io/settingmanual/supermanager/ |

## 追加のしかた

1. `<商材フォルダ>/index.html` を追加する
2. ルート `index.html` にカードを1件追加し、`data-updated` に最終更新日時（ISO 8601・日本時間）を入れる
3. 並び順と連番はJavaScriptで最終更新の新しい順に整えるが、JavaScript無効時に備えてHTML上の順番も合わせる

## 注意

- 料金・導入期間・個人情報の取り扱いは、マニュアルに書かない
- 商材ページ内のリンク先（Chromeウェブストア、スプレッドシート、Notion、Vimeo）を差し替えるときは、リンク切れがないか公開後に確認する
