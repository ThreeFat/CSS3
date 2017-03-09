##	CSS3选择器 
	属性选择器 语法 [] 查找条件是以“属性”做为查找条件，并且我们还可以
	通过属性值来查找 [^=] [$=] [*=] [=] [attr]

	伪类选择器 语法 : E:first-child :last-child :nth-child(n) 
	dl
		dt
		dd 
	dd:nth-child(1)

	n 可以是一个表达式 y = an + b, n 的取值n=0, 1, 2 ...

	伪元素选择器 语法 :: 

	E::before E::after 必须要指定一个 content: '' 新添加的无素是一个行内元素
	根据自已需要 display

	:before :after 尽量使用 :after :before

##	文字阴影 
	`text-shadow: 2px 2px 5px red; `

##	边框 border
	边框圆角 border-radius: 10px 10px 10px 10px / 10px 10px 10px 10px;
	简写方式
	border-radius: 10px 10px 10px 10px; 水平半径和垂直半径相等
	border-radius: 10px;
	border-radius: 10px 20px;  对角线
	border-radius: 10px 20px 30px; 

	边框阴影
	box-shadow: 2px 2px 5px blue;
	box-shadow: inset 2px 2px 5px blue; 内阴影
	box-shadow: 2px 2px 5px blue, 2px 2px 8px pink;

	边框图片
	border-image-source: url();
	border-image-slice: 27 27 27 27; 
	border-image-repeat: round stretch repeat;
	border-image-width: 30px;

##	盒模型

	盒子大小 = content + padding + border

	CSS3可以改变这种计算方式

	当设置box-sizing: border-box;
	盒子大小 = width (CSS里设置的width)

	当设置 box-sizing: content-box;
	盒子大小 = content + padding + border





