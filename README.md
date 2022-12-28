[![test](https://github.com/sekitorimisaki/mypkg/actions/workflows/test.yml/badge.svg)](https://github.com/sekitorimisaki/mypkg/actions/workflows/test.yml)
# mypkg
* ロボットシステム学用の練習用リポジトリ
* ROS2のパッケージ
# 概要
* talkerというノードが時間経過とともに0から1ずつ数字を増やした16ビット符号付整数の型のメッセージをトピック(/countup)を通じて送信しlistenerというノードがそのメッセージを受け取り表示する
# インストール，ビルド          
```
git clone https://github.com/sekitorimisaki/mypkg.git
colcon build
```
## 実行方法
```
timeout 10 ros2 launch mypkg talk_listen.launch.py
```
timeout の後の数字は秒数なので数字を変えれば実行される時間が変わります 
## 必要なソフトウェア
* ROS2
## テスト環境
* Ubuntu 22.04 LTS
                       
## 備考                                               
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
	* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

* © 2022 Misaki Sekitori
