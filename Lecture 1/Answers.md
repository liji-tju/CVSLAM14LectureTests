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

#### 3
C++ 在 C 语言的基础上增加了面向对象的编程，C++ 支持面向对象的程序设计。类是 C++ 的核心特性，通常被称为用户定义的类型。

类用于指定对象的形式，它包含了数据表示法和用于处理数据的方法。类中的数据和方法称为类的成员。

定义一个类，本质上是定义一个数据类型的蓝图。这实际上并没有定义任何数据，但它定义了类的名称意味着什么，也就是说，它定义了类的对象包括了什么，以及可以在这个对象上执行哪些操作。

类定义是以关键字 class 开头，后跟类的名称。类的主体包含在一对花括号中。类定义后必须跟着一个分号或一个声明列表。例如，我们使用关键字 class 定义 Box 数据类型，如下所示：

'''c++
class Box
{
   public:
   double length;   // Length of a box
   double breadth;  // Breadth of a box
   double height;   // Height of a box
};
'''
关键字 public 确定了类成员的访问属性为公共的。在类对象作用域内，公共成员在类的外部是可访问的。您也可以指定类的成员为 private或 protected。

