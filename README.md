# PLUG_resource4matlab
PLUGを用いた事後解析のための関数集。
- 0_sourcesが基本的な中身です。
- 1_testDataにロガーから入手できるデータのサンプルを格納しています。
- 2_exmplesに実用例を載せています。
## 機能
- インポートと整形
- ノイズ時区間の確認(生波形の描出)
- 周波数フィルタリング
- エポッキング(data.eeg.epoched,data.imp.epochedなどに格納されます)
- 短時間FFT
- 可視化関数
## Getting Started
### 開発環境_MATLABのバージョン
- 2022aで開発
- 2021b以降にて動作を確認しています
### 開発環境_modules
- [signal processing toolbox](https://jp.mathworks.com/products/signal.html)
- その他必要モジュールが見つかり次第追記します。ご一報ください。
### 対応するloggerのバージョン
- V1.0.3
### 想定する利用方法
- 用途に合わせてPlug_Analysisを書き換えるor継承して関数を追加することを想定しています。
- 1セッション(すなわち1計測データ)に紐づく解析を1インスタンスとして建てられるイメージです。

## 関連リンク
- [PLUG_logger配布先](https://drive.google.com/drive/folders/1Ubncn51XVxTQvzBBvWvCVQYMFGrulUmm)
- python版解析リソース(整備中)

## 残課題
- [ ] 別モダリティデータとのデータアライメント例の整備
- [x] リンク繋げる
- [ ] python版の整備
- [ ] EEGLABなどとの繋ぎ込み
