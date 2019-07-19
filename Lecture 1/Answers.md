#### 1
利用系数矩阵**A**与向量<a href="https://www.codecogs.com/eqnedit.php?latex=\vec{b}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\vec{b}" title="\vec{b}" /></a>组成增广矩阵<a href="https://www.codecogs.com/eqnedit.php?latex=\left&space;[&space;\mathbf{A},\vec{b}&space;\right&space;]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\left&space;[&space;\mathbf{A},\vec{b}&space;\right&space;]" title="\left [ \mathbf{A},\vec{b} \right ]" /></a>,再将其划为简化行阶梯形（rref），即可得到线性方程<a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{A}\vec{x}=\vec{b}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{A}\vec{x}=\vec{b}" title="\mathbf{A}\vec{x}=\vec{b}" /></a>的解。  
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

```c++
class Box
{
   public:
   double length;   // Length of a box
   double breadth;  // Breadth of a box
   double height;   // Height of a box
};
```
关键字 public 确定了类成员的访问属性为公共的。在类对象作用域内，公共成员在类的外部是可访问的。您也可以指定类的成员为 private或 protected。

C++ STL（标准模板库）是一套功能强大的 C++ 模板类，提供了通用的模板类和函数，这些模板类和函数可以实现多种流行和常用的算法和数据结构，如向量、链表、队列、栈。
C++ 标准模板库的核心包括以下三个组件：

- 容器：用来管理某一类对象的集合。包括deque,list,vector,map等。
- 算法：作用于容器。提供了执行何种操作的方式，包括对容器内容进行初始化，排序，搜索和转换等操作。 
- 迭代器：用于遍历对象集合的元素。这些集合可能是容器，也可能是容器的子集。

#### 4
QT

#### 5

C++11是自1998年C++首次被ISO标准化以来变化最大的一个新标准，它主要在以下两个方面对C++进行了革命性的改进和增强：  

一方面，C++11让C++更加易于使用。我们都知道，C++以其语法简洁而著称于世，虽然简洁的语法受到编程高手们的喜爱。同时，C++也非常灵活而自由，我们几乎可以在C++中完成任何我们想要完成的事情。简洁、自由和灵活是一把双刃剑，它让C++拥有无限的能力，但同时也让C++在程序员们的心目中成为一门难学难用难以掌握的编程语言，特别是让一些初学者望而却步，阻碍了C++的进一步发展。为了改变这一现状，C++11加入了很多改善其易用性的语法特性，并从其他主流的编程语言（特别是Java）中借鉴吸收了很多旨在改善C++易用性的语法特点。例如，C++11提供了auto这种特殊的数据类型，使用它作为变量的数据类型，编译器可以根据变量的初始值自动推断其合理的真实数据类型，省去了程序员确定复杂变量的数据类型的繁琐；C++11开始支持Lambda表达式，让C++中匿名函数的定义和使用成为可能；C++11从Java和C#中借鉴了序列for循环语句，让针对某个容器的循环遍历更加简单；C++11从Java中借鉴了函数属性，从而可以对函数进行更加灵活的修饰。例如，我们可以使用noreturn指明一个函数没有返回值，也可以使用final限制某个虚函数被派生类重载，函数属性的引入满足了我们对函数的不同需求。  

另一方面，C++11让C++的性能更高。相对于其他主流的高级编程语言而言，接近于低级语言的高性能表现，应该是C++最大的优势了。但是C++11并不满足于C++现有的性能表现，通过增加新的语法特性、改写标准库等手段，想榨干C++身上最后的一滴性能血液。例如，C++11提供了对右值引用、移动语义的完全支持，解决了从函数返回一个大对象的问题；利用新的语法特性对标准库进行了大规模的改写，极大地提高了标准库的性能表现；特别值得一提的是，为了适应当今越来越普及的并行计算，充分利用主流的多核CPU的计算资源，C++11在标准库中对并行计算提供了全面的支持，我们可以通过线程thread对象轻松完成线程的创建，也可以通过条件变量对线程的执行情况进行控制。对并行计算的完全支持，让C++11拥有了更加优异的性能表现。

还有C++98、C++03、C++14和C++17标准。

#### 6

Linux是一套免费使用和自由传播的类Unix操作系统，是一个基于POSIX和UNIX的多用户、多任务、支持多线程和多CPU的操作系统。它能运行主要的UNIX工具软件、应用程序和网络协议。它支持32位和64位硬件。Linux继承了Unix以网络为核心的设计思想，是一个性能稳定的多用户网络操作系统。 Linux操作系统诞生于1991 年10 月5 日（这是第一次正式向外公布时间）。Linux存在着许多不同的Linux版本，但它们都使用了Linux内核。Linux可安装在各种计算机硬件设备中，比如手机、平板电脑、路由器、视频游戏控制台、台式计算机、大型机和超级计算机。 严格来讲，Linux这个词本身只表示Linux内核，但实际上人们已经习惯了用Linux来形容整个基于Linux内核，并且使用GNU 工程各种工具和数据库的操作系统。

#### 7

![text](https://www.runoob.com/wp-content/uploads/2014/06/003vPl7Rty6E8kZRlAEdc690.jpg)

以下是对这些目录的解释：

* /bin：
bin是Binary的缩写, 这个目录存放着最经常使用的命令。

* /boot：
这里存放的是启动Linux时使用的一些核心文件，包括一些连接文件以及镜像文件。

* /dev ：
dev是Device(设备)的缩写, 该目录下存放的是Linux的外部设备，在Linux中访问设备的方式和访问文件的方式是相同的。

* /etc：
这个目录用来存放所有的系统管理所需要的配置文件和子目录。

* /home：
用户的主目录，在Linux中，每个用户都有一个自己的目录，一般该目录名是以用户的账号命名的。

* /lib：
这个目录里存放着系统最基本的动态连接共享库，其作用类似于Windows里的DLL文件。几乎所有的应用程序都需要用到这些共享库。

* /lost+found：
这个目录一般情况下是空的，当系统非法关机后，这里就存放了一些文件。

* /media：
linux系统会自动识别一些设备，例如U盘、光驱等等，当识别后，linux会把识别的设备挂载到这个目录下。

* /mnt：
系统提供该目录是为了让用户临时挂载别的文件系统的，我们可以将光驱挂载在/mnt/上，然后进入该目录就可以查看光驱里的内容了。

* /opt：
 这是给主机额外安装软件所摆放的目录。比如你安装一个ORACLE数据库则就可以放到这个目录下。默认是空的。

* /proc：
这个目录是一个虚拟的目录，它是系统内存的映射，我们可以通过直接访问这个目录来获取系统信息。
这个目录的内容不在硬盘上而是在内存里，我们也可以直接修改里面的某些文件，比如可以通过下面的命令来屏蔽主机的ping命令，使别人无法ping你的机器：
```
echo 1 > /proc/sys/net/ipv4/icmp_echo_ignore_all
```
* /root：
该目录为系统管理员，也称作超级权限者的用户主目录。

* /sbin：
s就是Super User的意思，这里存放的是系统管理员使用的系统管理程序。

* /srv：
 该目录存放一些服务启动之后需要提取的数据。

* /sys：
 这是linux2.6内核的一个很大的变化。该目录下安装了2.6内核中新出现的一个文件系统 sysfs 。

sysfs文件系统集成了下面3种文件系统的信息：针对进程信息的proc文件系统、针对设备的devfs文件系统以及针对伪终端的devpts文件系统。
该文件系统是内核设备树的一个直观反映。

当一个内核对象被创建的时候，对应的文件和目录也在内核对象子系统中被创建。

* /tmp：
这个目录是用来存放一些临时文件的。

* /usr：
 这是一个非常重要的目录，用户的很多应用程序和文件都放在这个目录下，类似于windows下的program files目录。

* /usr/bin：
系统用户使用的应用程序。

* /usr/sbin：
超级用户使用的比较高级的管理程序和系统守护程序。

* /usr/src：
内核源代码默认的放置目录。

* /var：
这个目录中存放着在不断扩充着的东西，我们习惯将那些经常被修改的目录放在这个目录下。包括各种日志文件。

---
ls：用来显示当前目录中的文件和子目录列表。  
cd：可让用户切换当前所在的目录。  
mkdir：可用来创建子目录。  
rmdir：删除子目录。  
cp：可以将文件从一处复制到另一处。  
rm：可以删除文件或目录。  
cat：显示文件的内容，或是将数个文件合并成一个文件。  

#### 8
```
sudo apt-get install "想要安装的软件"
```
Ubuntu软件安装位置，一般都在/usr/bin下，个别可能会安装到/usr/share和/usr/local里。  
只知道模糊的名称，可以通过tab键补足软件全称。  

#### 9

参阅这篇文章<https://www.cnblogs.com/chenlogin/p/6245958.html>。
