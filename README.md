# springboot_mybatis
# 图书管理系统

# Spring Boot与MyBatis集成示例
该项目演示了如何将MyBatis与Spring Boot集成。

# 环境要求
要运行此项目，您需要：

Java 8或更高版本
Maven 3.6.0或更高版本

# 入门指南
按照以下说明在本地机器上获取该项目的副本并运行它。

# 克隆存储库
bash
Copy code
git clone https://github.com/wwedutop/springboot_mybatis.git

# 构建和运行应用程序
bash
Copy code
cd springboot_mybatis
mvn clean package
java -jar target/springboot_mybatis-1.0.0.jar
访问应用程序
应用程序启动后，您可以在 http://localhost:8080 上访问它。

# API端点
此应用程序提供以下API端点：

GET /users - 返回数据库中所有用户的列表
GET /users/{id} - 返回指定ID的用户
POST /users - 创建新用户
PUT /users/{id} - 更新指定ID的用户
DELETE /users/{id} - 删除指定ID的用户
# 配置
该应用程序使用以下配置：

数据库：MySQL
服务器端口：8080
您可以通过修改 application.properties 文件来更改配置。

# 使用的技术栈
Spring Boot
MyBatis
MySQL数据库
Maven
# 作者
WW
# 许可证
本项目使用 MIT 许可证进行许可 - 有关详情，请参见 LICENSE.md 文件。
