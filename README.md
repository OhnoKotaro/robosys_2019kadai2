# robosys_2019kadai2
ロボットシステム学課題2_ROS

### 概要
講義で使用したcount_upノードの一桁の数によって光るLEDの数が変わるプログラムです．0個から最大9個まで光ります．

### 動作環境
|||
|:--:|:--:|
| Raspberry Pi | Raspberry Pi Model 3B+ |
| OS | Ubuntu18.04 |
| ROS | ROS Melodic |
| LEDの数 | 9 |

### 実行方法

```
$ cd ~/catkin_ws/src
$ git clone https://github.com/OhnoKotaro/robosys_2019kadai2.git
$ cd ..
$ catkin_make
$ cd src/robosys_2019kadai2/ROSled
$ bash LEDsetup.sh
$ roslaunch robosys_2019kadai2 LED.launch
```

### 回路図
<img src="file:///C:/Users/kotar/Documents/6s/%E3%83%AD%E3%83%9C%E3%83%83%E3%83%88%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%AD%A6/robosyskadai2.png">
### デモ動画
