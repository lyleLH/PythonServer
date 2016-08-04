# PythonServer

##文档传送门:

###[零基础学Python](http://python.xiaoleilu.com/index.html "零基础学Python")
###[Flask快速入门](http://docs.jinkan.org/docs/flask/quickstart.html "快速入门")



---

##实际应用（针对本项目）

	Flask框架实现的一个微型HTTP服务器，没有使用到数据库，不适合生产使用，只是用于熟悉Flask的使用

###环境配置

#### 安装 `pip`
#####[pip的安装和使用](http://www.ttlsa.com/python/how-to-install-and-use-pip-ttlsa/ "pip安装使用详解")

#### 安装 `virtualenv`

#####[virtualenv的安装](https://virtualenv.pypa.io/en/stable/installation/ "virtualenv文档首页")


---

###服务器实现
#### 安装和引入`Flask` ，以及代码实现

##### [Flask实现一个RESTful API服务器](http://www.cnblogs.com/vovlie/p/4178077.html "使用python的Flask实现一个RESTful API服务器端[翻译]")


---
###服务器运行

####去除文件的执行权限 
`chmod a+x app.py`
####运行服务器程序

` ./app.py`

####配置程序监听所有公网的请求

```
if __name__ == '__main__':
    # app.run(debug=True) // 
    app.run(host='0.0.0.0')
    
```


---







