# 機械電子工学コース実験実習　データマイニング，機械学習
## １ ニューラルネットを体験する
### 1.1 グラフィカルに直感する
以下のサイトで直感的にニューラルネットを体感することができる。その下の解説サイトを読んだ後，ニューロンの数，隠れ層の数，学習するデータなどを変更し，学習の様子を（出力や接続線の重みの変化）見てください。
- [A Neural Network Playground](https://playground.tensorflow.org/)

このサイトの解説が以下のサイトにある。ニューロンの入出力の関係，ニューロン間の接続線の重み，ニューラルネットの出力と正解との誤差による重みの学習につて概略を理解してください。
- [TensorFlow Playgroundの仕組み](https://hinaser.github.io/Machine-Learning/index.html)

## 1.2 pythonでニューラルネットを動作する
以下をクリックするとgoogle colaboratoryでpythonの開発環境のJupyterが開く。洋服やシューズのモノクロ写真（10種類7万個）を学習し分類するニューラルネットワークを作成し，テストするプログラムです。#の行はコメントです。最初に画面上部の「ランタイム」をクリックし「すべてのランタイムをリセット」をクリックしてください。その後，コードセルの右上にある[ ]をクリックするとそのセルに書かれたプログラムが実行されます。説明を読みながら実行してください。
- [ファッション画像を分類する](https://colab.research.google.com/github/tokunagahide/asjikken/blob/master/notebooks/Basic_Classification_ja.ipynb)


## ９ ディープラーニングを体験する
### 9.1 畳み込みニューラルネットワークとは
- [畳み込みニューラルネットワークの仕組み](https://postd.cc/how-do-convolutional-neural-networks-work/)
### 9.2 犬と猫を識別する畳み込みニューラルネットワークを作る
- [犬と猫の画像を分類する](https://colab.research.google.com/github/tokunagahide/asjikken/blob/master/notebooks/Lesson_6-1_Dogs_vs_Cats_AS.ipynb)
- [keras.modelsのSequentialモデルの説明](https://keras.io/ja/)
以下は上記ページの目次より辿れる
- [model.compile model.fitのパラメータ]（https://keras.io/ja/models/sequential/)
model.addで追加するレイヤについて
- [Conv2D MaxPooling2Dのパラメータ]（https://keras.io/ja/layers/convolutional/)(https://keras.io/ja/layers/pooling/)
- [Flatten Dense Dropoutのパラメータ]（https://keras.io/ja/layers/core/)
