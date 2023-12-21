<dependency>
   <groupId>com.mysql</groupId>
   <artifactId>mysql-connector-j</artifactId>
   <scope>runtime</scope>
</dependency>

spring:
  datasource:
    url: jdbc:mysql://localhost:3306/microservices
    username: root
    password: root
    driver-class-name: com.mysql.cj.jdbc.Driver
  jpa:
    database-platform: org.hibernate.dialect.MySQL8Dialect
    hibernate:
      ddl-auto: update
    show-sql: true
  application:
    name: USER-SERVICE

    npm install @angular/cli @angular-devkit/build-angular --legacy-peer-deps


    login video:https://www.youtube.com/watch?v=YUqi1IjLX8I
