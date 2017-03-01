# npm-gui-tool
npm-gui-tool

package.json を gui で扱えるようにするツール.

初期フェーズは readonly

## usage

1. ファイル読み込みもしくは ドラッグ&ドロップ で package.json を読み込む
2. 左側にプロジェクトとして追加される
3. package.json 内の `npm scripts` をボタン化
4. name や description も表示しておく
5. github へのリンクも

## memo

- finder で開くボタンを作る (`$ open <path/to/file>`)
