# node学习笔记

### art-template

### JWT

对称加密

```js
var jwt=require('jsonwebtoken');
var token = jwt.sign(payload,privateKey);   //加密

var decode = jwt.verify(token,privateKey);  //解密
```

非对称加密

![image-20210301124729017](C:\Users\95191\AppData\Roaming\Typora\typora-user-images\image-20210301124729017.png)

![image-20210301125310753](C:\Users\95191\AppData\Roaming\Typora\typora-user-images\image-20210301125310753.png)