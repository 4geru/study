## 01. 統計
### 主な統計量
- 平均
```
ex) 30, 40, 50 = (30 + 40 + 50) / 3
```

$$
\overline{x} = \frac{1}{N} \sum_{n=1}^{N} x_n\\
$$


- 分散

母集団 > 標本集団について、それぞれ分散が存在する

母分散

$$
\sigma^{2} = \frac{1}{N} \sum_{n=1}^{N} (x_n - \bar{x})^2 \\
$$

標本分散

$$
\sigma^{2} = \frac{1}{N - 1} \sum_{n=1}^{N} (x_n - \bar{x})^2 \\
$$

- 標準偏差

元のスケールにする。データのばらつきを定量評価

$$
\sigma = \sqrt{\sigma^{2}}
$$

## 02. 練習問題

集団1: (-2, -1, 0, 1, 2)
集団2: (-4, -2, 0, 2, 4)

- 平均

集団1: 0 / 5 = 0
集団2: 0 / 5 = 0

- 分散

集団1: (4 + 1 + 0 + 1 + 4) / 5 = 2
集団2: (16 + 4 + 0 + 4 + 16) / 5 = 8

- 標準偏差

集団1: sqrt{2}
集団2: 2 sqrt{2}

標準偏差より、ばらつきが大きいことがわかる

## 03. 正規分布と3\sigma法

### 正規分布
- 数式として扱いやすい
- 物理現象として出てくる

$$
\sigma = 68 \% \\
2 \sigma = 95 \% \\
3 \sigma = 99.7 \%
$$

Hanmpel判別法

## 04. スケーリング