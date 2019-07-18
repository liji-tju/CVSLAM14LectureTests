#### 1
设**A**为*m*×*n*矩阵，当b=0时，线性方程**A***x*=*0*有非零解的充要条件是系数矩阵**A**的秩rank(**A**)<n。  
当b≠0时，线性方程**A***x*=*b*解存在的充要条件是，系数矩阵的秩与增广矩阵的秩相等，即rank(**A**)=rank(**A**,*b*)。

#### 2
高斯分布，又称正态分布，其概念最早由德国的数学家和天文学家Abraham de Moivre于1733年首次提出的，但由于德国数学家Gauss率先将其应用于天文学研究，故正态分布又叫高斯分布。  
一维形式：  
若随机变量<a href="https://www.codecogs.com/eqnedit.php?latex=\chi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\chi" title="\chi" /></a>服从一个数学期望为<a href="https://www.codecogs.com/eqnedit.php?latex=\mu" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mu" title="\mu" /></a>，方差为 <a href="https://www.codecogs.com/eqnedit.php?latex=\sigma^2" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sigma^2" title="\sigma^2" /></a> 的高斯分布，记为： 

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=X$\sim$N(\mu,\sigma^2)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?X$\sim$N(\mu,\sigma^2)" title="X$\sim$N(\mu,\sigma^2)" /></a>
</p>  

则其概率密度函数为：  

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=N(x|\mu,\sigma^2)=\frac{1}{\sigma\sqrt{2\pi}}exp\{-\frac{(x-\mu)^2}{2\sigma^2}\}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?N(x|\mu,\sigma^2)=\frac{1}{\sigma\sqrt{2\pi}}exp\{-\frac{(x-\mu)^2}{2\sigma^2}\}" title="N(x|\mu,\sigma^2)=\frac{1}{\sigma\sqrt{2\pi}}exp\{-\frac{(x-\mu)^2}{2\sigma^2}\}" /></a>
</p>  

高维形式:  
若D维随机变量<a href="https://www.codecogs.com/eqnedit.php?latex=\vec{\chi}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\vec{\chi}" title="\vec{\chi}" /></a>服从一个数学期望为<a href="https://www.codecogs.com/eqnedit.php?latex=\vec{\mu}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\vec{\mu}" title="\vec{\mu}" /></a>，协方差矩阵为 <a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{\Sigma}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{\Sigma}" title="\mathbf{\Sigma}" /></a> 的高斯分布，则其概率密度函数为：
<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=N(\vec{x}|\vec{\mu},\mathbf{\Sigma})=\frac{1}{(2\pi)^{D/2}}\frac{1}{\left&space;|&space;\mathbf{\Sigma}&space;\right&space;|^{1/2}}exp\{-\frac{1}{2}(\vec{x}-\vec{\mu})^T\mathbf{\Sigma}^{-1}(\vec{x}-\vec{\mu})\}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?N(\vec{x}|\vec{\mu},\mathbf{\Sigma})=\frac{1}{(2\pi)^{D/2}}\frac{1}{\left&space;|&space;\mathbf{\Sigma}&space;\right&space;|^{1/2}}exp\{-\frac{1}{2}(\vec{x}-\vec{\mu})^T\mathbf{\Sigma}^{-1}(\vec{x}-\vec{\mu})\}" title="N(\vec{x}|\vec{\mu},\mathbf{\Sigma})=\frac{1}{(2\pi)^{D/2}}\frac{1}{\left | \mathbf{\Sigma} \right |^{1/2}}exp\{-\frac{1}{2}(\vec{x}-\vec{\mu})^T\mathbf{\Sigma}^{-1}(\vec{x}-\vec{\mu})\}" /></a>
</p>  

具体推导过程请参阅<https://zhuanlan.zhihu.com/p/36522776>。  

从数学上可以证明，在自然界与生产中，一些现象受到许多相互独立的随机因素的影响，如果每个因素所产生的影响都很微小时，总的影响可以看作是服从正态分布的。
