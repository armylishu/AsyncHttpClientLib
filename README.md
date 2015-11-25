# AsyncHttpClientLib
在asynchttpclient库中添加httpclient的包内引用，兼容6.0SDK

在android 6.0（API 23）中，Google已经移除了移除了Apache HttpClient相关的类
推荐使用HttpUrlConnection，因此基于httpclient设计的开源框架asynchttpclient
受到直接影响，这个库现在加入了httpclient引用，亲测可用。项目库添加了httpclient
内部引用，所以相对应的包的大小增加了，如果有apk大小限制的同学推荐使用google推荐
的volley。

ascyhttpclient项目地址：http://loopj.com/android-async-http/

volley项目地址：https://github.com/callmeli/android-volley

volley项目地址：https://android.googlesource.com/platform/frameworks/volley/+/master（源地址，需要翻墙）
