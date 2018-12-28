## 这是一个网页

You can use the [editor on GitHub](https://github.com/Baxlumen/myH5/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.




## 这是一个头像图


<!DOCTYPE html>
<html>
<meta charset="utf-8">
<head>
	<title>图片</title>
	<style type="text/css">
		canvas{border: 1px solid black;
		background-color: rgb(232,255,61);
		}
	</style>
	<script type="text/javascript">  
          function windowTocanvas(canvas, x, y) {  
                var bbox = canvas.getBoundingClientRect();  
                return {  
                    x: x - bbox.left * (canvas.width / bbox.width),   
                    y: y - bbox.top * (canvas.height / bbox.height)  
                };  
  
            }  
         window.onload=function(){  
            var canvas=document.getElementById("myCanvas");  
              
            canvas.onclick=function(event){  
                  
                var loc=windowTocanvas(canvas,event.clientX,event.clientY)  
                var x=parseInt(loc.x);  
                var y=parseInt(loc.y);  
                document.getElementById("input_window").value=event.clientX+"--"+event.clientY;  
                document.getElementById("input_canvas").value=x+"--"+y;  
            }  
        }  
              
        </script>  
</head>
<body>
<canvas id="myCanvas">your browser does not support the canvas</canvas>

<script type="text/javascript">
	var canvas=document.getElementById('myCanvas');
	canvas.width=780;
	canvas.height=660;
	var ctx=canvas.getContext('2d');
	/*ctx.fillStyle='#ffe1ff'; 头
	ctx.fillRect(0,0,80,100);  矩形*/	
	ctx.beginPath();
	ctx.arc(390,170,152,1*Math.PI,0);	
	ctx.closePath();
	ctx.fillStyle='rgb(238,225,255)';
	ctx.fill();
	/*脖子*/
    ctx.fillStyle='rgb(248,176,177)';
	ctx.fillRect(373,300,38,90);/*455,66*/
	/*阴影处*/
    ctx.beginPath();
    ctx.moveTo(374,344);
    ctx.lineTo(352,310);
    ctx.lineTo(373,300);
    ctx.closePath();
    ctx.fillStyle='rgb(198,198,198)';
    ctx.fill();
    ctx.beginPath();
    ctx.moveTo(406,344);
    ctx.lineTo(428,310);
    ctx.lineTo(407,300);
    ctx.closePath();
    ctx.fillStyle='rgb(198,198,198)';
    ctx.fill();
	
/*脸*/
    ctx.beginPath();
	ctx.arc(390,170,145,0,1*Math.PI);	
	ctx.closePath();
	ctx.fillStyle='rgb(255,239,232)';
	ctx.fill();
/*马尾*/
	ctx.fillStyle='rgb(238,225,255)';
	ctx.fillRect(218,112,35,367); 
	
	ctx.fillStyle='rgb(190,147,255)';
	ctx.fillRect(230,169,30,310); 

    ctx.fillStyle='rgb(238,225,255)';
	ctx.fillRect(530,112,35,367); 
    ctx.fillStyle='rgb(190,147,255)';
	ctx.fillRect(518,169,30,310);

/*鬓角*/
    ctx.beginPath();
	ctx.arc(390,170,152,0.8*Math.PI,1.25*Math.PI);	
	ctx.closePath();
	ctx.fillStyle='rgb(238,225,255)';
	ctx.fill();

    ctx.beginPath();
	ctx.arc(390,170,152,1.75*Math.PI,0.2*Math.PI);	
	ctx.closePath();
	ctx.fillStyle='rgb(238,225,255)';
	ctx.fill();
  /*眼睛*/
    ctx.fillStyle='rgb(128,37,166)';
	ctx.fillRect(335,181,15,25); 
	ctx.fillStyle='rgb(151,78,183)'; 
	ctx.fillRect(335,206,15,25);
	ctx.fillStyle='rgb(128,37,166)';
	ctx.fillRect(431,181,15,25); 
	ctx.fillStyle='rgb(151,78,183)'; 
	ctx.fillRect(431,206,15,25);      
	/*脸颊*/
	ctx.beginPath();
    ctx.ellipse(300, 242, 8, 26,0.5*Math.PI, 0, 2*Math.PI, true);//radiusX:x方向上半径,radiusY：x方向上半径,0.5:rotation：旋转角度
    ctx.closePath();
    ctx.fillStyle='rgb(255,205,206)';
    ctx.fill();

    ctx.beginPath();
    ctx.ellipse(480, 242, 8, 26,0.5*Math.PI, 0, 2*Math.PI, true);//radiusX:x方向上半径,radiusY：x方向上半径,0.5:rotation：旋转角度
    ctx.closePath();
    ctx.fillStyle='rgb(255,205,206)';
    ctx.fill();
/*发卡*/

	/*身体*/
	ctx.fillStyle='rgb(128,37,166)';
	ctx.fillRect(275,344,230,135);
    /*接脖子*/
    ctx.beginPath();
    ctx.moveTo(390,369);
    ctx.lineTo(374,344);
    ctx.lineTo(406,344);
    ctx.closePath();
    ctx.fillStyle='rgb(248,176,177)';
    ctx.fill();
	/*衣领*/
	ctx.beginPath();
    ctx.moveTo(352,310);
    ctx.lineTo(325,402);
    ctx.lineTo(343,394);
    ctx.lineTo(375,479);
    ctx.lineTo(405,479);
    ctx.lineTo(437,394);
    ctx.lineTo(455,402);
    ctx.lineTo(428,310);
    ctx.lineTo(390,369);
    ctx.closePath();
    ctx.fillStyle="white";
    ctx.fill();
    /*衣扣*/ 
    ctx.beginPath();  
    ctx.moveTo(390,369);
    ctx.lineTo(390,473);
    ctx.strokeStyle ='rgb(230,220,231)';
    ctx.closePath();
    ctx.stroke();
	/*领结*/
	ctx.beginPath();  
    ctx.moveTo(385,380);
    ctx.lineTo(385,390);
    ctx.lineTo(360,419);
    ctx.lineTo(375,439);
    ctx.lineTo(385,409);
    ctx.lineTo(380,469);
    ctx.lineTo(385,469);

    ctx.lineTo(390,439);

    ctx.lineTo(395,469);
    ctx.lineTo(400,469);
    ctx.lineTo(395,409);
    ctx.lineTo(405,439);
    ctx.lineTo(420,419);
    ctx.lineTo(395,390);
    ctx.lineTo(395,380);
    ctx.closePath();
    ctx.fillStyle='rgb(251,177,254)';
    ctx.fill();
   /*中间镂空*/
    ctx.beginPath();  
    ctx.moveTo(385,395);
	ctx.lineTo(368,419);
	ctx.lineTo(375,430);
	ctx.lineTo(385,400);    
    ctx.closePath();
    ctx.fillStyle="white";
    ctx.fill();

    ctx.beginPath();
    ctx.moveTo(395,395);
    ctx.lineTo(412,419);
    ctx.lineTo(405,430);
    ctx.lineTo(395,400); 
    ctx.closePath();
    ctx.fillStyle="white";
    ctx.fill();
    /*肩*/
    ctx.beginPath();
    ctx.moveTo(342,344);
    ctx.lineTo(331,344);
    ctx.lineTo(345,334);
    ctx.closePath();
    ctx.fillStyle='rgb(128,37,166)';
    ctx.fill();

    ctx.beginPath();
    ctx.moveTo(438,344);
    ctx.lineTo(449,344);
    ctx.lineTo(435,334);
    ctx.closePath();
    ctx.fillStyle='rgb(128,37,166)';
    ctx.fill();
</script>
<div class="" align="right" style="position: absolute; z-index: 1; top: 30px; right: 100px;">      
          窗口的X，Y值：<input type="text" id="input_window" value="" /> <br />  
          canvas的X，Y值：<input type="text" id="input_canvas" value="" />   
          <p>底部479，中线390</p>
</div>
</body>
</html>






### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Baxlumen/myH5/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
