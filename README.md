# flexbox
理解flexbox

flexbox布局模式为布局、对齐、容器内的子项提供了更加高效的展示方式。给指定的容器提供修改其子项的宽、高乃至顺序的能力。并且足够完美的去填充可用的空间。适用于各种各样的显示设备及屏幕大小。

**备注：** flexbox适用于应用程序的组件和小规模的布局，而网格布局更适合于大规模的布局。

+（new）意味着已成为规范的新语法（比如：display:flex;）
+（tweener）意味着是来自2011年一种临时的非官方的语法（display:flexbox;）
+（old）意味着来自2009年的老语法（display:box 

**期望：**

*在任何流动的方向上(包括上下左右)都能进行良好的布局
*可以以逆序或以任意顺序进行布局
*可以线性的沿着主轴一字排列或沿着侧轴换行排列
*可以弹性的在任意容器中伸缩大小
*可以使子元素们沿着主轴方向上或沿着侧轴方向上进行对齐
*可以动态的沿着主轴方向 伸缩子集的尺寸，于此同时保证父级侧轴方向上的尺寸 

**属性：**

*display:flex
*flex-direction
*flex-wrap
*justify-content
*align-items
*align-content
*flex-grow
*flex-shrink
*flex-basis
*flex: 1 1 0/auto
*margin: auto 

**DEMO：**

*基本使用，各个属性的介绍使用
*垂直居中的使用
*页面里的使用
