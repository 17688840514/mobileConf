# mobileConf
移动端自使用的基础js和css

#js:根据设计稿  设置你的屏幕宽度  如我的设计稿是750的   那么下面就是 7.5
document.documentElement.style.fontSize = document.documentElement.clientWidth / 7.5 + 'px';

#css:
*{
	margin: 0;
	padding: 0;
	box-sizing:border-box;
	-moz-box-sizing:border-box;
}
html{
	font-size: 100px;
	background-color: #fff;
}
/*清除浮动代码*/
.clearfix {
	zoom: 1;
}

.clearfix:after {
	content: '';
	display: block;
	clear: both;
}
body{
	width: 100%;
}
