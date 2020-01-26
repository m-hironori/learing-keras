# Kerasの学習コンテンツ

Kerasをつかって、既存モデルは使えるけど、モデルを自分で組み立てるには敷居が高い人向けの学習コンテンツを目指す

内容は[Deep Learning with Python (Manning Publications)](https://www.manning.com/books/deep-learning-with-python?a_aid=keras&a_bid=76564dff)をもとにしています。
日本語版 [PythonとKerasによるディープラーニング](https://book.mynavi.jp/ec/products/detail/id=90124)。

Jupyter NoteBook形式で記述し、Google Colabなどクラウドでの実行もできるようにしていきます。

## 目次(予定)

### ニューラルネットワーク入門(知っている人は飛ばしてもいい)

* モデル作成の基本(MNISTデータで手書き文字認識)
* 2値分類(IMDbレビュー)
  * 2値分類(日本語：[Tweet評価情報ありなし](http://www.cl.ecei.tohoku.ac.jp/resources/twitter_target_review/))
* 多値分類(Reutersニュース)
  * 多値分類([LiveDoorニュース](https://www.rondhuit.com/download.html#ldcc))
* 回帰(Boston Housingデータセットの価格予測)

### 機械学習モデルの評価

* 評価のプロセス(簡単に)
* 過学習への対処 - ネットワークサイズを削減
* 過学習への対処 - 重みの正則化
* 過学習への対処 - ドロップアウト

### 画像処理

### テキスト処理

### 高度使い方

* 多入力多出力
* 重みの共有
* TensorBord

### 生成系

* LSTMによる文生成
* 画風変換
* 変分オートエンコーダー(VAE)
* GAN

