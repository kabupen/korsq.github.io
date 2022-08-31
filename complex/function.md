## 複素関数

複素数 $z$ に対して $w=f(z)$ なる関数があるとき、それを複素関数という。

## 図形

$(x,y)$を用いて表すか、複素数 $z$ を用いて表すかの差である。

### 直線

$\bar{\alpha}z + \alpha\bar{z} + c = 0$

## 円の方程式

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

### 円の方程式にする

$z = k~~(k\neq 0)$ が $w=1/z$ においてどの様な図形に射影されるか？

以下の変形はよく使用する：
$$
x =\frac{z+\bar{z}}{2}~~~(\because z=x+iy,~\bar{z}=x-iy)\\
$$
いまは $z=k$（$k$は複素定数）であるので
$$
k = \frac{z+\bar{z}}{2} \\
k = \frac{1/w+1/\bar{w}}{2} \\
2kw\bar{w} -\bar{w} - w = 0 \\
w\bar{w} -\frac{1}{2k}\bar{w} - \frac{1}{2k}w = 0 \\
\bar{w}\left(w-\frac{1}{2k}\right) -\frac{1}{2k}\left(w-\frac{1}{2k}\right) - \frac{1}{4k^2}= 0 \\
\left(w-\frac{1}{2k}\right)\left(\bar{w}-\frac{1}{2k}\right) = \frac{1}{4k^2} \\
\left|w-\frac{1}{2k}\right| = \frac{1}{2k} \\
$$
となり、複素関数$f(z)=1/z$ によって $w$ 平面上における円上に射影される。

### 複素定数 $\alpha$ の近傍

円の方程式の形を用いて、ある複素定数の近傍は
$$
|z-\alpha| < \delta
$$
と不等式で表せる。