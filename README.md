# DES & RSA
## 网络安全的三道防线
防火墙 -> 入侵检测 -> 信息加密
## 信息加密
最后一道防线：数据加密，是对付黑客的终极武器。即使黑客突破了我们的防火墙、避过了入侵检测、最后拿到了我们的数据，结果却看到一堆乱码，得不到有效的信息，这或许实现了“真正的安全”。
## 密码学
密码学的3个主要分支是：
- 对称密码
- 非对称密码
- 密码学Hash函数，以及相关的消息认证码和数字签名
## [DES](DES.ipynb)
DES是使用最广泛的**对称密码**：数据加密标准（Data Encryption Standard）。<br>
在对称密码系统（也叫做私钥密码系统）中，加密和解密使用**相同的密钥**。<br>
关于DES的原理以及代码实现，请点[这里](DES.ipynb)。
## [RSA](RSA.ipynb)
RSA是著名的**非对称密码**：1977年由Ron Rivest、Adi Shamir、Leonard Adleman一起提出来的。RSA就是他们三人姓氏开头字母拼在一起组成的。<br>
在非对称密码系统（也叫做公钥密码系统）中，加密和解密由一对密钥来完成，分别称为**公钥和私钥**，公钥可以公开，私钥要保密。<br>
关于RSA的原理以及代码实现，请点[这里](RSA.ipynb)。
## 图解对称密码与非对称密码

