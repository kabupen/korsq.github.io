
# 複素数について

## 基本性質

複素数の基本性質、よく使用する関係式を列挙する。

- 複素数 $z=x+iy$
- 共役複素数 $\bar{z} =x-iy$
- 絶対値：$|z|=\sqrt{z\bar{z}}=\sqrt{x^2+y^2}=r$
- 極形式：$z=re^{i\theta}$
- 偏角：$\theta=\arg z$（$2n\pi$ の自由度を持っている）
- 主値：偏角のうち、$[-\pi,\pi]$　の範囲の偏角のこと

以下で補足説明を行う：

## 絶対値

複素数の絶対値は
$$
|z| = r = \sqrt{x^2+y^2} = \sqrt{z\bar{z}}
$$
である。


## 極形式

複素数 $z=a+ib$ は、絶対値 $|z|=r$、偏角 $\arg z=\theta$として $z=re^{i\theta}$とできる。偏角は$2n\pi$の自由度があるので一意には決まらないことに注意。$[0,2\pi]$の範囲の偏角を特に主値（principal value）という。


## 複素関数

複素数 $z$ に対して $w=f(z)$ なる関数があるとき、それを複素関数という。

## 図形

$(x,y)$を用いて表すか、複素数 $z$ を用いて表すかの差である。

### 直線

$\bar{\alpha}z + \alpha\bar{z} + c = 0$

### 円の方程式

複素平面上の円の方程式は、複素変数 $z$、複素定数（中心）$\alpha$、正の実定数 $r$を用いて
$$
|z-\alpha|=r
$$
と表せる。$x,y$に戻すと

$$
|z-\alpha|^2 = r^2 \\
(z-\alpha)(\overline{z-\alpha}) = r^2 \\
(z-\alpha)(\overline{z} -\overline{\alpha}) = r^2 \\
\dots\\
(x-a)^2+(y-b)^2 = r^2
$$

と、よく見た円の方程式になる。

### 複素定数 $\alpha$ の近傍

円の方程式の形を用いて、ある複素定数の近傍は
$$
|z-\alpha| < \delta
$$
と不等式で表せる。