

## MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications



### Standard convolution 

カーネルを $K$、入力特徴量を $F$、出力特徴量を $G$ とする。出力チャンネル数を$N$、画素の番号を$(k,l)$で表すこととすると、ストライド1、パディングありな標準的な畳込み演算は：
$$
G_{k,l,n} = \sum_{i,j,m} K_{i,j,m,n} \cdot F_{k+i-1,l+j-1,m}
$$
で表される。


### MobileNets convolution

