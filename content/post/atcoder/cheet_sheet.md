
# 四則演算

```python
a // b # 商を切り下げたもの：3//2=1（1.5を1に切り下げ）
a % b  # 剰余：3%2=1
```

# 標準入力を受け取る

## 行数指定あり、入力フォーマットがある

```python
# 標準入力を1行取得する（1行を文字として取得）
# abcd --> 'abcd'
s = input()
```

```python
# 標準入力を2行取得する
s = [input() for _ in range(2)] # --> ['a', 'b'] のリスト形式になる
```

### 文字分解

```python
# s = '1100101'
# list(s) --> ['1', '1', '0', '0', '1', '0', '1']
list(s) 
```

```python
s = '101'
s1,s2,s3 = list(s)
# s1=1, s2=0, s3=1
```

## 行数指定なし

行数指定なしで
```
1 1 1 1 
2 2 
3 4 5 6 6
...
```

というデータを読む場合は、while ループで try-except する。

```python
while True:
    try:
        s = input()
    except:
        break
```

複数行を一度に集める場合は、

```python
while True:
```

# 問題

## Coins

あなたは、500 円玉を A 枚、100 円玉を B 枚、50 円玉を C 枚持っています。 これらの硬貨の中から何枚かを選び、合計金額をちょうど X 円にする方法は何通りありますか。

--> 全探索すること！！

```python
a = int(input())
b = int(input())
c = int(input())
x = int(input())

correct_comb = 0
for num_a in range(a+1):
    for num_b in range(b+1):
        for num_c in range(c+1):
            if 500 * num_a + 100 * num_b + 50 * num_c == x : correct_comb += 1
print(correct_comb)
```