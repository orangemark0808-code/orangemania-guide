# orangemania-guide

OrangeMania の説明書サイトです。Cloudflare Pages でホストし、将来的に `orangemania.net` ドメインで公開する予定です。

## 構成

```
orangemania-guide/
├── index.html              # トップページ
├── guide/
│   └── web/
│       ├── index.html      # WEBアプリガイドトップ（baseアプリ共通入口）
│       └── pomodoro/
│           └── index.html  # Pomodoroタイマー専用ガイド
├── css/
│   └── style.css           # 共通スタイル
└── README.md
```

## デプロイ

Cloudflare Pages と本リポジトリを連携してデプロイします。ビルドコマンドは不要（静的HTML）で、出力ディレクトリはリポジトリルートです。
