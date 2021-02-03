# FAQ

### 1、云数据库 SQL Server 价格是怎样的？

云数据库 SQL Server 包含微软正版许可授权，采用按年、按月和按时计费模式。
定价由实例规格（CPU核数、内存容量）与存储空间（硬盘容量）3部分构成，具体定价详情参见 产品价格。

### 2、如何购买云数据库 SQL server?

登录 SQL Server 控制台 新建实例或直接调用API创建购买实例。

### 3、需要自己购买 SQL Server 许可声明吗？

UCloud为您提供“附带许可”模型的云数据库，在“附带许可”定价中，已经包含 SQL Server 软件许可，底层硬件资源，以及UCloud UDB 管理功能，您无需再单独购买 Microsoft SQL Server 许可。
使用附带许可模型的云数据库，您可以直接根据实例规格和使用时间支付费用，而无需考虑硬件成本和许可费用，高额的固定成本转换为较小的可变成本，降低您的IT成本。

### 4、如何下载安装SQL Server Management Studio?

先获取SQL Server Management Studio的安装包，方式一：通过点击此处下载（ufile上保存我们提供的SQL Server Management Studio安装包），方式二：通过访问Microsoft网站，下载SQL Server Management Studio安装包。

再将安装包上传到云服务器UHOST，双击安装包，按照向导完成安装即可。


### 5、如何查看数据库的参数信息？ 

连接UDB后执行如下SQL语句可查看：
```
select * from sys.configurations
```

### 6、如何查看当前数据库的连接信息？ 

连接UDB后执行如下SQL语句可查看:

`select * from sys.dm_exec_connections`

### 7、如何查看当前数据库的空间占用？ 

连接UDB后执行如下SQL语句可查看数据库的空间占用：

`use 数据库名; Exec sp_spaceused;`

### 8、如何查看一个表的空间占用？ 

连接UDB后执行如下SQL语句可查看:

`use 表所在的数据库; Exec sp_spaceused '表名';`
