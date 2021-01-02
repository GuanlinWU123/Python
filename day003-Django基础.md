# Day003
## Django
- Django 连接mysql
	- https://www.cnblogs.com/tassel/p/12038105.html
	- 在2.4 弹出 “*mysqlclient 1.4.0 or newer is required; you have 0.10.1.*” 版本信息不匹配时，可以通过在整个project的“__init__.py”文件中指定版本来解决
	- ```python
		import pymysql
		pymysql.version_info = (1, 4, 13, 'final', 0)
		pymysql.install_as_MySQLdb()
	  ```
	- Django配置 实现简易网页的编写
		- https://www.bilibili.com/video/BV1wT4y1j71A?p=9
	- 