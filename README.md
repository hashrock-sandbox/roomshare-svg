# roomshare-svg

> my fantastic project

# 構成

- チップエディタ
- マップ表示・エディタ
- 文字 / UI

上記をすべて別SVG要素で実装する。
すべての画像データのやり取りはbase64で行う。

# サーバサイド

- socket.ioサーバを一つ立てる
- 更新のたびに差分をbase64データを送る
- 全chipを送るコマンドを作っておく

## License

MIT