# carouselMmap
js简单实现轮播图效果
打开主页即可查看效果；

使用：

    1，先导入js文件，animate.js、carousel.js和style样式（样式在页面里）;

    2,页面结构为：

<div>
   <img></img>
   <img></img>
   <ul>
     <li></li>
   </ul>
</div>

    解释：最外边的div是轮播图外框，它的作用是控制轮播图单个图片显示的大小；

两个img为轮播图左右两个点击按钮；ul里面包含的就是图片了，每个li包含一张图片；
   
    3，使用时调用Carousel（parameter1，parameter2，parameter3）
    解释：parameter1为div的类名，
    parameter2为左点击按钮的类名，
    parameter3为右点击按钮的类名，
    参数必须为字符串，所以得用‘’包裹。
