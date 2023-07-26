<font size=10><center>CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior</center></font>

### <center>CVPR 2023</center>  

<p><center><a href="https://doubiiu.github.io" title="超链接title">Jinbo Xing</a><sup>1</sup>, Menghan Xia<sup>2</sup>, Yuechen Zhang<sup>1</sup>, Xiaodong Cun<sup>2</sup>, Jue Wang<sup>2</sup>, Tien-Tsin Wong<sup>1</sup></center><br>
<center><sup>1</sup>The Chinese University of Hong Kong, <sup>2</sup>Tencent AI Lab </center></p>
 
  
## Abstract
<font size=3>Speech-driven 3D facial animation has been widely studied, yet there is still a gap to achieving realism and vividness due to the highly ill-posed nature and scarcity of audio-visual data. </font>



## Method
### Discrete Motion Prior Learning
<font size=3>CodeTalker first learns a discrete context-rich facial motion codebook by self-reconstruction learning over real facial motions.</font>   

![](codebook.png)     
<center><iframe height=480 width=480 src="May1.mp4"></iframe></center>

<html>
<head>
    <title>Elliptical Border Example</title>
    <style>
        /* CSS样式定义 */
        .elliptical-border {
            width: 30px; /* 设置元素宽度 */
            height: 20px; /* 设置元素高度 */
            border-top: 2px solid black; /* 设置上边框样式，2像素宽，黑色 */
            border-bottom: 2px solid black; /* 设置下边框样式，2像素宽，黑色 */
            border-left: 20px solid black; /* 设置左边框样式，20像素宽，黑色（可根据需要调整宽度） */
            border-right: 20px solid black; /* 设置右边框样式，20像素宽，黑色（可根据需要调整宽度） */
            border-radius: 50px; /* 设置圆角半径，实现半圆形效果（可根据需要调整半径大小） */
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            color: white; /* 设置文字颜色为白色 */
            font-weight: bold;
            font-size: 18px;
            background-color: black
        }
        .elliptical-border:hover {
            background-color: black; 
            }
    </style>
</head>
<body>
    <a href="www.baidu.com" class="elliptical-border">
        Video
    </a >
</body>
</html>



