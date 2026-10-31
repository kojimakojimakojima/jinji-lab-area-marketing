# 人事ラボ｜エリアマーケティングLP

人事ラボのエリアマーケティングサービス紹介LP。白基調、黄色のブランドアクセント、赤いCTA。

## ファイル
- `index.html` — GitHub Pages等でそのまま表示できる単一HTML。**社内確認・デザインレビュー用**。フォーム送信機能なし。
- `bluemonkey-bownow/` — BlueMonkeyのCMS組み込み用HTML/CSS、BowNowフォームの埋め込み用プレースホルダー、説明書。

## GitHub Pagesでプレビューする場合
1. `jinji-lab-area-marketing` というリポジトリを作る（公開範囲に注意）。
2. このフォルダの内容をリポジトリのルートに入れてコミットする。
3. GitHubの **Settings → Pages → Build and deployment** で `Deploy from a branch`、`main`、`/(root)` を選ぶ。
4. GitHub Pagesが表示するURLで確認する。

注意：GitHub Pagesの公開URLは認証付き社内限定URLではありません。
ページ内には `noindex,nofollow` を設定していますが、非公開を保証するものではありません。

## 本番のフォーム連携について
現行LPにはBowNowの実際の「サイト反映コード」はまだ組み込まれていません。
公開用のBowNowコード、個人情報保護・同意事項、送信後遷移などを設定し、
実ドメインでテストしてから公開してください。
`bluemonkey-bownow/README_導入手順.md` に実装手順を記載しています。

APIキーや管理用ID、個人情報が入った設定ファイルを公開リポジトリに追加しないでください。

## 制作に関する注意
商品価格はすべて税抜表示。料金条件は公開前に最終確認してください。