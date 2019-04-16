此项目代码为Mybatis-plus 3.1.0 的使用方法

项目中的代码为mybatis-plus-generator 代码生成器部分

mybatis-plus-generator：是用来生成mybatis-plus 下mybatis代码的

官方使用教程：https://mp.baomidou.com/guide/#%E7%89%B9%E6%80%A7

生成的代码包括controller、service、mapper、entity、xml...

生成方法：

    此处以oracle数据库示例：
        1、将application.yml中数据库连接配置改为自己的库。
        2、运行OracleGenerator.java中的main方法 
        3、控制台输入上一级包名
        4、输入想要反向生成代码的表结构
        5、将生成的代码考入项目中即可使用mybatis plus的核心功能。