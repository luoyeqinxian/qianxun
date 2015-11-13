千寻网1.0使用文档

环境要求:
1).JDK1.7+
2).eclipse for javaEE +
3).mysql5.6+
4).tomcat8.0+

数据库搭建:
首先进入mysql,
创建一个数据库"qianxun",
使用图形化工具navcat for mysql,右键"qianxun"数据库->执行SQL文件("Project_QianXun\src\com\qianxun.sql");

更改JDBC的用户名
1.找到Project_QianXun\src\com\util\ConnectionUtils.java
2.把用户名和密码改为你们自己的！
private static String userName = "root";// 用户名
private static String password = "root";// 密码

到此为止，可以把代码发布到tomcat运行了!
