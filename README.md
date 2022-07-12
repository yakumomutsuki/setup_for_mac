# Setup for Mac

Macのセットアップ方針です

## Browser

- Firefox (default)
- Google Chrome
- Safari

※ Firefox は WebGL まわりで google meet の背景ぼかしが使えないため、Chrome を使用すること

## Tools

便利ツール系

- [Clipy](https://clipy.softonic.jp/mac) / クリップボード履歴
- [HyperSwitch](https://bahoom.com/hyperswitch) / `cmd + tab` でウィンドウの切り替えをする

開発ツール系

- [Homebrew](https://brew.sh/index_ja)
- Docker
- [Volta](https://volta.sh/) (JavaScript Tool Manager)

### Docker

```bash
$ brew install --cask docker; # Dockerのインストール
$ open /Applications/Docker.app; # Docker for Mac および docker-compose コマンドが入る
```

### Volta

公式を引用、Homebrew経由で入れるとちょい厄介なので必ず以下の手順から😥

```bash
# install Volta
curl https://get.volta.sh | bash

# install Node
volta install node

# start using Node
node
```

## Fonts

- https://github.com/miiton/Cica/releases より最新版の package を取得する
- package を展開して作成された該当のフォルダを `~/ライブラリ/Fonts/` に移動させる

## Terminal

### テーマ変更

- [bashからZshに乗り換え - preztoを使ってプロンプトテーマを変えてみた](https://qiita.com/gilly/items/5ff7bd7142e963cdbb9b) を実行する
- thema の変更はせず、`sorin` を使用します

### Git の補完機能追加

- https://zenn.dev/aruneko/articles/26815f95ea2124

### Fonts 変更

- `Cica(シカ)` をデフォルトに設定


<img src="./terminal.jpg" />
