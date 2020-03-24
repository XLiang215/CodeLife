https://www.geeksforgeeks.org/ajax-introduction/

## AJAX (Asynchronous JavaScript and XML)

Ajax是一项让网页不用刷新页面就可以从后段加载新数据的技术
Ajax使用JavaScript XMLHTTPRequest Object

创建对象的语法:
req = new XMLHttpRequest();

有两种类型的方法open（）和send（）:
req.open("GET", "abc.php", true); 
req.send();
上面的两行描述了这两种方法。req代表请求，它基本上是一个参考变量。GET参数通常是发送请求的两种方法之一。根据是否通过POST或GET方法发送数据，也可以使用POST。第二个参数是实际处理并处理请求的文件名。第三个参数为true，它指示请求是异步还是同步处理。默认情况下为true，这意味着请求是异步的。Open()方法用于准备请求，send()用于发送请求给server

- 优点：
1. 由于不需要再次重新加载页面，因此速度得以提高。
2. AJAX异步调用Web服务器，这意味着客户端浏览器避免在开始渲染之前等待所有数据到达。
3. 表单验证可以通过它成功完成。
4. 带宽利用率–从同一页面获取数据时，它可以节省内存。
5. 更具互动性。

- 缺点：
1. Ajax依赖于JavaScript。如果浏览器或操作系统存在JavaScript问题，则不支持Ajax。
2. Ajax在搜索引擎中可能会出现问题，因为它的大部分部分都使用JavaScript。
3. 用AJAX编写的源代码易于阅读。Ajax中将存在一些安全问题。
4. 调试很困难。
5. 使用启用AJAX的页面时浏览器后退按钮出现问题。
