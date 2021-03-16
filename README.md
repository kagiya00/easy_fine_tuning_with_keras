# easy_fine_tuning_with_keras

画像分類を行う機械学習モデルのサンプルコードです。

* VGG16, ResNet50, Xceptionなど、Kerasに含まれる代表的な学習済みモデルをベースに、ファインチューニングを行っています。
* Google Colaboratory上で実行可能です。
* 学習データは、[Intel Image Classification](https://www.kaggle.com/puneet6060/intel-image-classification)を用いています。

Google Colaboratory上での実行方法の概要：

* Googleドライブのフォルダ(ex. 'Colab Notebooks/easy_fine_tuning_with_keras/')に CNN_fine_tuning_for_intel_image_classification.ipynb をアップしてください。
* CNN_fine_tuning_for_intel_image_classification.ipynb をGoogle Colaboratoryで開いてください。
* 後は、CNN_fine_tuning_for_intel_image_classification.ipynb の内容に沿って、上のセルから順に実行してください。

このコードの解説および評価結果を、[Kerasでできる簡易Fine-Tuningのすすめ](https://qiita.com/kagiya00/items/311864936f8661b20cb9)」 にまとめています。

このコードの作成にあたり、[Keras学習済みモデルをFine-tuningさせて精度比較](https://qiita.com/ha9kberry/items/daa2fc330c71485b2c27) を参考にさせていただきました。


