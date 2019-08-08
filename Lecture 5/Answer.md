#### 1

#### 2
相机内参矩阵为：<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;f_x&space;&&space;0&space;&&space;c_x\\&space;0&space;&&space;f_y&space;&&space;c_y\\&space;0&space;&&space;0&space;&&space;1&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;f_x&space;&&space;0&space;&&space;c_x\\&space;0&space;&&space;f_y&space;&&space;c_y\\&space;0&space;&&space;0&space;&&space;1&space;\end{bmatrix}" title="\begin{bmatrix} f_x & 0 & c_x\\ 0 & f_y & c_y\\ 0 & 0 & 1 \end{bmatrix}" /></a>，进一步可以写为：<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;\alpha&space;f&space;&&space;0&space;&&space;c_x\\&space;0&space;&&space;\beta&space;f&space;&&space;c_y\\&space;0&space;&&space;0&space;&&space;1&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;\alpha&space;f&space;&&space;0&space;&&space;c_x\\&space;0&space;&&space;\beta&space;f&space;&&space;c_y\\&space;0&space;&&space;0&space;&&space;1&space;\end{bmatrix}" title="\begin{bmatrix} \alpha f & 0 & c_x\\ 0 & \beta f & c_y\\ 0 & 0 & 1 \end{bmatrix}" /></a>。

其中：<a href="https://www.codecogs.com/eqnedit.php?latex=\alpha" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\alpha" title="\alpha" /></a>为像素在u轴上的缩放系数，f为物理成像平面到小孔的距离(焦距)，<a href="https://www.codecogs.com/eqnedit.php?latex=\beta" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\beta" title="\beta" /></a>为像素在v轴上的缩放系数，像素坐标系的坐标原点通常在图像的左上角，<a href="https://www.codecogs.com/eqnedit.php?latex=c_x,c_y" target="_blank"><img src="https://latex.codecogs.com/gif.latex?c_x,c_y" title="c_x,c_y" /></a>为成像平面原点到像素坐标系原点的平移。

相机分辨率变为原来的两倍，即像素点密度提升为原来的两倍，所以<a href="https://www.codecogs.com/eqnedit.php?latex=\alpha,\beta,c_x,c_y" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\alpha,\beta,c_x,c_y" title="\alpha,\beta,c_x,c_y" /></a>均变为原来的两倍。

#### 3

#### 4

卷帘式快门是逐行顺序曝光，所以不适合快速运动物体的拍摄，会出现所谓的[果冻效应](https://baike.baidu.com/item/%E6%9E%9C%E5%86%BB%E6%95%88%E5%BA%94)。<>

