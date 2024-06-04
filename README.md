﻿# Pong_game
<br>
このコードはC++によって書かれています。
<br>
### 導入必要なライブラリー
SDL2/SDL.h
<br>
これは2人用のシンプルなPongゲームです。
<br>
#### 操作方法

|プレイヤー１(左側のパドル)|プレイヤー２(右側のパドル)|
|:-------------------------|:-------------------------|
|上移動: Wキー             |上移動: Iキー              |
|下移動: Sキー             |下移動: Kキー              |

ゲーム終了: ESCキー
<br>

#### ゲームの流れ

ゲーム開始時、ボールが1つ中央に配置されます。
<br>
  プレイヤーは、上下キーを使ってパドルを操作し、ボールを打ち返します。
  <br>
  ボールが上下の壁に当たると、反射します。
  <br>
  ボールがパドルに当たると、反対方向に跳ね返ります。
  <br>
  30秒ごとに、最大5個までボールが追加されます。
  <br>
  ボールが左右の画面外に出ると、ゲームが終了します。
  <br>
##### ゲームの目的

  相手のパドルを抜かれないように、ボールを打ち返し続けることが目的です。
  <br>
  より長い時間ラリーを続けることを目指しましょう。
  <br>
