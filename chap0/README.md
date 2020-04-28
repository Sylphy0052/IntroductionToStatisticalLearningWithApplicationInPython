# 第0章 線形代数

## 0.1 逆行列

$A \in \mathbb{R}^{m \times n}$, $b \in \mathbb{R}^m$から$Ax=b$なる$x \in \mathbb{R}^n$を考える．系列行列$A$もしくは$A$の横に1列ベクトル$b$をつなぎ合わせた行列(拡大係数行列)$[A|b] \in \mathbb{R}^{m \times (n+1)}$について

* ある行列全体を非ゼロ定数で割る
* ある2行を入れ替える
* ある行の何杯かを他の行に加える

以上の操作を行い，$A$が$B \in \mathbb{R}^{m \times n}$に変形できることを$A \sim B$で表す．