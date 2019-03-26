# 初始化

```bash
# 安装
cd ssm-integrated-archetype/
mvn install
mvn archetype:update-local-catalog

# 创建项目
mvn archetype:generate -DarchetypeCatalog=local
```

|可配置参数|默认值|
|--|--|
|db_url         |jdbc:mysql:///demo?characterEncoding=utf-8|
|db_driver      |com.mysql.jdbc.Driver|
|db_username    |root |
|db_password    |root |
|redis_host     |localhost |
|redis_post     |6379 |
|redis_password |redis |

<br>

# 框架集成版本

|主要框架|版本|
|--|--|
|spring     |4.3.9.RELEASE |
|mybatis    |3.4.2 |
|druid      |1.1.10 |
|slf4j      |1.7.25 |
|log4j      |1.2.17 |
|junit      |5.3.1 |

# Maven 插件

|插件|版本|
|--|--|
|jetty  |6.2.5 \| 9.2.26|
|jrebel |1.1.5 |