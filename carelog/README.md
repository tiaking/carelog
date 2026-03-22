# ケアログ — Android PWA

## ファイル構成
```
carelog/
├── index.html       ← メインアプリ
├── manifest.json    ← PWA設定
├── sw.js            ← Service Worker（オフライン対応）
└── icons/
    ├── icon-192.png ← アプリアイコン（要作成）
    └── icon-512.png ← アプリアイコン（要作成）
```

## アイコンの作成
以下のサイズのPNGアイコンが必要です：
- 192×192px → icons/icon-192.png
- 512×512px → icons/icon-512.png

[Canva](https://www.canva.com) や [favicon.io](https://favicon.io) で無料作成できます。

## デプロイ手順（GitHub Pages）

1. GitHubでリポジトリを作成（例: `carelog`）
2. このフォルダの全ファイルをアップロード
3. Settings → Pages → Source を「main ブランチ」に設定
4. `https://ユーザー名.github.io/carelog/` でアクセス可能になります

## Google Play への公開（PWABuilder）

1. https://www.pwabuilder.com にアクセス
2. GitHub PagesのURLを入力
3. 「Android」を選択 → パッケージをダウンロード
4. Google Play Consoleにアップロード

## 必要な費用
- GitHub Pages: **無料**
- PWABuilder: **無料**
- Google Play Developer 登録: **$25（一回払い）**
