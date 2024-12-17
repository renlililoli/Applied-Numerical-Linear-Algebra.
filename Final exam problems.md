### Final exam problems(2024 autumn)

1. Answer following queations briefly.
   - $A \in \Real^{m\times n}$, $B \in \Real^{n\times p}$, $C \in \Real^{p\times q}$. How to compute $D = ABC$?
   - $X$, $Y$ are $3\times 2$ matrices, $X^\top X = Y^\top Y = I_2$, what is the angle of these two spaces spaned by $X,Y$?
   - Campare **CGS, MGS, Givens, Householder** briefly when using them to compute QR factorization.
   - What symmetry eigenvalue mathods can not be applied to the non-symmetry case.
   - Forgot :)
2. If $A$ is column full rank, then prove:
   $$\begin{equation}
       \begin{pmatrix}I & A^\top\\A&0\end{pmatrix}\begin{pmatrix}r\\x\end{pmatrix} = \begin{pmatrix}b\\0\end{pmatrix}
   \end{equation}$$
   is equaivlent to the least square problem of $(A,b)$.
3. If $A$ is a strictly column dominate matrix, i.e., $\sum_{k\neq i}\abs{A_{ki}} < \abs{A_{ii}}$, then
   - Please prove that in **gepp** to compute the $LU$ factorization of $A$, row exchanges never happen.
   - Please give an upper bound of the condition number of $L$, you can choose any norm you like.

5. Describe and prove the **Implicit Q Theorem**.
6. If $A$ is an upper-triangular matrix with $A_{ii}\neq A_{jj}$ for all $i\neq j$, then please propose a psedo-code to
   compute the eigen vectors of $A$, i.e., compute $X, \Lambda$ such that
   $$\begin{equation}
       A = X\Lambda X^\{-1}.
   \end{equation}$$
7. In **Divide & Conqure** method to solve the eigenvalue problem of symmetry matrices, w.l.o.g., we assume that
   $$\begin{equation}
       D + uu^\top
   \end{equation}$$
   - Elements in diag matrix $D$ are different from each other,
   - $u_i\neq 0$.
   
   Please prove why this does not lose any genelarity.
