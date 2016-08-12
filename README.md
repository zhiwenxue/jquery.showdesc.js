<h1>jquery.showdesc.js</h1><h3>0.01</h3>

鼠标浮动 显示扩展信息插件

![image](https://github.com/zhiwenxue/jquery.showdesc.js/blob/master/screenshots/image1.png?raw=true)

鼠标移动上可显示信息，如图
<h3>示例代码</h3>
```
$("#tesct_div").descshow({
			height:100,width:100, 
			borderColor:'gray',
			borderWidth:2,
			backgroundColor:'white',
			arrowLenght:10,
			content:'',
			direction:null,
			appendContext:function(event){
				event.append("<h1>一个不错的插件</h1>")
			}

		});
```
<h3>字段</h3>
*  height ：提示框宽度

*  width  ：提示框高度

*  borderColor：边框背景颜色
*  borderWidth：边框宽度
*  backgroundColor：背景颜色
*  arrowLenght：小箭头边长
*  content：内容（直接加载）
*  direction:null：提示框朝向（top，bottom，left，right）
*  appendContext：回调函数，当提示框出现调用
