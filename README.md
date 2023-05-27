# ruoyi_manager
バックエンド管理システム


1.基于SpringBoot + Thymeleaf + Layui + Apache Shiro + Redis + Mybatis Plus 的后台管理系统  
2.支持菜单权限与数据权限    
3.数据库支持 MySQL、Oracle、sqlServer 等主流数据库  
4.提供代码生成器，基本增删改查无需编写，可快速完成开发任务。  
5.后台接口RESTful 风格，支持前后端分离，可与app公用一套接口。  


- 后台接口RESTful 风格，支持前后端分离，可与app公用一套接口
- 采用RBAC的权限控制，支持数据权限（用法见下）
- 统一响应结果封装及生成工具
- 统一异常处理
- Shiro + Redis 实现 Token 角色权限认证
- 使用Druid Spring Boot Starter 集成Druid数据库连接池与监控
- 集成MyBatis-Plus，实现单表业务零SQL
- 支持多数据源，自由切换，只需方法或类上用 @DS 切换数据源
- 集成国人风格的knife4j，自动生成接口文档
- 提供代码生成器(MySQL、Oracle、sqlServer等主流数据库)，生成从Html到Mapper，爽歪歪  
