
最近在研究图像出来这一块，网上查的比较多，试过基础的opencv 的抠图，效果不是很理想

opencv抠图参考

https://blog.csdn.net/hardWork_yulu/article/details/78757665
https://blog.csdn.net/u010302327/article/details/78898781


试了很多，最终找到一个还不错哦的，基本能完成自己想要的效果，那就是这个开源的modnet算法，
基于PaddleSeg的MODNet算法实现人像抠图，但是一些复杂的图片还是不行，也花了很多时间，所以来分析一哈。

分享案例可以选择相册或者直接拍照体验哈


效果图看博客

https://blog.csdn.net/DickyQie/article/details/123554666

##功能：

1.在人像抠图Demo中，默认会载入一张人像图像，并会在图像下方给出CPU的预测结果和预测时延；
2.在人像抠图Demo中，你还可以通过右上角的"打开本地相册"和"打开摄像头拍照"按钮分别从相册或相机中加载测试图像然后进行预测推理；

PC端版本体验：（点击地址，上传 图片体验）

https://sight-x.cn/portrait_matting/

如何使用，参考官网文档，下载sdk配置即可

参考地址：

https://www.paddlepaddle.org.cn/

https://github.com/PaddlePaddle/PaddleSeg





