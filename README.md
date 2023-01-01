[![test](https://github.com/sekitorimisaki/mypkg/actions/workflows/test.yml/badge.svg)](https://github.com/sekitorimisaki/mypkg/actions/workflows/test.yml)
# mypkg
* ロボットシステム学用の練習用リポジトリ
* ROS2のパッケージ
# トピック(/countup)
* talkerという数字をカウントするノードから16ビット符号付整数のメッセージをlistenerという貰ったメッセージを表示させるノードに送信する
# インストール，ビルド          
```
git clone https://github.com/sekitorimisaki/mypkg.git
colcon build
```
## 実行方法と結果
```
timeout 10 ros2 launch mypkg talk_listen.launch.py
```
timeout の後の数字は秒数なので数字を変えれば実行される時間が変わります
* 実行結果
```
[listener-2] [INFO] [1672576645.404412479] [listener]: Listen: 0
[listener-2] [INFO] [1672576645.861709843] [listener]: Listen: 1
[listener-2] [INFO] [1672576646.362042525] [listener]: Listen: 2
[listener-2] [INFO] [1672576646.861349089] [listener]: Listen: 3
[listener-2] [INFO] [1672576647.361680882] [listener]: Listen: 4
[listener-2] [INFO] [1672576647.862018433] [listener]: Listen: 5
[listener-2] [INFO] [1672576648.362095711] [listener]: Listen: 6
・
・
・
```
このように数字が１ずつカウントされたものが出てきます．
## 必要なソフトウェア
* ROS2
## テスト環境
* Ubuntu 22.04 LTS
                       
## 備考                                               
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
	* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

* © 2022 Misaki Sekitori
