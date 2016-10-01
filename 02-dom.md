# 一些 DOM 对象方法 #

	方法							描述
	getElementById()			返回带有指定 ID 的元素。
	getElementsByTagName()		返回包含带有指定标签名称的所有元素的节点列表（集合/节点数组）。
	getElementsByClassName()	返回包含带有指定类名的所有元素的节点列表。
	appendChild()				把新的子节点添加到指定节点。
	removeChild()				删除子节点。
	replaceChild()				替换子节点。
	insertBefore()				在指定的子节点前面插入新的子节点。
	createAttribute()			创建属性节点。
	createElement()				创建元素节点。
	createTextNode()			创建文本节点。
	getAttribute()				返回指定的属性值。
	setAttribute()				把指定属性设置或修改为指定的值。

# 属性 #

	属性							描述
	innerHTML 					获取元素内容
	nodeName 					元素节点的 nodeName 与标签名相同、属性节点的 nodeName 与属性名相同、文本节点的 nodeName 始终是 #text、文档节点的 nodeName 始终是 #document
	nodeValue 					元素节点的 nodeValue 是 undefined 或 null、文本节点的 nodeValue 是文本本身、属性节点的 nodeValue 是属性值
	nodeType 					返回节点的类型（元素1、属性2、文本3、注释8、文档9）
	childNodes		
	document.anchors			获取	锚（<a>）
	x=event.clientX				光标的位置
	event.screenX				相对屏幕光标的位置
	event.keyCode				按键