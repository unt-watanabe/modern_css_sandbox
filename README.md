# Modern CSS Sandbox

このリポジトリは、最新の CSS 技術を学び、実験するためのサンドボックスプロジェクトです。主に`@container`や`subgrid`などのモダンな CSS 機能を活用したレイアウトやスタイリングの実装を目的としています。

## ディレクトリ構成

```
modern_css/
├── package.json
└── src/
    ├── index.html         # サンプルページ
    └── scss/              # SCSSファイル群
        ├── _base.scss     # ベーススタイル（リセットや基本的な要素のスタイル）
        ├── _block.scss    # ブロック単位のスタイル
        ├── _config.scss   # SCSSの設定ファイル（変数やミックスインなど）
        ├── _layout.scss   # レイアウト関連のスタイル
        ├── _reset.scss    # CSSリセット
        ├── _unique.scss   # ページ固有のスタイル
        ├── _utilities.scss # ユーティリティクラス
        └── style.scss     # メインのスタイルシート
```

## 必要要件

- Node.js (推奨バージョン: 16.x 以上)
- npm または yarn

## セットアップ

1. リポジトリをクローンします。

   ```bash
   git clone <リポジトリのURL>
   cd modern_css
   ```

2. 必要なパッケージをインストールします。

   ```bash
   npm install
   # または
   yarn install
   ```

## 開発方法

1. SCSS ファイルを編集します。
2. 開発サーバーを起動して変更をリアルタイムで確認します。

   ```bash
   npx parcel src/index.html
   ```

3. ビルドを実行して最適化されたファイルを生成します。

   ```bash
   npx parcel build src/index.html
   ```

## 主な機能

- **Container Queries**: `@container`を使用したレスポンシブデザイン。
- **Subgrid**: CSS Grid の`subgrid`機能を活用したレイアウト。
- **モジュール化された SCSS**: 各ファイルが役割ごとに分割されています。

## ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。
