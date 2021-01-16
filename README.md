# mypkg1  
#ロボットシステム学 課題2
---

## 課題内容 
  
 ロボットシステム学の第10回で作成したコードを改変した。プログラムを実行すると1秒間隔で10倍にした数字を出力する。

## 動作環境

・Ubuntu 20.04  
・Raspberry Pi 4 ModelB  

---

## インストール方法

`$cd ~/catkin_ws/src/`  
`&git clone  
`$cd ..`  
`$catkin_make`  

---

## 実行手順

ディレクトリに移動する。  
`$cd ~/catkin_ws/src/mypkg/scripts/`  

パーミッションの設定  
`$chmod +x count.py`
`$chmod +x fukitu.py`

4つのターミナルに以下のコマンド順番に入力する。  

ターミナル1  
`$roscore`   
ターミナル2  
`$rosrun mypkg count.py`  
ターミナル3  
`$rosrun mypkg fukitu.py`  
ターミナル4  
`$rostopic echo /fukitu`

---

## 動画

　プログラムを実行した様子：https://youtu.be/-sKA5XiUXMU
 
---
