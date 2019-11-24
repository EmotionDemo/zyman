# zyman
基于SSM架构：SpringMVC+Spring+MyBatis创建的一个医药管理系统具备CRUD
create、Retrieve、Update、Delete
功能点：1、分页
        2、数据校验
          jQuery前端校验+JSR303后端校验
       3、Ajax
       4、rest风格的URI：使用Http协议请求方式的动词，来表示对资源的操作（GET（查询）、POST（新增）、PUT（修改）、DELETE（删除））
技术点：基础框架－SSM
       数据库：Oracle
       前端框架：-bootstrap
       依赖管理：maven
       分页：pagehelper
       逆向工程：MyBatis Generator
       
基础环境搭建：1、创建一个maven工程
             2、引入项目依赖的jar包
                ·spring
                ·springmvc
                ·mybatis
                ·数据库连接池、驱动包
             3、引入bootstrap前端框架
             4、编写SSM整合的关键配置文件
                ·web.xml,spring,springmvc,mybatis,使用Mybatis的逆向工程生成对应的Bean以及mapper
             5、测试mapper
