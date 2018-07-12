# hello-world
hello world description
Chulan here and i did some changes here to the readme file
thank you.
#dependancies
<parent>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-parent</artifactId>
  <version>1.5.9.RELEASE</version>
  <relativePath/> <!-- lookup parent from repository -->
</parent>

<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>

<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-web</artifactId>
</dependency>
<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-test</artifactId>
  <scope>test</scope>
</dependency>

<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-devtools</artifactId>
  <scope>runtime</scope>
</dependency>
<dependency>
    <groupId>org.postgresql</groupId>
    <artifactId>postgresql</artifactId>
    <version>42.2.1</version>
</dependency>
<dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <scope>runtime</scope>
</dependency>

#Database properties
#spring Datasource
#spring.datasource.url = jdbc:mysql://localhost:3306/sb_hb_rest_db?useSSL=false
#spring.datasource.username = chulan
#spring.datasource.password = chulan

#Hibernate Properties
#spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQLDialect

#Hibernate ddl auto (create, create-drop, validate, update)
#spring.jpa.hibernate.ddl-auto = update

#spring Datasource
spring.datasource.url=jdbc:postgresql://localhost:5432/sb_rest_db
spring.datasource.username=postgres
spring.datasource.password=root
#spring.datasource.driver-class-name= org.postgresql.Driver

# Hibernate properties
spring.jpa.database-platform = org.hibernate.dialect.PostgreSQLDialect
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto = update
