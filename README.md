  # easyUtil_rollingNums_clock
  动态时钟及翻动效果的数字牌
<h3>总述</h3> 
<h4>&emsp;&emsp;纯js实现的两个功能插件，共用同一个rollingStyle.css样式，rollingClock为时钟的js，rollingNums为数字牌的js，均支持某块化引用</h4>
<h4>&emsp;&emsp;兼容性：自测IE10+,FF,Chrome及其他浏览器兼容（IE10以下未测试）</h4>
<h3>一、动态时钟简介</h3>
		<h4>&emsp;&emsp;动态时钟，具有数字翻动效果，可自定义颜色和大小</h4>
		<h4>&emsp;&emsp;支持模块化引用</h4>
		<h3>API:</h3>
		<h3>入口</h3>
		<ul>
			<li>普通调用全局引用名称为easy_Clock，模块化可自定义名称</li>
		</ul>
		<h3>具体方法及参数（以普通调用名称为例）</h3>
		<ul>
			<li>
				以如下方法初始化即可：<br/>
				&emsp;&emsp;easy_Clock.create("容器id"（String）,<br/>
				&emsp;&emsp;&emsp;&emsp;{height : 时钟高度（Number）,<br/>
				&emsp;&emsp;&emsp;&emsp;color: 字体颜色（String）,<br/>
				&emsp;&emsp;&emsp;&emsp;bgColor : 背景颜色（String）}<br/>
				&emsp;&emsp;);<br/>
			</li>
			<li>
				其中：容器id为必填参数；<br/>{height : 时钟高度（Number） ,color: 字体颜色（String）,bgColor : 背景颜色（String）}<br/>为可选参数，默认高度25px，黑色字体，白色背景<br/>
			</li>
		</ul>
<h3>二、翻动效果的数字牌简介</h3>
		<h4>
		<h4>&emsp;&emsp;翻动效果的数字牌，可自定义颜色，大小和边框</h4>
		<h4>&emsp;&emsp;支持模块化引用</h4>
		<h3>API:</h3>
		<h3>入口</h3>
		<ul>
			<li>普通调用全局引用名称为easy_RollNums，模块化可自定义名称</li>
		</ul>
		<h3>具体方法及参数（以普通调用名称为例）</h3>
		<ul>
			<li>
				以如下方法初始化即可：<br/>
				&emsp;&emsp;easy_RollNums.create("容器id"（String）,num(Number),<br/>
				&emsp;&emsp;&emsp;&emsp;{height : 数字牌高度（Number）,<br/>
				&emsp;&emsp;&emsp;&emsp;color: 字体颜色（String）,<br/>
				&emsp;&emsp;&emsp;&emsp;bgColor : 背景颜色（String）,<br/>
				&emsp;&emsp;&emsp;&emsp;borderColor : 边框颜色（String）}<br/>
				&emsp;&emsp;);<br/>
			</li>
			<li>
				其中：容器id和num为必填参数，num必须为number类型；<br/>
				{height : 数字牌高度（Number） ,color: 字体颜色（String）,bgColor : 背景颜色（String）,borderColor :边框颜色（String） }<br/>为可选参数，默认高度25px，黑色字体，白色背景，白色边框<br/>
			</li>
		</ul>
	
