# dockerfile-sample-react-with-typescript

## 概要
- React 用の Docker ファイルのサンプルです  
- npm create vite@latest で作成したプロジェクトがベースです  
  - 言語は TypeScript を選択しました  
- 用途  
  - React をちょっと試したいとき  
  - React を勉強したくて、Docker コマンドも使ってみたいとき  
## 利用方法の例
- 2024年3月6日、以下は Mac と WSL で確認しました
- Github からダウンロードしたら、、  
  ```
  # ダウンロードして配置したディレクトリへ
  cd dockerfile-sample-react-with-typescript

  # Docker ビルド
  docker compose build
  
  # 必要なものをインストール
  docker-compose run --rm react_with_ts npm install
  
  # コンテナを起動
  docker compose up

  ※Webブラウザで http://localhost:5173/ にアクセス
  ```
