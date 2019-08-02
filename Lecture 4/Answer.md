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
* 1.封闭性：<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{R_1R_2}\in&space;\mathbb{R}^{3\times3}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{R_1R_2}\in&space;\mathbb{R}^{3\times3}" title="\mathbf{R_1R_2}\in \mathbb{R}^{3\times3}" /></a>, <a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{R_1R_2}(\mathbf{R_1R_2})^T=\mathbf{R_1R_2}\mathbf{R_2}^T\mathbf{R_1}^T=\mathbf{I}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{R_1R_2}(\mathbf{R_1R_2})^T=\mathbf{R_1R_2}\mathbf{R_2}^T\mathbf{R_1}^T=\mathbf{I}" title="\mathbf{R_1R_2}(\mathbf{R_1R_2})^T=\mathbf{R_1R_2}\mathbf{R_2}^T\mathbf{R_1}^T=\mathbf{I}" /></a>
