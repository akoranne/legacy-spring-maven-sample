# Legacy Spring Sample

This application is a legacy spring / maven sample. 

To build
```
  $ mvn clean package
```

To build and run as docker compose
```
  $ docker-compose up -d
```

Goto - http://localhost:8080/springwebapp/car/add

To shutdown 
```
  $ docker-compose stop
```

To clean
```
  $ docker system prune -a
```

Reference:

*  https://runnable.com/docker/java/dockerize-your-java-application
*  https://github.com/sbrosinski/spring-boot-on-k8s
