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
`&git clone https://github.com/Asahi0801/mypkg1.git
`$cd ..`  
`$catkin_make`  

---

## 実行手順

ディレクトリに移動する。  
`$cd ~/catkin_ws/src/mypkg/scripts/`  

4つの端末に以下のコマンド順番に入力する。  

端末1  
`$roscore`   
端末2  
`$rosrun mypkg count.py`  
端末3  
`$rosrun mypkg tentimes.py`  
端末4  
`$rostopic echo /tentimes`

---

## 動画

　プログラムを実行した様子：https://youtu.be/-sKA5XiUXMU
 
---
