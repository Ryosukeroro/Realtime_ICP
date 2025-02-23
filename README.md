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

起動コマンドです。以下のコマンドでノードを起動します。
research はパッケージ名ですので、必要に応じてご自身のパッケージ名に置き換えてください。
```
rosrun research Lidar_node_client4
```
![Screenshot from 2025-02-24 00-32-41](https://github.com/user-attachments/assets/7c0f2753-3732-4223-9609-5437f01882ac)

