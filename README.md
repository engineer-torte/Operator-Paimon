# Operator-Paimon

NIKKEのユニオン「パイモンは非常食」でオペレーターとして使われる非常食…もといパイモンのプロジェクトです。

- [構築手順](#構築手順)

## 構築手順

1. プロジェクトディレクトリ作成
2. package.jsonの初期化

    ```sh
    npm init -y
    ```

3. TypeScriptと必要な依存関係のインストール

    ```sh
    npm install discord.js node-fetch
    npm install --save-dev eslint typescript @types/node @types/node-fetch
    ```

4. TypeScriptの初期化

    ```sh
    npx tsc --init
    ```

5. TypeScriptの設定（`tsconfig.json`）
   1. `"outDir": "./dist",`
   2. includeとexcludeを追加
6. Discord BOTコードの作成
