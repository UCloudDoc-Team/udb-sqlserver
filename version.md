# 类型版本

## 实例类型

UDB SQL Server 提供 NVMe 机型**普通版**与**集群版**两类实例，满足不同业务场景需求。

**普通版**

普通版实例采用计算与存储分离架构，基于高性能云盘，采用单节点部署，具备价格低廉、性价比高等优势。其主要特性包括：计算与存储分离，若计算节点故障，能够通过更换节点达到快速恢复的效果；底层数据采用云盘三副本存储，保证一定的数据可靠性。

普通版支持对数据库连接、访问量及资源使用等多项指标进行监控，并可配置告警策略，较自建数据库更省心易用。同时，普通版基于云服务器节点部署，具备显著的成本优势，并提供优于自建方案的数据库性能。其底层采用高性能云盘，适用于大多数 I/O 场景，兼具稳定性与高性价比。适合用于测试、学习等对高可用性要求不高的场景。


**集群版** 
集群版基于 Always On 技术实现，支持主从复制和自动故障切换，保证数据库的高可用性和业务连续性。



## 数据库版本

| 地域 | 实例类型 | 数据库类型 |
| --- | --- | --- |
| 华北一 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 华北二 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 上海二 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 广州 | 普通版 | SQL Server 2012、SQL Server 2019 |
| | 集群版 | SQL Server 2019 |
| 香港 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 台北 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 新加坡 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 曼谷 | 普通版 | SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 胡志明市 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 孟买 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 洛杉矶 | 普通版 | SQL Server 2012、SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |
| 拉各斯 | 普通版 | SQL Server 2017、SQL Server 2019 |
| | 集群版 | SQL Server 2017、SQL Server 2019 |


## 规格配置

CPU&内存规格：

|CPU(核)|2核|4核|8核|16核|32核|64核|
|----|--|--|--|--|--|--|
|内存(GB)|	4G、8G、16G| 8G、16G、32G| 16G、32G、64G| 64G、128G|	128G、256G|	256G、512G|

硬盘范围：20GB-32000GB。
