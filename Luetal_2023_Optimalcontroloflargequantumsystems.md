# Optimal control of large quantum systems: assesing memory and runtime performance of GRAPE

## 著者: Yunwei Lu, et al.
## 出版年: 2023

### 内容
- GRAPEと自動微分（AD）の組み合わせに関する論文。

- ADはメモリコストがボトルネックとなる。この論文ではメモリ要件を大幅に削減する戦略を提案。

- 大規模な量子系ではこのようなメモリリソースはボトルネックとなりうる。

- $e^a_B = (1 + B + \frac{B^2}{2} + \dots + \frac{B^m}{m!})\ket{\Psi}$ を利用して実行時間を$O(d^2)$へと落とせる。

- $\frac{\partial U_n}{\partial a_n} \ket{\Psi}$の計算は行列演算によって実現。

- ヒルベルト空間や時間ステップが大きい場合にメモリ使用量やランタイムがネックとなる。その場合はhard-coded gradientの方法が適している。

### メモ
- QOC以外でも古典的なメモリがボトルネックとなるようなテーマはあるか。

- Chebyshev展開はTaylor展開より収束が早い。

- 半自動微分を使用してQOC。
