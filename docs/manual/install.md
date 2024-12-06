# プラグイン利用前の準備

1. プラグインのダウンロードと起動について
2. CityGMLファイルの準備

## 1. プラグインのダウンロードと起動について

プラグインは以下のURLからダウンロードが可能です。

[https://github.com/bassdrum-org/PLATEAU-TouchDesigner-Plugin/archive/refs/heads/main.zip](https://github.com/bassdrum-org/PLATEAU-TouchDesigner-Plugin/archive/refs/heads/main.zip)

ダウンロードファイルはZIPファイルとして保存されるので、ダウンロード完了後にファイルを解凍します。
すると以下のようなファイルが保存されるので、プラグインを利用する場合はこの中にある「PLATEAU-TouchDesigner-Plugin.toe」をダブルクリックで開きます。

## 2. CityGMLファイルの準備

プラグインを利用するにはPLATEAUで配布しているCityGMLデータが必要です。CityGMLデータは以下のサイトからダウンロードが可能です。

[https://www.geospatial.jp/ckan/dataset/plateau](https://www.geospatial.jp/ckan/dataset/plateau)

なお、解凍後のフォルダ構成は変更しないようにしてください。変更すると属性が適切に読み込めないことがあります。
例として渋谷区のデータの場合「13113_shibuya-ku_city_2023_citygml_1_op.zip」というファイルがダウンロードされますが、こちらを解凍し指定の場所にフォルダを移動するのは問題ないですが、中身のファイル構造を変えてしまうと正しくデータが読み込めなくなってしまいます。