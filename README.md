# setup_for_mac

Macのセットアップ方針です

## Tools

- [Clipy](https://clipy.softonic.jp/mac) / クリップボード履歴
- [HyperSwitch](https://bahoom.com/hyperswitch) / `cmd + tab` でウィンドウの切り替えをする


## Homebrew

https://brew.sh/index_ja

### Docker

```bash
$ brew install --cask docker; # Dockerのインストール
$ open /Applications/Docker.app; # Docker for Mac および docker-compose コマンドが入る
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
