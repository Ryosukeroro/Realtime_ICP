# リアルタイムICPアルゴリズムの実行
研究用ICPアルゴリズムのリアルタイム実験コードです。
# 使い方
ROSで実行可能です。
パッケージ名はLiDAR_client_node4です。

まずは、地図（map）の役割を果たすデータ群として`scan.txt`を用意してください。

LiDARデバイスを接続し、起動しておいてください。
私はLD-06を使用しています。

あくまでも、サンプルです。GNU-PLOTで位置推定の様子は見れますが、ROSのRviZには対応していません。
ICPアルゴリズムの位置推定の様子をつかむためのコードとなっています。
