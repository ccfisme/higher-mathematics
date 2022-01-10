主要参考：https://www.zhihu.com/question/66601481/answer/1942980648

# 为什么dx没办法被约掉

![Screenshot_20220110_011655_com kiwibrowser browse](https://user-images.githubusercontent.com/74129445/148732536-40fcbeaa-31a2-483c-9a66-c67d02d77f1b.jpg)  
![Screenshot_20220110_011655_com kiwibrowser browse](https://user-images.githubusercontent.com/74129445/148732541-9da05d96-2a4b-417d-89a9-6369b9efdc31.jpg)  

  以前在做上面这种链式求导和反函数求导时，会经常认为不能简单的将dx约分的想法是错误的，因为我认为dy/dx * dx，这两个dx是一样的，如果不一样就证明dx分的不一样，会导致原函数出错。  
  
  其实我这样理解错误的根本原因还是没有搞明白导数的公式，**导数不是用微分相除得到的，是用一个微分算子求出来的**。也就是说，那些链式求导，反函数求导等等的dy/dx不是除法，是一个整体d()/dx微分算子，括号里是求导的函数，这相当于一个黑箱，是求导数的，原型是lim那个求导公式。所以说，之前的链式求导和反函数求导不能约分，因为d/dx是一个符号整体，不可能被约掉  
  ![Screenshot_20220110_132307_com zhihu android](https://user-images.githubusercontent.com/74129445/148733295-80907dc3-5a89-49b0-9037-6c4d9eeffbe3.jpg)  
  ![Screenshot_20220110_132313_com zhihu android](https://user-images.githubusercontent.com/74129445/148733343-dce3421d-d0cd-4854-9b38-e8b92eb5a4c5.jpg)  
# 导数与微分的关系  
先有导数，再有微分，即是用导数求出来的微分，怎么求出来的呢？  

![Screenshot_20220110_013056_com kiwibrowser browse](https://user-images.githubusercontent.com/74129445/148733649-f02f53e2-29b8-44ae-ad37-0808d31cafe6.jpg)  

这是微分的图像，由图可知，△y=dy+高阶无穷小，当△x趋近于零时，高阶无穷小为零，△y变成dy。，而dy=导数 * dx，所以可以通过导数求微分。 
那后面算面积不会少一块吗？不会，因为求原函数有dx。这是微元，也就是极限。导数与dx乘积之和会复原出原函数。


# 总结  

导数不是用微分通过除法求得的，是微分算子，也就是lim公式求出来的  
![Screenshot_20220110_115643_com zhihu android](https://user-images.githubusercontent.com/74129445/148734537-1f09a04c-65ab-4d48-a84d-3ec76f473863.jpg)  
