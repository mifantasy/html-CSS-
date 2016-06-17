#《head first Html and Css》学习笔记#---2016.6.17
##边框修饰##

    border-style:groove；  //solid(实线)，double(两条线)，dotted(点)，dashed(围绕边框的虚线)
    border-width:thin;    //thin medium thick (5px)
    border-color:red;    //rgb(100%,0%,0%) ; #ff0000
    border-top-color:20px //定义边框的一侧
    border-right-style:
    border-left-width:

##class和id的区别##
class:将一种样式应用到**多个元素**的情况下，使用类比较合适。  
id：唯一元素的命名标识。需要将样式只应用到一个元素且页面上只有一个这个元素。  
   **页面中的标题、页脚和导航条都在页面中具有唯一性**  

##div##
  用来把页面分割成逻辑部分或者组。  
  把一些元素放进<div>里面了，就表明它们属于同一组，同时用Id属性为其提供一个唯一的标签  
  **div可以认为是一个容器**

##那些缩写##
  **边界，补白或者border**

    margin:0px 20px  //上和下，左和右
    border:thin solid #007e7e //width,style,color
    background: white url(images/cocktail.gif) repeat-x //颜色，图片地址，重复模式
    font:font-style font-variant font-weight font-size/line-height font-family //1.2.3可以任意组合，  
                                  但是一定要再size之前，字体系列之间要加逗号，添加字体系列强烈建议两种以上  
    font:small/1.6em Verdana,Helvetica,Arial, sans-serif;

##根据状态样式化链接##

    a:link{
       color:green;
      }     //选择符选择的是未被访问的链接

    a:visited{
      color:red;
      }    //选择符选择的是已被访问的链接

    a:hover{
      color: yellow;
     }    //选择符选择鼠标停留在上面的链接





