### 算法助手 版本：2.1.2

重要提示：由于更改了配置信息和数据库的存储方式，此次更新会导致旧版的数据配置全部丢失，请提前做好备份处理


#### 功能新增：
1、修改了配置文件的存储方式，避免宿主App卸载重装后算法助手配置丢失

2、兼容Android13

3、修改日志列表布局，提升日志查找体验

4、日志列表对日志进行简单分类

5、依赖系统服务，Lsposed用户请在作用域中勾选"系统框架"

6、新增自定义Hook配置的分享和导入

7、自定义Hook支持修改参数值

8、新增数据输出的设置功能，hex和base64随意切换


#### 功能优化:

1、修复了在部分情况下，加解密算法数据不全的问题

2、修复了数据量过大导致崩溃的问题

3、修复部分数据无法加载的问题

4、日志列表改为异步加载，避免卡顿

5、修复其他若干个bug




## 主要功能

1、Md5,Sha等信息摘要算法(MessageDigest类)

2、AES、DES，RSA等秘钥算法(Cipher类)

3、Hmac等含有秘钥的哈希算法(Mac类)

4、对话框的定位(Dialog类)

5、Log捕获(LOG类)

7、拦截程序退出(System以及其他类)

8、justTrustMe升级版(可高效自动定位混淆后的okhttp)

9、文件访问记录(File类)

10、自定义Hook，可自行定义hook类，可设置返回值，可拦截执行

11、……后续会不断进行增加


## 自定义Hook是否支持加固app
理论上支持一些免费版的加固


## 使用教程
1、设备上需要安装xposed环境，并激活模块，Lsp用户需要勾选"系统框架"和被Hook的app

2、启动算法助手，选择需要hook的目标程序，应用开关打开，相应的功能自行选择

3、运行目标程序，回到算法助手，即可在日志面板看到相关信息



## 下载地址
[https://wwmb.lanzouw.com/iOrIc0xkn9fg](https://wwmb.lanzouw.com/iOrIc0xkn9fg)
