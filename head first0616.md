#《head first Html and Css》学习笔记#---2016.6.16
##字体系列##

* sans-serif Family：没有称线的字体。在电脑屏幕上这些字体要比serif更具可读性  
  Verdana / Arial Black / Trebuchet MS / Arial / Geneva  
* Serif Family:有称线的字体，一般用于报纸印刷  
  Times / Times New Roman / Georgia
* Monospace Family:字母具有相同的宽度，主要用来显示软件代码实例  
  Courier / Courier New / Andale Mono
* Cursive Family:像是手写的字体，有时候用于标题  
  Comic Sans/ Apple Chancery
* Fantasy Family:一些有固定装饰的字体，这些字体并不多见，在规范的web设计中也不常用  
  LAST/NINJA/Impact  

**css中定义字体系列**    

    body{  
         font-family: Verdana, Geneva, Arial, sans-serif  
        }  
依次查找各个字体，如果找到，直接使用，如果未找到，就用浏览器默认的某个“sans-serif”字体

**Windows和Mac中通用的字体**  

    Andale Mono * Arial * Arial Black * Comic Sans * Courier New * Georgia  
    Impact * Times New Roman * Trebuchet MS * Verdana

##字体大小##

**不要用像素指定网页文字的大小，因为有些浏览器不支持用像素调整自己，且降低了网页的通用性**

几种定义字体大小的方法：px,em,百分数和关键字。  到底使用哪一种好呢？有个小技巧，使字体大小在大多浏览器中显示一致。  

    * 选择一种关键字（推荐使用small或medium）定义body字体大小，也就是网页的默认字体大小
    * 用em或百分数把别的元素的字体大小制定为相对于body字体大小的字体尺寸（选em还是百分数都无所谓，效果是一样的）  
举个例子：  
    
    body{font-size:small;}
    h1 {font-size: 150%;}
    h2 {fong-size: 120%;}

浏览器默认的字体一般是16px，如果用small一般是12px  

**各个默认标题字体大小是多大**
具体来说，取决于浏览器，但是一般来说，如下：  

    <h1>是默认body大小的200%  
    <h2>..............150%  
    <h3>..............120%  
    <h4>和body一样大  
    <h5>和<h6>要更小一些

##字体粗细##
font-weight属性用来控制字体的粗细 
 
    font-weight:bold;
    font-weight:normal;
    font-style:italic; //设置为斜体

##字体修饰##

    em{
        text-decoration: line-through;
      }  //元素<em>的文本中央有线穿过

    em{
        text-decoration: underline overline;
      } //元素<em>既有下划线又有中间线穿过

    em{
        text-decoration:none;
      } //文本没有修饰

##Web颜色是如何工作的##
名称：规定的只有17中  
数值：rgb 6位  #CCFF02 十六进制  
几种提供颜色数值的方式：  
     * 使用PS查看目标颜色的数值
     * 使用在线颜色表 
      
##段落添加样式##
**给段落块补白**
给段落内容与段落边缘中间的距离添加

    padding：25px;

**给段落添加边界**
在内容border的外界添加空白间隔

    margin:30px;

**给段落设置背景图片**

    background-image: url(images/background.gif);
    background-repeat: no-repeat;  //不想让背景图像重复
    background-position:top left; //想把它放左上角
 









