## 集族，幂集和集合的划分

集合的集合称为集类或者集族。集族中的元素（集合），称为子类或子族。

### 幂集

对于给定的集合S，其所有可能子集的族，称为集合S的幂集。记作：Power(S)。如果S为有限集，则Power(S)也是有限集。并且：

n(Power(S)) = 2 ^ n(S)

### 划分

设S是一个非集合，S的一个划分是将S剖分为一些不交叠的非空子集。即：S的一个划分是S的一族非空子集{A_i}，满足：
  1. S中的每个元素a属于一个A_i；
  2. `{A_i}`中的集合互不相交，即对于两个不同的集合， `A_i ∩ A_j = 0`。

划分中的子集叫胞腔。

## 集合运算的推广

### 定理1.7

设A为集族，则：
  1. `(∪(A_i : A_i ∈ A))ᶜ = ∩(A_iᶜ: A_i ∈ A)`
  2. `(∩(A_i : A_i ∈ A))ᶜ = ∪(A_iᶜ: A_i ∈ A)`

## 数学归纳法

### 数学归纳法原理I

设 P 是定义于正整数集合N上的一个命题，即对N中的每个n，P(n) 或者正确或者不正确。假设P具有下列两个性质：

  1. P(1)为真，
  2. 只要P(n)为真，P(n+1)亦为真

则对任意正整数，P都为真。

### 数学归纳法原理II

设P是定义于正整数N上的一个命题，使得：

  1. P(1)为真，
  2. 当对于所有的 1 <= k < n，P(k) 为真时，有P(n)为真，

则P对于所有的正整数为真。