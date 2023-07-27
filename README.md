# RC_robot
OSOYOOのロボットカーをSTM32f405に載せ替えてC言語で制御及び機能追加してみた
ハードウェアのリンク
https://osoyoo.com/ja/2021/04/09/sg90-servo-steering-robot-car-kit/

追加機能はRTOSによるマルチスレッド処理、加速度センサーによるショック検知＆回避機能　PID制御による正面距離維持移動

