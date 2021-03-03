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