# dotfiles

## インストール

1. git clone
2. Makefileがあるフォルダまで移動
3. `make all` で全て実行

Makefile から実行できる内容は以下の通り

- `make init`
  - Xcode, homebrew のインストール
- `make link`
  - 各種シンボリックリンクの作成
  - .bin以下の.始まりのファイルの `$HOME` へのシンボリックリンク作成
- `make brew`
  - homebrewでインストールするものを一括でインストール
  - インストールされるアプリ群(cask)は、hyper, karabiner-elements, mos, rectangle, vscode, warp

## 手動でやること

- [UDEV Gothic](https://github.com/yuru7/udev-gothic)のインストール
  - VSCode や Hyper (使用中のターミナル) で使用しているフォント

## 参考

- https://zenn.dev/tsukuboshi/articles/6e82aef942d9af