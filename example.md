一个单子 $(T,\eta,\mu)$ 由函子与两个自然变换组成，满足一条结合律与两条单位律.

$$
\mu\circ T\mu=\mu\circ\mu T,\qquad \mu\circ T\eta=1_T=\mu\circ\eta T.
$$

## *1.1* 代数与比较函子

:::definition 定义 1.1
$T$-代数是一个二元组 $(X,x)$，其中 $x\colon TX\to X$ 满足 $x\circ\eta_X=1_X$ 与 $x\circ\mu_X=x\circ Tx$. 它们与保持结构的态射一起构成 Eilenberg-Moore 范畴 $\mathcal C^T$.
:::

遗忘函子 $U^T\colon\mathcal C^T\to\mathcal C$ 有左伴随 $F^T\colon X\mapsto(TX,\mu_X)$，其复合 $U^TF^T$ 恰好是原来的单子. 对任意的伴随 $F\dashv U$，都存在唯一的比较函子 $K\colon\mathcal D\to\mathcal C^T$ 使 $U^TK=U$.

:::remark 评注 1.2
单子的三个标准例子：自由群伴随诱导的单子，幂集函子 $P\colon\mathbf{Set}\to\mathbf{Set}$ 连同单位与并集乘法，以及任意幂等单子. 前两者的 Eilenberg-Moore 范畴分别是群与完备格. 这些伴随的比较函子何时是等价，见 ++定理 2.2++.
:::

:::theorem 定理 2.2
（Beck 单子性定理）比较函子 $K$ 是等价当且仅当 $U$ 有左伴随、反映同构，并且 $\mathcal D$ 有 $U$-分裂对的余等子且 $U$ 保持它们.
:::
