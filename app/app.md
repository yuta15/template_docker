# APPコンテナについて
Fast APIの稼働する環境


## ディレクトリ構成
```
.
├── app.md              # 本ファイル
├── .env                # 環境変数ファイル
├── dockerfile          # Dockerfile
└── requirements.txt    # python依存関係
```
---

# 環境変数
`.env`ファイルをAPPディレクトリ内に作成し、以下の環境変数を記述してください。


※DB関連のパラメータはDBコンテナにて設定している環境変数の値と合わせて設定してください。