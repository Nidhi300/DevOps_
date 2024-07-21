Given the generator matrix 
G
G:

1 & 0 & 0 & 0 & 1 & 1 & 1 \\
0 & 1 & 0 & 0 & 0 & 1 & 1 \\
0 & 0 & 1 & 0 & 1 & 0 & 1 \\
0 & 0 & 0 & 1 & 1 & 1 & 0
\end{bmatrix} \]
The codewords are found by multiplying all possible message vectors \( \mathbf{m} \) with \( G \). The message vectors for a (7,4) code are all possible 4-bit binary numbers:
\[ \mathbf{m} = \begin{bmatrix}
m_1 & m_2 & m_3 & m_4
\end{bmatrix} \]
There are \( 2^4 = 16 \) possible message vectors. Let's generate all possible codewords:
\[
\begin{align*}
\mathbf{m}_0 &= [0 \ 0 \ 0 \ 0] \quad \Rightarrow \quad \mathbf{c}_0 = \mathbf{m}_0 G = [0 \ 0 \ 0 \ 0 \ 0 \ 0 \ 0] \\
\mathbf{m}_1 &= [0 \ 0 \ 0 \ 1] \quad \Rightarrow \quad \mathbf{c}_1 = \mathbf{m}_1 G = [0 \ 0 \ 0 \ 1 \ 1 \ 1 \ 0] \\
\mathbf{m}_2 &= [0 \ 0 \ 1 \ 0] \quad \Rightarrow \quad \mathbf{c}_2 = \mathbf{m}_2 G = [0 \ 0 \ 1 \ 0 \ 1 \ 0 \ 1] \\
\mathbf{m}_3 &= [0 \ 0 \ 1 \ 1] \quad \Rightarrow \quad \mathbf{c}_3 = \mathbf{m}_3 G = [0 \ 0 \ 1 \ 1 \ 0 \ 1 \ 1] \\
\mathbf{m}_4 &= [0 \ 1 \ 0 \ 0] \quad \Rightarrow \quad \mathbf{c}_4 = \mathbf{m}_4 G = [0 \ 1 \ 0 \ 0 \ 0 \ 1 \ 1] \\
\mathbf{m}_5 &= [0 \ 1 \ 0 \ 1] \quad \Rightarrow \quad \mathbf{c}_5 = \mathbf{m}_5 G = [0 \ 1 \ 0 \ 1 \ 1 \ 0 \ 1] \\
\mathbf{m}_6 &= [0 \ 1 \ 1 \ 0] \quad \Rightarrow \quad \mathbf{c}_6 = \mathbf{m}_6 G = [0 \ 1 \ 1 \ 0 \ 1 \ 1 \ 0] \\
\mathbf{m}_7 &= [0 \ 1 \ 1 \ 1] \quad \Rightarrow \quad \mathbf{c}_7 = \mathbf{m}_7 G = [0 \ 1 \ 1 \ 1 \ 0 \ 0 \ 0] \\
\mathbf{m}_8 &= [1 \ 0 \ 0 \ 0] \quad \Rightarrow \quad \mathbf{c}_8 = \mathbf{m}_8 G = [1 \ 0 \ 0 \ 0 \ 1 \ 1 \ 1] \\
\mathbf{m}_9 &= [1 \ 0 \ 0 \ 1] \quad \Rightarrow \quad \mathbf{c}_9 = \mathbf{m}_9 G = [1 \ 0 \ 0 \ 1 \ 0 \ 0 \ 1] \\
\mathbf{m}_{10} &= [1 \ 0 \ 1 \ 0] \quad \Rightarrow \quad \mathbf{c}_{10} = \mathbf{m}_{10} G = [1 \ 0 \ 1 \ 0 \ 0 \ 1 \ 0] \\
\mathbf{m}_{11} &= [1 \ 0 \ 1 \ 1] \quad \Rightarrow \quad \mathbf{c}_{11} = \mathbf{m}_{11} G = [1 \ 0 \ 1 \ 1 \ 1 \ 0 \ 0] \\
\mathbf{m}_{12} &= [1 \ 1 \ 0 \ 0] \quad \Rightarrow \quad \mathbf{c}_{12} = \mathbf{m}_{12} G = [1 \ 1 \ 0 \ 0 \ 1 \ 0 \ 0] \\
\mathbf{m}_{13} &= [1 \ 1 \ 0 \ 1] \quad \Rightarrow \quad \mathbf{c}_{13} = \mathbf{m}_{13} G = [1 \ 1 \ 0 \ 1 \ 0 \ 1 \ 0] \\
\mathbf{m}_{14} &= [1 \ 1 \ 1 \ 0] \quad \Rightarrow \quad \mathbf{c}_{14} = \mathbf{m}_{14} G = [1 \ 1 \ 1 \ 0 \ 0 \ 0 \ 1] \\
\mathbf{m}_{15} &= [1 \ 1 \ 1 \ 1] \quad \Rightarrow \quad \mathbf{c}_{15} = \mathbf{m}_{15} G = [1 \ 1 \ 1 \ 1 \ 1 \ 1 \ 1] \\
\end{align*}
So, the codewords are:

c
0
=
[
0
 
0
 
0
 
0
 
0
 
0
 
0
]
c
1
=
[
0
 
0
 
0
 
1
 
1
 
1
 
0
]
c
2
=
[
0
 
0
 
1
 
0
 
1
 
0
 
1
]
c
3
=
[
0
 
0
 
1
 
1
 
0
 
1
 
1
]
c
4
=
[
0
 
1
 
0
 
0
 
0
 
1
 
1
]
c
5
=
[
0
 
1
 
0
 
1
 
1
 
0
 
1
]
c
6
=
[
0
 
1
 
1
 
0
 
1
 
1
 
0
]
c
7
=
[
0
 
1
 
1
 
1
 
0
 
0
 
0
]
c
8
=
[
1
 
0
 
0
 
0
 
1
 
1
 
1
]
c
9
=
[
1
 
0
 
0
 
1
 
0
 
0
 
1
]
c
10
=
[
1
 
0
 
1
 
0
 
0
 
1
 
0
]
c
11
=
[
1
 
0
 
1
 
1
 
1
 
0
 
0
]
c
12
=
[
1
 
1
 
0
 
0
 
1
 
0
 
0
]
c
13
=
[
1
 
1
 
0
 
1
 
0
 
1
 
0
]
c
14
=
[
1
 
1
 
1
 
0
 
0
 
0
 
1
]
c
15
=
[
1
 
1
 
1
 
1
 
1
 
1
 
1
]
 
c 
0
​	
 
c 
1
​	
 
c 
2
​	
 
c 
3
​	
 
c 
4
​	
 
c 
5
​	
 
c 
6
​	
 
c 
7
​	
 
c 
8
​	
 
c 
9
​	
 
c 
10
​	
 
c 
11
​	
 
c 
12
​	
 
c 
13
​	
 
c 
14
​	
 
c 
15
​	
 
​	
  
=[0 0 0 0 0 0 0]
=[0 0 0 1 1 1 0]
=[0 0 1 0 1 0 1]
=[0 0 1 1 0 1 1]
=[0 1 0 0 0 1 1]
=[0 1 0 1 1 0 1]
=[0 1 1 0 1 1 0]
=[0 1 1 1 0 0 0]
=[1 0 0 0 1 1 1]
=[1 0 0 1 0 0 1]
=[1 0 1 0 0 1 0]
=[1 0 1 1 1 0 0]
=[1 1 0 0 1 0 0]
=[1 1 0 1 0 1 0]
=[1 1 1 0 0 0 1]
=[1 1 1 1 1 1 1]
​	
 
Part (b): Find the parity check matrix of the code.
The parity check matrix 
H
H is found from the generator matrix 
G
G by ensuring that 
G
H
T
=
0
GH 
T
 =0. For a (7,4) code, 
H
H will be a 
3
×
7
3×7 matrix.

Since 
G
G has the form 
G
=
[
I
k
∣
P
]
G=[I 
k
​	
 ∣P], where 
I
k
I 
k
​	
  is the 
k
×
k
k×k identity matrix and 
P
P is a 
k
×
(
n
−
k
)
k×(n−k) matrix, 
H
H can be found as:

H
=
[
−
P
T
∣
I
n
−
k
]
H=[−P 
T
 ∣I 
n−k
​	
 ]

Here, 
P
P is:

1 & 1 & 1 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{bmatrix} \]
So, \( P^T \) is:
\[ P^T = \begin{bmatrix}
1 & 0 & 1 & 1 \\
