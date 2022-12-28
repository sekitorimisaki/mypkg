# mypkg
* ロボットシステム学用の練習用リポジトリ
* ROS2のパッケージ

# ダウンロード方法          
'''
git clone https://github.com/sekitorimisaki/mypkg.git
colcon build
'''
## 実行方法
'''
timeout 10 ros2 launch mypkg talk_listen.launch.py
'''
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