## I. Linear Regression and ML Introduction
 - A general linear function for vector **x**: $f(x;w,b) =w^Tx+b$, where $w$ and $x$ are two column vectors.
---> a. For multiple instances: $\underline{y} = \underline{X}w + b$. when output $\underline{y}$ and input $\underline{X}$ are matrix, stacked by $n$ input-output pairs $(x^{(i)},y^{(i)}), i = 1,2,...n$:
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
   x_1^{(n)} & x_2^{(n)} &...& x_D^{(n)}
  \end{matrix} 
\right),\underline{y} = \left(
 \begin{matrix}
   y^{(1)}\\
   \vdots\\
   y^{(n)}
  \end{matrix} 
\right),
$$where D is the dimension of the data, n is the number of the instances. $$\newline$$
---> b. Total square error between prediction function $f$ and true value: $$L = \sum_{n=1}^{N}[y^{(n)}-f(x^{(n)};w,b)]^2 = (y-f)^T(y-f)$$ 
 - The least-square fitting problem is to find the parameters (in this case $w,b$) that minimize the error.
 - 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4ODUwMDAwNDAsLTE4NDA0MDc4MTUsLT
E3MTcyMjk0ODMsLTE3MDY5OTI2NjldfQ==
-->