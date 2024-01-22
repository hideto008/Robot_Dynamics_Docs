# 単位ベクトル法で関節慣性行列を計算する

単位ベクトル方はRNEAを用いて関節慣性行列 $\boldsymbol{H}(\boldsymbol{\theta})$を計算する方法の一つ。

$$
\begin{equation}
\boldsymbol{\tau} = \boldsymbol{H}(\boldsymbol{\theta}) \ddot{\boldsymbol{\theta}} + \boldsymbol{B}(\boldsymbol{\theta}, \dot{\boldsymbol{\theta}}) + \boldsymbol{C}(\boldsymbol{\theta})g + \boldsymbol{J}^T K
\end{equation}
$$

1. $\boldsymbol{\tau}$ : 関節にあるアクチュエータが発生するトルク (縦ベクトル)
1. $\boldsymbol{\theta}$ : 関節角度 (縦ベクトル)
1. $\dot{\boldsymbol{\theta}}$ : 関節角速度 (縦ベクトル)
1. $\ddot{\boldsymbol{\theta}}$ : 関節角加速度 (縦ベクトル)
1. $\boldsymbol{H}(\boldsymbol{\theta})$ : 慣性行列 (行列)
1. $\boldsymbol{B}(\boldsymbol{\theta}, \dot{\boldsymbol{\theta}})$ : 遠心力とコリオリの力の項 (縦ベクトル)
1. $\boldsymbol{C}(\boldsymbol{\theta})$ : 重力項 (縦ベクトル)
1. $g$ : 重力加速度 (スカラー)
1. $\boldsymbol{J}$ : 基礎ヤコビ行列 (行列)
1. $\boldsymbol{K}$ : マニピュレータ先端に加わる外力$\boldsymbol{F}$と外力モーメント$\boldsymbol{N}$をまとめた($\boldsymbol{F}^T, \boldsymbol{N}^T)^T$ (縦ベクトル)






