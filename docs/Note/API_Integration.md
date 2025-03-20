## 相关学习
以下是 **Spring Boot 与数据库（MySQL、JPA、MyBatis 等）集成的权威网站和资源**，涵盖官方文档、教程和社区支持：

---

### **一、官方文档（必读）**
1. **[Spring Data JPA 官方文档](https://spring.io/projects/spring-data-jpa)**  
   • 核心内容：`JpaRepository` 接口、查询方法、事务管理。  
   • 实战示例：定义实体类、自定义查询、分页与排序。

2. **[Spring Boot 数据库配置](https://docs.spring.io/spring-boot/docs/current/reference/html/data.html)**  
   • 核心内容：`DataSource` 配置、连接池（HikariCP）、多数据源集成。  
   • 关键配置项：`spring.datasource.url`、`spring.jpa.hibernate.ddl-auto`。

3. **[MyBatis-Spring-Boot 文档](https://mybatis.org/spring-boot-starter/mybatis-spring-boot-autoconfigure/)**  
   • 核心内容：`@Mapper` 注解、XML 映射文件配置、动态 SQL 示例。

---

### **二、教程与实战**
4. **[Baeldung - Spring Data JPA 教程](https://www.baeldung.com/spring-data-jpa-tutorial)**  
   • 核心内容：实体关系映射（`@OneToMany`）、JPQL 查询、审计功能（`@CreatedDate`）。

5. **[Spring Guides - Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)**  
   • 核心内容：15 分钟快速入门项目，含完整代码和步骤。

6. **[MyBatis 实战指南](https://github.com/mybatis/spring-boot-starter/wiki/Quick-Start)**  
   • 核心内容：整合 Spring Boot 的配置示例、动态 SQL 编写技巧。

---

### **三、社区与问答**
7. **[Stack Overflow - Spring Boot + MySQL 常见问题](https://stackoverflow.com/questions/tagged/spring-boot+mysql)**  
   • 高频问题：连接池配置、事务不回滚、`LazyInitializationException` 处理。

8. **[GitHub 开源项目](https://github.com/search?q=spring+boot+mysql)**  
   • 推荐项目：搜索 `spring boot mysql demo`，参考真实项目结构。

---

### **四、工具与扩展**
9. **[Hibernate 官方文档](https://hibernate.org/orm/documentation/)**  
   • 核心内容：缓存机制、二级缓存配置、性能优化。

10. **[Flyway 数据库迁移工具](https://flywaydb.org/documentation/)**  
    ◦ 核心内容：SQL 版本控制、与 Spring Boot 集成配置。

---

### **五、中文资源**
11. **[Spring Boot 中文社区](https://springboot.io/)**  
    ◦ 核心内容：实战博客、常见错误解决方案。

12. **[MyBatis 中文文档](https://mybatis.org/mybatis-3/zh/index.html)**  
    ◦ 核心内容：XML 映射文件语法、动态 SQL 标签。

---

### **六、注意事项**
• **版本兼容性**：Spring Boot 2.x 和 3.x 的配置差异较大，注意文档版本。  
• **ORM 选择**：  
  • **JPA**：适合快速开发、标准化的场景；  
  • **MyBatis**：适合复杂 SQL 或遗留项目迁移。

---

通过以上资源，可系统学习 Spring Boot 与数据库的集成技术。遇到具体问题，优先查阅 **官方文档** 和 **Stack Overflow** 历史解答！ 🚀