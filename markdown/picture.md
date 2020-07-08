-------------------------------------------------**图片**--------------------------------------------

一、行内式

![图片1](./image/img1.jpg "Optional title")
![图片2](https://github.com/xiarainla/document/blob/master/markdown/image/img1.jpg)

二、参考式

![图片3][id]
[id]: ./image/img2.jpg

三、修改图片大小
到目前为止， Markdown 还没有办法指定图片的宽高，如果你需要的话，你可以使用普通的 `<img>` 标签。
直接以MarkDown插入图片的方法，图片就会靠在左侧，大小也不由自己决定：
<img src="https://github.com/xiarainla/document/blob/master/markdown/image/img1.jpg.jpg"/>

# 固定图片显示大小：
# <img src="https://github.com/xiarainla/document/blob/master/markdown/image/img1.jpg" width=256 height=256 />

根据一定比例显示
<img src="https://github.com/xiarainla/document/blob/master/markdown/image/img1.jpg" width="50%" height="50%" />

给图像加个标注
<center>
<img src="https://github.com/xiarainla/document/blob/master/markdown/image/img1.jpg.jpg" width="25%" height="25%" />
Figure 1. Lena
</center>

<center>
<img src="https://github.com/xiarainla/document/blob/master/markdown/image/img1.jpg" />
Figure 2. Lena
</center>

