#爬虫相关技术

1. 在伪造信息时，如果一个网站有手机端，那就在调试的时候调到手机模式，去获取headers。

异步加载：
在网页异步加载的时候，在调试处选择'Network'-'XHR'，然后不断下拉网页，看返回信息。找到实际的request