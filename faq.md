# FAQ
{{indexmenu_n>40}}

## 如何查看数据库的参数信息？ 连接UDB后执行如下SQL语句可查看

\`select \* from sys.configurations\`

## 如何查看当前数据库的连接信息？ 连接UDB后执行如下SQL语句可查看:

\`select \* from sys.dm\_exec\_connections\`

## 如何查看当前数据库的空间占用？ 连接UDB后执行如下SQL语句可查看数据库的空间占用：

\`use 数据库名; Exec sp\_spaceused;\`

## 如何查看一个表的空间占用？ 连接UDB后执行如下SQL语句可查看:

\`use 表所在的数据库; Exec sp\_spaceused '表名';\`
