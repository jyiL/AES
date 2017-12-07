## 在跟java对接API时遇到的AES加解密问题

* 工作模式为CBC
* 填充方式为PKCS5

java的初始化向量
```
private static final byte[] DEFAULT_IV = {1,-1,1,-1,1,-1,1,-1,1,-1,1,-1,1,-1,1,-1};
```