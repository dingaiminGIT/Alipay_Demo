## Alipay_Demo

* 这是一个支付宝集成的Demo, 当然因为没有签约商户, 返回的状态码是支付不成功的.
* 下面是关于Clone代码下来运行报错的问题, 主要是文件路径找不到, 我已经截了图, 只要按照图中的步骤重新配置就好了

#### 一. 文件报红,删掉重新添加即可
![截图1](http://images2015.cnblogs.com/blog/871467/201601/871467-20160109182113090-695667822.png)

#### 二. rsa.h 文件报错,提示"'openssl/asn1.h' file not found" 
![截图2](http://images2015.cnblogs.com/blog/871467/201601/871467-20160109182128309-1495461776.png)

#### 解决方法: 请根据下图步骤重新配置路径
![截图3](http://images2015.cnblogs.com/blog/871467/201601/871467-20160109182159528-978714781.png)
