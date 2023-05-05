# RobustQuantumOptimalControlwithTrajectoryOptimization

## 著者: Propsonetal, et al.
## 出版年: 2022

### 内容
- ロボット工学の知識を利用したパラメータドリフト，ノイズ，制御分解能のズレに強い、ロバストなパルスのQOC。

- 制約関数を導入して最適化問題として解く。

- $d^2_t a_k$と$d_t a_k$に制約を課すことによって滑らかな曲線になる。

- フラクソニウムのハミルトニアンを$fq → fq +\delta fq$に変更したときにロバストかどうか。

- サンプルメソッドでは$fq → fq \pm \delta fq$で発展した状態も制約、コスト関数に加えて最適化する。

- unscented sampling method。

- 不確定なパラメーターで状態を微分し、その状態を制約に追加する。unscented sampling methodと共にグローバル位相に敏感なので、複数の初期状態を使用した場合に性能向上しない。


### メモ

- $\ket{0}$から$\ket{1}$への発展に限定したゲート最適になっているので、一般的なゲート最適化を考えるにはどうしたらいいか。