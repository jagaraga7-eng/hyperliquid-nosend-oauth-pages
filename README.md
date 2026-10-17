# Hyperliquid NOSEND Backup — public information

本人の監査ログを本人の Google Drive に私的にバックアップするための OAuth アプリについて、用途説明とプライバシーポリシーを公開するリポジトリです。利用対象は運営者本人だけです。

- `index.html`：アプリの説明
- `privacy.html`：プライバシーポリシー、権限解除・手動削除・問い合わせ
- `styles.css`：ローカルの表示用スタイル
- `.nojekyll`：静的ファイルを配信するためのマーカー

## 公開先（GitHub Pages 有効化後）

- ホーム：https://jagaraga7-eng.github.io/hyperliquid-nosend-oauth-pages/
- プライバシー：https://jagaraga7-eng.github.io/hyperliquid-nosend-oauth-pages/privacy.html

Pages の設定は Settings → Pages → Deploy from a branch → main → /(root) → Save。
上の URL は有効化とデプロイの成功後に利用できます。

## 状態と管理方針

このリポジトリは説明用の静的ページだけです。OAuth ログイン、コールバック、バックアップ実行、取引・注文処理は含みません。バックアップの稼働状態、実際の要求スコープ、自動保存期間は未確認としてページ内に明記しています。未確認事項が確認できたら、実態に合わせて説明を更新してください。

OAuth クライアント ID・Secret、トークン、API キー、認証ファイル、監査ログ、取引履歴、残高、バックアップ実データは、このリポジトリに追加しないでください。Issues は公開窓口のため機密情報を投稿しないでください。

既存の trading_bot、VPS、Healthchecks、自動注文とは別の、公開説明専用リポジトリです。本リポジトリの追加・公開でそれらを変更しません。

Google による OAuth アプリの確認・審査の承認を保証するものではありません。

