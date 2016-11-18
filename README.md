# canvas基础
## canvas标签说明
1. 属性 width height 用来指定canvas画布大小
2. canvas画布默认大小为300*150，宽高不能设置在css样式中

## javascript控制
1. 获得canvas对象  
    document.getElementsByTagName("canvas")[0]  
2. 获得canvas的2d对象
3. 进行各种2d图形的操作

## 对于canvas图形图像的修饰
1. 对于填充的样式的修饰
  1.1 fillstyle
  1.2 createLinearGradient
  1.3 addColorStop
  1.4 createRadialGradient(r1,x1,y1,r2,x2,y2)
  1.5 createPattern（imgobj，repeat|repeat-x|repeat-y）
2. 对于线条的修饰
  2.1 lineWidth
  2.2 strokeStyle
  
3. 投影的设置
  3.1 分别用四个属性来设置投影的颜色、模糊级别、x，y的偏移量
  3.2 **shadowColor**
  
4. 注意
  4.1 canvas里面的颜色的设置    `可以用四种方式分别为关键字、16进制、rgb、rgba`
  4.2 canvas坐标系统
  4.3 