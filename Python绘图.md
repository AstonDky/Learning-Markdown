# Matplotlib 库
## 多子图的绘制
### 1.subplot()函数
#### 用法 : subplot(a,b,c)  
1. a,b : 行和列
2. c : 子图的编号
______
### 2.add_subplot()函数
#### 用法 : 先生成figure()对象,在对象的基础上添加子图

        fig = plt.figure()
        ax1 = fig.sdd_subplot(212)
        ax2 = fig.add_subplot(221)
-----
### 3.subplots()函数
#### 用法 : subplots(nrows , ncols, sharex, sharey)  
#### subplots_adjust(left=None, bottom=None, right=None, top=None, wspace=None, hspace=None)

1. nrows,ncols 表示绘制子图的行数和列数 
2. sharex, sharey 表示是否共享 X&Y 轴
3. * left	子区左边的位置，默认为 0.125，以画布figure为参考系
   * right	子区右边的位置 ，默认为 0.9，以画布figure为参考系
   * bottom	子区底边的位置，默认为 0.11，以画布figure为参考系
   * top 子区顶边的位置，默认为 0.88，以画布figure为参考系
   * wspace	子区之间的空白宽度，默认为 0.2，以绘图区的平均宽度为参考
   * hspace	子区之间的空白高度，默认为 0.2，以绘图区的平均宽度为参考

   
------
### 4.axes()
#### 用法 : 
1. 主要是为当前figure()画布对象添加axes()坐标图形对象
2. 提供rect参数(一个四元组:left,bottom,width,height)
3. 对当前画布对象中的坐标图形对象添加颜色和大小映射,或者在已有的axes对象上添加另一个axes对象

```python

```
-----

### https://blog.csdn.net/tore007/article/details/125816264