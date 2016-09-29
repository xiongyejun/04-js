 创建新的 HTML 元素

    <!DOCTYPE html>
    <html>
    <body>
    
    <div id="div1">
    <p id="p1">这是一个段落。</p>
    <p id="p2">这是另一个段落。</p>
    </div>
    
    <script>
    for (var i = 0; i < 110; i++){
	    var para=document.createElement("p");
	    var node=document.createTextNode("这是新段落。" + i);
	    para.appendChild(node);
	    
	    var element=document.getElementById("div1");
	    element.appendChild(para);
    }
    </script>
    
    </body>
    </html>
    
删除已有的 HTML 元素
    
    <!DOCTYPE html>
    <html>
    <body>
    
    <div id="div1">
    <p id="p1">这是一个段落。</p>
    <p id="p2">这是另一个段落。</p>
    </div>
    
    <script>
    var parent=document.getElementById("div1");
    var child=document.getElementById("p1");
    parent.removeChild(child);

	//child.parentNode.removeChild(child);

    </script>
    
    </body>
    </html>