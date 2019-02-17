# box_failure_detection

本プログラムを作成するにあたり、開発環境はgoogle colaboratoryを使用しました

Google colaboratoryでは画像ファイルを圧縮せずに扱うには、おそらくメモリ不足等で動かなかったため、
189×252サイズに圧縮し解析を実施しました

画像ファイルを189×252サイズで読み込み後、numpyのテンソル形式で保存し、それを再び読み込む設計に
なっています。OK_list_16,NG_list_16がnumpyのテンソルになります

# プログラムの説明
submittion.ipynbがノート形式のプログラムになります。プログラムの説明もsubmittion.ipynbに
記入しています。

注意点としては、データをGoogle Driveから読み込んでいるため、読み込み先を変える必要があります。添付のOK、NGをダウンロード頂き、
解凍後、本プログラム-3.学習データ・テストデータの分割において、ファイルの読み込み先を変更ください。

ご不明点あれば教えてください
