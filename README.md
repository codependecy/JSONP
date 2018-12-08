更新hosts

添加127.0.0.1 frank.com
	127.0.0.1 jack.com
	
git bash 里分别打开

node server.js 8001

node server.js 8002

浏览器打开(frank.com:8001)以及(jack.com:8002)

点击按钮，就实现了 frank.com:8001与jcak.com:8002之间的JSONP请求