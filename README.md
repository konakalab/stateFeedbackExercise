# このリポジトリについて
状態フィードバックの演習用ファイルです．
名城大学情報工学部小中研での研究紹介，研究室体験での利用を想定して作成しました．

ファイル実行の順序は以下を想定しています．
- SpringMassDumper_noControl.mlx　ばね・おもり・ダンパ系で制御していない挙動を再現します．
- SpringMassDumper_StateFB.mlx　状態フィードバックゲインを適当に決めた場合の挙動を再現します．
- SpringMassDumper_LQR.mlx　最適制御(Linear Quadratic Regulator)の挙動を再現します．

また，parameterSetup.m は制御対象やアニメーション描画の有無などを設定するファイルです．

# MATLAB Onlineへのリンク
以下のリンクをクリックするとMATLAB Onlineで開くことができます
（無料のMathWorksアカウントが必要です．有料のMATLABライセンスは不要です）

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=konakalab/stateFeedbackExercise)

- 無料のMATLAB Online(basic)については以下のリンク先をご参照ください．
  https://jp.mathworks.com/products/matlab-online/matlab-online-versions.html
