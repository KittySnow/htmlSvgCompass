# htmlSvgCompass

圆形菜单编写
这个是一个用SVG写出来的圆形菜单代码，最多支持12个菜单，修改css可修改配色。
使用方法：
$.luopan({data:[{name:'建议中文', link:'www.baidu.com', onClick:function(){}}],id:'luopanSvg'})//有onClick就不写link,
如果要更新数据：

var t = $.luopan({data:[{name:'建议中文', link:'www.baidu.com', onClick:function(){}}],id:'luopanSvg'});


t.updataDom([{name:'建议中文', onClick:function(){}}])
