# Embrace Japan Website

Embrace Japan の日本語教育サービス用ランディングページです。

## 内容

- ブランド名: Embrace Japan
- サービス: 日本語教育のみ
- 言語: インドネシア語 / 英語 / 日本語
- 予約導線: Google Calendar → Google Meet
- 予約URL: https://calendar.app.google/xk9TVfJy4Mg6ZjyZ7

## ファイル構成

```text
embrace_japan_site/
├── index.html
└── assets/
    └── embrace-japan-logo.png
```

## 公開方法のおすすめ

### 一番簡単: Netlify Drop

1. https://app.netlify.com/drop を開く
2. `embrace_japan_site` フォルダをドラッグ&ドロップ
3. 発行されたURLを確認
4. 必要なら独自ドメインを接続

### Cloudflare Pages

1. Cloudflare Pagesで新規プロジェクト作成
2. `index.html` と `assets/` をアップロード、またはGitHub連携
3. Build command は不要
4. Output directory はルート
5. 独自ドメインを接続

## 公開前に決めるとよい項目

- 正式な講師名・プロフィール写真
- 料金
- 支払い方法
- キャンセルポリシー
- 連絡先メールアドレス
- 利用規約 / プライバシーポリシー

## ローカル確認

```bash
cd ~/embrace_japan_site
python3 -m http.server 8000
```

ブラウザで開く:

```text
http://localhost:8000/
```
