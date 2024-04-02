# open-liberty-spring-boot

Followed
tutorial  [open-liberty](https://openliberty.io/guides/spring-boot.html#building-and-running-the-application-in-a-docker-container)

### To run the project:

```mvn clean package```

 ```
    docker build -t spring-boot-open-liberty . 
    
     docker run -d --name spring-boot-open-liberty  -p 9080:9080 -p 9443:9443 springboot
```

If everything is ok: [helloWorld](http://localhost:9080/hello)