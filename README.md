# TMDS_TEMPEST_Simulator
HDMI TEMPEST 再構築画像シミュレータ

TMDS信号については[こちら](https://github.com/daianjibetu/TMDS_Signal_Simulator)を参照
<br><br>

## 実行方法
Google Colab上で実行可能

画像をアップロードすると、グレースケールに変換された後、画像の再構築が行われます。
<br><br><br>
画像の再構築では、仕様が以下の点で異なります。

- [TMDS_TEMPEST_Simulator.ipynb](TMDS_TEMPEST_Simulator.ipynb)

  Transition Minimized（遷移時間最短）：未考慮
  <br>
  DC Balanced（DCバランス）：考慮
<br><br>
- [TMDS_TEMPEST_Simulator_2.ipynb](TMDS_TEMPEST_Simulator_2.ipynb)

  Transition Minimized（遷移時間最短）：考慮
  <br>
  DC Balanced（DCバランス）：考慮

<br><br>

## 実行結果
入力画像①
<img src="img/1.png"><br><br>

出力画像①
<img src="img/1_TEMPEST.png"><br><br>

入力画像②
<img src="img/2.png"><br><br>

出力画像②
<img src="img/2_TEMPEST.png"><br><br>
