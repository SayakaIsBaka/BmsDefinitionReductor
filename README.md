# BMS Definition Reductor

BMSファイルの別名の似ている音声の定義を省略する。

# Features

BMSファイルに定義されているwavファイルを比較する。
一致率が指定した数値以上の場合、配置された音の番号を小さいほうに置き換えたBMSファイルを出力する。

※Version 0.1 現在、削除した定義は消していないため、BMSE等を使用して消してください。

# System requirement
- [BMSE](http://ucn.tokonats.net/software/bmse/)

未使用定義の削除、番号を詰めるのに使用。同様の機能があるものであればそれで代用可能。


# Usage

操作デモ動画
:-------------------------:
[![操作デモ](http://img.youtube.com/vi/_MTTS2_fP44/0.jpg)](https://www.youtube.com/watch?v=_MTTS2_fP44)

Sample files(https://drive.google.com/file/d/1ZA9rhmUquSWN_1ZhIbkYSRxegHOm5vLe/view?usp=sharing)


■BMS Definition Reductorでの処理
1. 「BMSファイルの読み込み」ボタンを押し、BMSファイルを読み込む。
1.  読み込んだBMSファイルの置換したい#WAV範囲を入力する。
1.  相関係数を入力する(小さいと全然違う音に置換され、大きいと置換されにくくなる)。
1. 「開始」ボタンを押し、出力するファイル名を入力し、「保存」ボタンを押す。

■BMSEでの処理
1.  出力したBMSファイルをBMSEで開く。
1. 「ファイル」→「変換ウィザードを表示」を押す。
1. 「使用していない#WAV・#BMP・"BGAの定義を消去」と、定義リストの整列」にチェックをつけ、「可能なら古いフォーマット(01 - FF)を使う」のチェックを外す。
1. 「実行」ボタンを押す。

# License

The GNU General Public License v3.0
