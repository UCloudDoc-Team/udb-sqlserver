## 登录访问


通过客户端连接访问UDB SQL Server实例。以Microsoft SQL Server Management Studio（SSMS）客户端为例介绍如何连接到UDB SQL Server实例。

1、下载SQL Server管理工具Microsoft SQL Server Management Studio（SSMS）客户端，点击下载（ufile下载地址链接）

2、在UHost云主机上启动Microsoft SQL Server Management Studio客户端。

3、选择连接 > 数据库引擎 。

4、在弹出的连接到服务器对话框中输入登录信息，通过IP、端口、用户名、密码连接登录SQL Server。

![image](/images/0204sqlserver.png)

客户端相关参数说明：

|参数|说明|
|----|-------|
| 服务器类型| 选择 数据库引擎 。|
| 服务器名称| 输入UDB SQL Server实例的 IP地址 和 端口号，IP地址与端口号之间用英文逗号隔开，如10.12.12.12,1433。|
| 身份验证| 选择SQL Server身份验证。|
| 登录名| UDB SQL Server实例的账号名称(admin)。|
| 密码| UDB SQL Server实例的账号密码（新建UDB SQL Server实例时设置的密码）。|

5、单击连接，即可连接到实例。
