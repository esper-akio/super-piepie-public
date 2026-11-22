# ぴえぴえ市場 横浜本店 ネット販売部 — 事業紹介サイト

Amazon Solution Provider Portalのウェブサイト欄に登録するための、静的な事業紹介サイトです。

## 含まれるファイル
- `index.html`: 事業紹介と自社向けSP-API利用予定の説明
- `privacy.html`: プライバシーポリシーの草案

## 公開前に必ず対応すること
1. `index.html` と `privacy.html` の `【公開前に連絡用メールアドレスへ差し替え】` を、実際に連絡可能なメールアドレスに差し替えてください。
2. 「ぴえぴえ市場 横浜本店 ネット販売部」が、Amazonに申請する正式な事業者名・屋号と一致するか確認してください。
3. 事業内容・所在地区分（神奈川県横浜市）・データ取り扱い方針が、実際の運用と一致するか確認してください。
4. `privacy.html` は実態に合わせた草案です。SP-API本番運用時のデータ処理、外部委託・保持期間・セキュリティ運用などと整合させてください。
5. ページ内の記載だけでSP-API審査やAmazonのセキュリティ要件への適合が保証されるわけではありません。

## GitHub Pages 公開方法
1. GitHubで公開用の **Public** リポジトリを新規作成します。例: `piepie-market-site`。
2. このZIP内の `index.html`、`privacy.html` をリポジトリ直下にアップロードします（README.mdは任意）。
3. GitHubの `Settings` → `Pages` → `Build and deployment` → `Source: Deploy from a branch` を選択します。
4. Branchを `main`、フォルダを `/ (root)` に指定して `Save`。
5. GitHubが表示する公開URL（例: `https://USERNAME.github.io/piepie-market-site/`）へアクセスし、事業紹介・プライバシーポリシー・連絡先リンク等が動作することを確認します。
6. 公開された正確なURLをAmazonの「ウェブサイト」欄へ入力します。

**注意**: このリポジトリは公開されます。Keepa APIキー、SP-APIクライアントシークレット、販売データ、個人情報、プライベートアプリのコードや設定ファイルは絶対に置かないでください。販売管理ツール本体は別のPrivateリポジトリで管理します。
