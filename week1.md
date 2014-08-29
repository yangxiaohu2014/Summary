# 杨小湖周总结第1次 #

## 工作总结 ##

1.  工作内容：

    a.  &nbsp;&nbsp;将画廊效果整合到[数说官网](http://shushuo.baidu.com/)   (网站已更新);
    b.	&nbsp;&nbsp;为[wordonline](word.baidu.com) 实现帮助菜单功能 和  字数等统计功能   (网站未更新);
    c.	&nbsp;&nbsp;为[kity](kity.baidu.com) 添加两个demo:  倒映效果 和  动感的饼状图   （网站未更新);

2.  遇到的问题:

	a.  &nbsp;&nbsp;如何提供一个合理的接口是我面临的一个重要的问题。
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在工作a的过程中， 战总和可敬先后提供一些改进的建议。 在当时的情况下， 直接该接口中的参数不能满足要求，需要到代码中改一些细节的代码。反映出的问题就是接口提供不科学，代码可维护性差。因此，查阅了一下《JavaScript编程精解》，了解了一下模块化编程的相关知识，获益匪浅。

	b.  &nbsp;&nbsp;大胆创新敢于实践，突破心理障碍。
	    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在工作b的过程中，在统计段落数的时候，需要统计&lt;p&gt;标签的对数，我的首选的做法是用正则匹配法，但是这种做法会遇到一些不可预测的问题，比如文本中有&lt;p&gt;字符串。 后来，金泉提供的方法是将获取的编辑区中的html字符串append到一个空的div标签中然后获取后代中的&lt;p&gt;, 这不正是我一开始就想到的方法吗！ 当时是觉得这种方法比较诡异，担心耗性能。现在回过头想想，这种方法反而是一个更加简单可靠的方法。

	c.  &nbsp;&nbsp;理清kity.js库的结构和使用方法。
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;说来惭愧，跟了家鸣这么久还没怎么深刻的分析清楚kity.js的来龙去脉！ 工作a是kity的第一次尝试， 工作c是kity的进一步实践， 通过对比kity与raphael的区别于联系， 发现两者各有千秋: raphael的文档比较全面， demo较丰富; kity毕竟是后起之秀，在功能方面会更加全面， 比如画动感的饼状图的demo时，由于kity提供了画饼状图的类Pie，所以实现起来更简单方便。 家鸣师傅写demo的规范我不习惯，原因是它完全不同于外部引用库的做法。如果对kity库不够了解，那么对于家鸣为什么要那么费劲的去写demo是不能理解的。因此，接下来要做的事情就是要花周末的时间仔细的研究一下kity。

## 下周工作安排  ##

1.   实现6个demo:

	+	[http://raphaeljs.com/bounce.html](http://raphaeljs.com/bounce.html)
	+	[http://raphaeljs.com/animation.html](http://raphaeljs.com/animation.html)
	+	[http://raphaeljs.com/helvetica.html](http://raphaeljs.com/helvetica.html)
	+	[http://bl.ocks.org/mbostock/1353700](http://bl.ocks.org/mbostock/1353700)
	+	[http://bl.ocks.org/metormote/6392996](http://bl.ocks.org/metormote/6392996)
	+	自选

2.   继续研究学习kity， 为kity串讲做准备

3.   继续研究学习模块化
