# 快速上手

Sqlserver 支持从备份创建出一个新实例，也支持用户填入指定的备份下载地址进行数据恢复

## 从Sqlserver备份创建一个新实例
从实例列表页，或者本地域备份列表页查看备份信息，点击恢复至新实例，进入备份创建页面

![image](/images/backup_list.png)

![image](/images/recovery_create.png)

## 从US3的备份创建实例
用户可以上传一个备份文件到自有US3空间上，在创建Sqlserver实例可以选择自有备份链接，从US3恢复数据到UDB实例
备份要求
* 可以是单独一个库的备份文件，备份文件后缀为.bak 
* 可以将所有库的备份文件打包压缩成一个zip 文件，其他的文件格式不支持
* 备份还原会过滤掉不是数据库类型的文件，以及系统库（master,model,msdb,tempdb）
* 备份下载链接的过期时间要满足下载要求

![image](/images/get_url.png)
![image](/images/create_by_url.png)


