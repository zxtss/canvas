html 中设置<canvas id="canvas" width="" height=""></canvas>
var canvas=document.getElementById('canvas');//获取canvas容器
var  ctx=canvas.getContext('2d');创建画布
//绘制矩形:
ctx.fillRect(x,y,width,height);//进行填充
ctx.strokeRect(x,y,width,height);//绘制边框
ctx .clearRect(x,y,width,height);//清除画布
//绘制路径
ctx.beginPath();//新建路径
ctx .moveTo(x,y);//路径起点
