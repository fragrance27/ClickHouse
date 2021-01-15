---
machine_translated: true
machine_translated_rev: 72537a2d527c63c07aa5d2361a8829f3895cf2bd
toc_folder_title: "\u8868\u51FD\u6570"
toc_priority: 34
toc_title: "\u5BFC\u8A00"
---

# 表函数 {#table-functions}

表函数是构造表的方法。

您可以使用如下场景使用表函数:

-   [FROM](../statements/select/from.md)  `SELECT` 查询中的 `FROM` 子语。

        用于创建只在当前的查询之中有效的临时表的方法。当查询完成该临时表会被删除。

-   [CREATE TABLE AS \<table_function()\>](../statements/create.md#create-table-query) 查询。

        创建一张表的方法之一。

!!! warning "警告"
    你不能使用表函数，如果 [allow_ddl](../../operations/settings/permissions-for-queries.md#settings_allow_ddl) 设置被禁用。

| 函数               | 产品描述                                                                                               |
|--------------------|--------------------------------------------------------------------------------------------------------|
| [file](file.md)    | 创建一个 [文件](../../engines/table-engines/special/file.md)-引擎的表。                                |
| [merge](merge.md)   | 创建一个 [合并](../../engines/table-engines/special/merge.md)-引擎的表。                               |
| [numbers](numbers.md) | 创建一个包含整数填充的单列的表。                                                                       |
| [remote](remote.md)  | 允许您访问远程服务器，而无需创建 [分布](../../engines/table-engines/special/distributed.md)-引擎的表。 |
| [url](url.md)      | 创建一个 [Url](../../engines/table-engines/special/url.md)-发动机表。                                  |
| [mysql](mysql.md)  | 创建一个 [MySQL](../../engines/table-engines/integrations/mysql.md)-引擎的表。                         |
| [jdbc](jdbc.md)    | 创建一个 [JDBC](../../engines/table-engines/integrations/jdbc.md)-引擎的表。                           |
| [odbc](odbc.md)    | 创建一个 [ODBC](../../engines/table-engines/integrations/odbc.md)-引擎的表。                           |
| [hdfs](hdfs.md)    | 创建一个 [HDFS](../../engines/table-engines/integrations/hdfs.md)-引擎的表。                           |
| [s3](s3.md)    | 创建一个 [S3](../../engines/table-engines/integrations/S3.md)-引擎的表。                           |

[原始文章](https://clickhouse.tech/docs/en/query_language/table_functions/) <!--hide-->
