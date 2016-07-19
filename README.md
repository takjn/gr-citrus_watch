# GR-CITRUS mruby demo
デジタル時計とカレンダー機能があります。

AdafruitのGFXライブラリを取り込んだ独自のmrubyファームを使っています。

## 必要なもの
- GR-CITRUS
- SSD1306 (I2C接続のOLED)
- ブレッドボード & ジャンプワイヤ
- ボタンスイッチ3個

## 配線図
あとで書く

## 実行方法
1. githubからzipファイルをダウンロード
2. ダウンロードしたzipファイルを解凍
3. GR-CITRUSをUSBケーブルでPCにつなぐ
4. GR-CITRUSのリセットボタンを押して書き込みモードにする
5. citrus_skech.binをGR-CITRUSにコピーする
6. Rubicを立ち上げる
7. Rubicのopenで、gr-citrus_watchフォルダを開く
8. main.rb(mrubyのプログラム)が表示されるはず
9. RubicのRunボタンを押して実行する
