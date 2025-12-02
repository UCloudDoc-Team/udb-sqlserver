# 类型版本

## 实例类型

UDB SQL Server 提供 NVMe 机型**普通版**与**集群版**两类实例，满足不同业务场景需求。普通版基于高性能云盘，采用单节点部署，兼具稳定性与高性价比，适合用于测试、学习等对高可用性要求不高的场景；集群版基于 Always On 技术实现，支持主从复制和自动故障切换，保证数据库的高可用性和业务连续性。

UDB SQL Server 采用计算与存储分离的架构设计。当计算节点出现故障时，可通过快速切换或替换节点实现业务快速恢复。底层数据基于云盘三副本进行存储，确保数据具备较高的可靠性。产品同时提供数据库连接数、访问量、资源使用率等多项指标的实时监控，并支持自定义告警策略，相比自建数据库更省心、更易运维。

UDB SQL Server 基于云服务器资源部署，具备明显的成本优势，同时能够提供优于传统自建方案的数据库性能。底层使用高性能云盘，能够满足绝大多数 I/O 负载的业务需求。







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
