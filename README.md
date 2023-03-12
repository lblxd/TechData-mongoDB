# TechData-mongoDB


## 此文件是考研教辅网站对应的数据库文件


首先确定自己的电脑已经安装好了mongodb服务器，并且配置好了全局变量。


打开命令行工具，使用mongoimport --db [databaseName] --collection [collectionName] --file [filePath]命令进行安装


参数说明
[databaseName] => 数据库名
[collectionName] => 集合名
[filePath] => 文件路径


示例：mongoimport --db test --collection user --file I:\routes.json


**如果发生报错，报错信息为"uncaught exception: SyntaxError: unexpected token: identifier :",可以参考 https://blog.csdn.net/lucaliu/article/details/118829087
