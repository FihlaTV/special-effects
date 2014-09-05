special-effects
=============

收集一些js 特效

effect_1
-------
###demo
![效果]('/effect_1/images/effect_1.png')
###how to use
```javascript
$(function(){
		$('#lrtk').movingBoxes({
			startPanel   : 1,       // 从第一个li开始
			reducedSize  : .5,      // 缩小到原图50%的尺寸
			wrap         : true,   // 无缝循环
			buildNav     : false,	// 显示指示器效果
            initAnimation:true
			//navFormatter : function(){ return "&#9679;"; } // 指示器格式，为空即会显示123
		});
	});
```javascript