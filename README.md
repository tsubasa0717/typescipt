# 開発者向け情報

## 1. 開発環境
動作確認が出来ているアプリケーションと対応バージョンは以下です。

| アプリケーション名 | バージョン | インストール条件 |
| ------- | ------- | ------- |
|[Node.js](https://nodejs.org/ja/)|10.19.0 , 12.16.3|備考|
|[Visual Studio Code](https://code.visualstudio.com/)|1.45.0|Visual Studio Codeを利用する場合|
|[yarn](https://classic.yarnpkg.com/ja/)|1.22.4|本プログラム
|[Git](https://git-scm.com/)|2.26.2|sourcetreeなどを使用する際、使用するGitのバージョンに注意|

### 1-1. Visual Studio Codeの拡張機能

Visual Studio Codeを利用する場合は、以下の拡張機能をインストールします。

| 拡張機能 | インストール条件 |
| ------- | ------- |
|[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)|任意|
---

## 2. 実行

コマンドの実行は、WorkingCopyのルートディレクトリでおこないます。

### 2-1. `yarn` を使う場合

#### 2-1-1. 依存関係を構築する

```bash
# install dependencies
$ yarn install
```
