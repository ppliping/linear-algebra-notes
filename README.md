# 线性代数学习笔记 · Linear Algebra Study Notes

基于 **Lay, Lay & McDonald《Linear Algebra and Its Applications》(6th Edition, 2022)** 的个人学习笔记。

## 📖 笔记结构

每章笔记（`chapterN.ipynb`）包含两部分：

| 部分 | 内容 | 完成方式 |
|---|---|---|
| 一、知识点总结 | 全章各节核心概念、定理与几何直觉 | Markdown + LaTeX |
| 二、习题解答 | 指定习题的完整解答 | 推导证明用 Markdown；计算验证用 Python |

## 📚 当前章节 · 知识点速览（第 1 章　线性方程组的线性代数）

> 每学完新的一章，此表更新为该章要点；完整内容见对应笔记。

| 节 | 核心内容 | 关键结论 / 定理 |
|:---:|---|---|
| 1.1 | 线性方程组、增广矩阵、初等行变换、阶梯形（EF/RREF）、主元 | 方程组**相容** ⟺ 增广矩阵最右列不是主元列 |
| 1.2 | 行化简算法（向前/向后阶段）、欠定与超定系统、计算量 flops | 定理 2：相容 ⟺ 右端列无主元；唯一解 ⟺ 无自由变量 |
| 1.3 | 向量、线性组合、张成 Span、向量方程 | 向量方程 ⇔ 线性方程组 ⇔ 矩阵方程（同一问题的三种形态） |
| 1.4 | 矩阵方程 $A\mathbf{x}=\mathbf{b}$：$A\mathbf{x}$ 即列向量的线性组合 | 定理 4：对每个 $\mathbf{b}$ 有解 ⟺ 列张成 $\mathbb{R}^m$；定理 5：唯一解 ⟺ 张成且线性无关 |
| 1.5 | 齐次方程组、解的参数向量形式、解集几何 | 定理 6：非齐次解集 = 特解 $\mathbf{p}$ + 齐次解（平移） |
| 1.6 | 应用建模思路（营养配方、网络等） | 实际问题 → $A\mathbf{x}=\mathbf{b}$ → 解 → 回到实际解释 |
| 1.7 | 线性无关 / 线性相关的定义与判定 | 定理 8：$\mathbb{R}^n$ 中多于 $n$ 个向量必相关；**主元列定理**：非主元列 = 主元列的线性组合 |
| 1.8 | 线性变换（保加法 + 保数乘）、矩阵变换、几何变换 | $T$ 线性 ⟹ $T(\mathbf{0})=\mathbf{0}$；叠加原理 |
| 1.9 | 标准矩阵 $A=[\,T(\mathbf{e}_1)\ \cdots\ T(\mathbf{e}_n)\,]$、单射 / 满射 | 定理 11：满射 ⟺ 列张成；定理 12：单射 ⟺ 列线性无关（$A\mathbf{x}=\mathbf{0}$ 仅平凡解） |
| 1.10 | 差分方程 $\mathbf{x}_{k+1}=A\mathbf{x}_k$、马尔可夫链、电路网孔法 | 正则马尔可夫链收敛于稳态 $\mathbf{q}$（$M\mathbf{q}=\mathbf{q}$）；网孔法 → 线性方程组 |

## 📊 学习进度

| 章节 | 主题 | 笔记 | 状态 |
|:---:|---|:---:|:---:|
| 1 | 线性方程组的线性代数 *Linear Equations in Linear Algebra* | [chapter1.ipynb](chapter1.ipynb) | ✅ 2026-09-25 |
| 2 | 矩阵代数 *Matrix Algebra* | — | ⏳ |
| 3 | 行列式 *Determinants* | — | ⏳ |
| 4 | 向量空间 *Vector Spaces* | — | ⏳ |
| 5 | 特征值与特征向量 *Eigenvalues and Eigenvectors* | — | ⏳ |
| 6 | 正交性与最小二乘 *Orthogonality and Least Squares* | — | ⏳ |
| 7 | 对称矩阵与二次型 *Symmetric Matrices and Quadratic Forms* | — | ⏳ |
| 8 | 向量空间的几何 *The Geometry of Vector Spaces* | — | ⏳ |
| 9 | 最优化 *Optimization* | — | ⏳ |

## 📁 目录结构

```
.
├─ README.md          # 本文件（含知识点速览与进度表，每章更新）
├─ chapterN.ipynb     # 各章笔记：chapter1.ipynb, chapter2.ipynb, ...
└─ ...
```
