## I. Linear Regression and ML Introduction
1. A general linear function for vector **x**: $f(x;w,b) =w^Tx+b$, where $w$ and $x$ are two column vectors.
---> a. when output $\underline{y}$ and input $\underline{X}$ are matrix, stacked by $n$ input-output pairs $(x^{(i)},y^{(i)}), i = 1,2,...n$:

$$\underline{X}=
\left(
 \begin{matrix}
   x^{(1)^T}\\
   \vdots\\
   x^{(n)^T}
  \end{matrix} 
\right)=
\left(
 \begin{matrix}
   x_1^{(1)} & x_2^{(1)} &...& x_D^{(1)}\\
   x_1^{(2)} & x_2^{(2)} &...& x_D^{(2)}\\
  \vdots&\vdots&\ddots\\
   p & q & r & s & t
  \end{matrix} 
\right)
$$
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNjAzNDA3MzksLTE4NDA0MDc4MTUsLT
E3MTcyMjk0ODMsLTE3MDY5OTI2NjldfQ==
-->