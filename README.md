# easyUtil_rollingNums_clock
  动态时钟:<br/>
  数字翻动效果;<br/>
  引入css和js,其中js支持模块化引入;<br/>
  如普通引入则利用easy_Clock.create("容器id",{height : 时钟高度（Number） ,color: 字体颜色（String）,bgColor : 背景颜色（String）})激活;<br/>
  其中{height : 时钟高度（Number） ,color: 字体颜色（String）,bgColor : 背景颜色（String）}为可选参数，默认高度25px，黑色字体白色背景;<br/>
  模块化则利用引入名称调用create()方法启用。
  # easyUtil_poped
  动态时钟
<h3>简介</h3>
		<h4>&emsp;&emsp;js实现动态时钟，具有数字翻动效果，可自定义颜色和大小，引入css和js即可</h4>
		<h4>&emsp;&emsp;支持模块化引用</h4>
		<h3>API:</h3>
		<h3>入口</h3>
		<ul>
			<li>普通调用全局引用名称为easy_Clock，模块化可自定义名称</li>
		</ul>
		<h3>具体方法及参数（以普通调用名称为例）</h3>
		<ul>
			<li>
				以如下方法初始化即可：
				&emsp;&emsp;easy_Clock.create("容器id",<br/>
				&emsp;&emsp;&emsp;&emsp;{height : 时钟高度（Number）,<br/>
				&emsp;&emsp;&emsp;&emsp;color: 字体颜色（String）,<br/>
				&emsp;&emsp;&emsp;&emsp;bgColor : 背景颜色（String）}<br/>
				);<br/>
				其中：{height : 时钟高度（Number） ,color: 字体颜色（String）,bgColor : 背景颜色（String）}<br/>为可选参数，默认高度25px，黑色字体，白色背景<br/>
			</li>
		</ul>
		<h4>兼容性：自测IE10+,FF,Chrome及其他浏览器兼容（IE10以下未测试）</h4>
