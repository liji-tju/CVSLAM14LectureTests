#### 1
群(Group)是一种集合加上一种运算的代数结构。我们把集合记作A，运算记作*，则群可记作G=(A,*)。群要求这个运算满足下列条件：

* 1.封闭性：<a href="https://www.codecogs.com/eqnedit.php?latex=\forall&space;a_1,a_2\in&space;A,&space;a_1*a_2\in&space;A" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\forall&space;a_1,a_2\in&space;A,&space;a_1*a_2\in&space;A" title="\forall a_1,a_2\in A, a_1*a_2\in A" /></a>
* 2.结合律：<a href="https://www.codecogs.com/eqnedit.php?latex=\forall&space;a_1,a_2,a_3\in&space;A,&space;(a_1*a_2)*a_3=a_1*(a_2*a_3)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\forall&space;a_1,a_2,a_3\in&space;A,&space;(a_1*a_2)*a_3=a_1*(a_2*a_3)" title="\forall a_1,a_2,a_3\in A, (a_1*a_2)*a_3=a_1*(a_2*a_3)" /></a>
* 3.存在幺元(identity element)：<a href="https://www.codecogs.com/eqnedit.php?latex=\exists&space;a_0\in&space;A,\&space;s.t.\&space;\forall&space;a\in&space;A,&space;a_0*a=a*a_0=a" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\exists&space;a_0\in&space;A,\&space;s.t.\&space;\forall&space;a\in&space;A,&space;a_0*a=a*a_0=a" title="\exists a_0\in A,\ s.t.\ \forall a\in A, a_0*a=a*a_0=a" /></a>
* 4.可逆：<a href="https://www.codecogs.com/eqnedit.php?latex=\forall&space;a\in&space;A,\&space;\exists&space;a^{-1}\in&space;A,\&space;s.t.\&space;a*a^{-1}=a_0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\forall&space;a\in&space;A,\&space;\exists&space;a^{-1}\in&space;A,\&space;s.t.\&space;a*a^{-1}=a_0" title="\forall a\in A,\ \exists a^{-1}\in A,\ s.t.\ a*a^{-1}=a_0" /></a>

1.特殊正交群(Special Orthogonal Group)SO(3):

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=SO(3)=\{\mathbf{R}\in&space;\mathbb{R}^{3\times3}|\mathbf{RR}^T=\mathbf{I},det(\mathbf{R})=1\}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?SO(3)=\{\mathbf{R}\in&space;\mathbb{R}^{3\times3}|\mathbf{RR}^T=\mathbf{I},det(\mathbf{R})=1\}" title="SO(3)=\{\mathbf{R}\in \mathbb{R}^{3\times3}|\mathbf{RR}^T=\mathbf{I},det(\mathbf{R})=1\}" /></a>
</p>  

下面验证其是否与矩阵乘法满足群成立的四个条件：
* 1.封闭性：<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{R_1R_2}\in&space;\mathbb{R}^{3\times3}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{R_1R_2}\in&space;\mathbb{R}^{3\times3}" title="\mathbf{R_1R_2}\in \mathbb{R}^{3\times3}" /></a>, <a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{R_1R_2}(\mathbf{R_1R_2})^T=\mathbf{R_1R_2}\mathbf{R_2}^T\mathbf{R_1}^T=\mathbf{I}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{R_1R_2}(\mathbf{R_1R_2})^T=\mathbf{R_1R_2}\mathbf{R_2}^T\mathbf{R_1}^T=\mathbf{I}" title="\mathbf{R_1R_2}(\mathbf{R_1R_2})^T=\mathbf{R_1R_2}\mathbf{R_2}^T\mathbf{R_1}^T=\mathbf{I}" /></a>, <a href="https://www.codecogs.com/eqnedit.php?latex=det(\mathbf{R_1R_2})=det(\mathbf{R_1})det(\mathbf{R_2})=1" target="_blank"><img src="https://latex.codecogs.com/gif.latex?det(\mathbf{R_1R_2})=det(\mathbf{R_1})det(\mathbf{R_2})=1" title="det(\mathbf{R_1R_2})=det(\mathbf{R_1})det(\mathbf{R_2})=1" /></a>。所以可以看出<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{R_1R_2}&space;\in&space;SO(3)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{R_1R_2}&space;\in&space;SO(3)" title="\mathbf{R_1R_2} \in SO(3)" /></a>，即满足封闭性。
* 2.结合率：我们知道矩阵乘法是满足结合律的，所以得证。
* 3.存在幺元(identity element)：<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{RI}=\mathbf{IR}=\mathbf{R}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{RI}=\mathbf{IR}=\mathbf{R}" title="\mathbf{RI}=\mathbf{IR}=\mathbf{R}" /></a>, 幺元为单位矩阵**I**。
* 4可逆：因为<a href="https://www.codecogs.com/eqnedit.php?latex=det(\mathbf{R})\neq&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?det(\mathbf{R})\neq&space;0" title="det(\mathbf{R})\neq 0" /></a>，所以**R**可逆。

所以，命题得证。


2.特殊欧式群(Special Euclidean Group)SE(3):

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=SE(3)=\left&space;\{&space;\mathbf{T}=\begin{bmatrix}&space;\mathbf{R}&space;&\vec{t}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}\in\mathbb{R}^{4\times4}|\mathbf{R}\in&space;SO(3),\vec{t}\in&space;\mathbb{R}^3&space;\right&space;\}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?SE(3)=\left&space;\{&space;\mathbf{T}=\begin{bmatrix}&space;\mathbf{R}&space;&\vec{t}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}\in\mathbb{R}^{4\times4}|\mathbf{R}\in&space;SO(3),\vec{t}\in&space;\mathbb{R}^3&space;\right&space;\}" title="SE(3)=\left \{ \mathbf{T}=\begin{bmatrix} \mathbf{R} &\vec{t} \\ \vec{0}^T & 1 \end{bmatrix}\in\mathbb{R}^{4\times4}|\mathbf{R}\in SO(3),\vec{t}\in \mathbb{R}^3 \right \}" /></a>
</p> 

下面验证其是否与矩阵乘法满足群成立的四个条件：
* 1.封闭性：<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{T_1T_2}=\begin{bmatrix}&space;\mathbf{R_1}&space;&\vec{t_1}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}\begin{bmatrix}&space;\mathbf{R_2}&space;&\vec{t_2}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}=\begin{bmatrix}&space;\mathbf{R_1R_2}&space;&\mathbf{R_1}\vec{t_2}&plus;\vec{t_1}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{T_1T_2}=\begin{bmatrix}&space;\mathbf{R_1}&space;&\vec{t_1}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}\begin{bmatrix}&space;\mathbf{R_2}&space;&\vec{t_2}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}=\begin{bmatrix}&space;\mathbf{R_1R_2}&space;&\mathbf{R_1}\vec{t_2}&plus;\vec{t_1}&space;\\&space;\vec{0}^T&space;&&space;1&space;\end{bmatrix}" title="\mathbf{T_1T_2}=\begin{bmatrix} \mathbf{R_1} &\vec{t_1} \\ \vec{0}^T & 1 \end{bmatrix}\begin{bmatrix} \mathbf{R_2} &\vec{t_2} \\ \vec{0}^T & 1 \end{bmatrix}=\begin{bmatrix} \mathbf{R_1R_2} &\mathbf{R_1}\vec{t_2}+\vec{t_1} \\ \vec{0}^T & 1 \end{bmatrix}" /></a>。上文中已验证<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{R_1R_2}&space;\in&space;SO(3)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{R_1R_2}&space;\in&space;SO(3)" title="\mathbf{R_1R_2} \in SO(3)" /></a>，且显然<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{R_1}\vec{t_2}&plus;\vec{t_1}\in&space;\mathbb{R}^3" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{R_1}\vec{t_2}&plus;\vec{t_1}\in&space;\mathbb{R}^3" title="\mathbf{R_1}\vec{t_2}+\vec{t_1}\in \mathbb{R}^3" /></a>，所以<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{T_1}\mathbf{T_2}\in&space;SE(3)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{T_1}\mathbf{T_2}\in&space;SE(3)" title="\mathbf{T_1}\mathbf{T_2}\in SE(3)" /></a>，即满足封闭性。
* 2.结合率：我们知道矩阵乘法是满足结合律的，所以得证。
* 3.存在幺元(identity element)：<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{TI}=\mathbf{IT}=\mathbf{T}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{TI}=\mathbf{IT}=\mathbf{T}" title="\mathbf{TI}=\mathbf{IT}=\mathbf{T}" /></a>, 幺元为单位矩阵**I**。
* 4可逆：因为<a href="https://www.codecogs.com/eqnedit.php?latex=det(\mathbf{R})\neq&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?det(\mathbf{R})\neq&space;0" title="det(\mathbf{R})\neq 0" /></a>，所以**R**可逆。

所以，命题得证。
