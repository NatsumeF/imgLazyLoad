# imgLazyLoad
//javaScript 插件 图片懒加载
项目引入imgLzayLoad文件；
  
  需要延迟加载的dom添加data-src属性；
  例：<img src="load.png" data-src="my-img.jpg"/>
  
 调用new ImgLazyLoad(doms,time,height);
 
 //doms：为需要懒加载的dom集合推荐document.querySelectorAll（"xx"）;
 
 //time：延迟多久加载；默认1000ms
 
 //height:距离多少高度开始触发加载；默认200px
 
  例：new ImgLazyLoad（dom,500,100）;
  
  
  欢迎issues；欢迎使用；
  
  554096147@qq.com || llandpp11@gmail.com
