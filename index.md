@def title = "试试整个博客"
@def hasmath = true
@def hascode = true

# 这是什么site捏

\tableofcontents

## 我喜欢Julia
* Julia 很简单
* Julia 很快
## 我精通Julia的安装与卸载
```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```
## 然后结束
$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

$$\forall \epsilon > 0, 
\exist \delta > 0,
\forall x \in \R: \quad 
0<|x-x_0|<\delta \Rightarrow |f(x)-L|<\epsilon$$

<!-- # Franklin syntax sandbox

This page is meant as a sandbox for Franklin Syntax so that you can quickly practice or experience things.

## Sandbox

Write whatever you want here to practice Franklin Syntax:

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```

\output{./ex1}

(yet another example that floating point arithmetics can be complicated).

$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

\newcommand{\E}{\mathbb E}

Surely some people remember the ordering, but I always forget:

$$ \varphi(\E[X]) \le \E[\varphi(X)] $$

for $\varphi$ convex. -->
