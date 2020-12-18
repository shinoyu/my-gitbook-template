# Readme

## 事前準備

```
# for MacOS
brew install graphviz
brew cask install Calibre
brew cask install java
npm install

# プラグインを追加したとき or 初回
gitbook install
```

### 注意

gitbookは長年メンテナンスされてないらしく、インストール時に脆弱性がいっぱい出てくる。
ローカルでマニュアル更新するためだけなので許容している

## 使い方

### プレビュー

```
npm run serve
```

### PDFとして出力

```
npm run build
```

## draw.ioの図について

https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio
を用いる。ドキュメントに反映する場合は、pngとしてエクスポートしたものにリンクを貼る。