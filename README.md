クラウドアーキテクト・ファーストステップ
==

- クラウドアーキテクト・ファーストステップの資材を管理します。当面はテキストの管理のみになると思います
- テキストは vuepress でビルドして github pages で公開します。

## 開発、デバッグ時
```
yarn src:dev
```

## ビルド
```
yarn src:build
```

- text/docs/に成果物ができる
- github pages では当面、textブランチのdocsフォルダを公開フォルダにします

## notice
- node.jsのバージョンとvuepressのがあってない？ので以下を投入してからyarnすると良いかと

```
export NODE_OPTIONS=--openssl-legacy-provider
```