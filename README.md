# robosys2019
+ robosysで作ったデバイスドライバの管理

## 実装内容
+ デバイスファイルに書き込んだ数字(0~9)の回数だけLEDを点滅させる。
+ 数字以外の文字が書き込まれた場合は2回点滅させ、警告する。
+ 警告したのち、デバイスファイルにエラー文を出力する。

## DEMO動画
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/JHrsDwuTSwI/0.jpg)](http://www.youtube.com/watch?v=JHrsDwuTSwI)  
https://www.youtube.com/watch?v=JHrsDwuTSwI

## 追加内容(02/02)
+ デバイスファイルに書き込んだ数字(0~9)の回数だけLEDを点滅させる際に、その数字に応じて明るさを変更するようにした.  
  - 数字が小さいほど暗く、大きいほど明るい  
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/aQDbDEXOyF8/0.jpg)](http://www.youtube.com/watch?v=aQDbDEXOyF8)  
https://youtu.be/aQDbDEXOyF8
