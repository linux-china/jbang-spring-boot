JBang with Spring Boot
===================================

Please install [JBang](https://www.jbang.dev/download/) first :)

# JBang Templates

### Spring Boot with Java

* Spring Boot 2: `jbang init -t SpringBoot2@linux-china/jbang-spring-boot HelloApp`
* Spring Boot 3: `jbang init -t SpringBoot3@linux-china/jbang-spring-boot HelloApp`

### Spring Boot with Kotlin

* Spring Boot 2: `jbang init -t SpringBoot2Kt@linux-china/jbang-spring-boot HelloApp`
* Spring Boot 3: `jbang init -t SpringBoot3Kt@linux-china/jbang-spring-boot HelloApp`

# IntelliJ IDEA integration

Please install [JBang IntelliJ IDEA plugin](https://plugins.jetbrains.com/plugin/18257-jbang) first.

Input `idea .` to open the project, then right click Java/Kotlin file and select `Sync JBang DEPS to Module`.

# Tips

* Spring Boot configuration from CLI

```
//JAVA_OPTIONS -Dserver.port=8081 -Dspring.application.name=hello-app
```

# References

* JBang: https://www.jbang.dev/ 