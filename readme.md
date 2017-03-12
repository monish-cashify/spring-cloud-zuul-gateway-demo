
spring-cloud-zuul-gateway-demo
========
- gradle
- spring boot/cloud
- jetty
- zuul


## Development

### Spring Boot
```
$ ./gradlew bootRun
```
### Build & Run
```
$ ./gradlew build && java -jar build/libs/tbk-spring-cloud-zuul-gateway-demo-<version>.jar
```

```
$ curl localhost:8080/health
{"status":"UP","diskSpace":{"status":"UP","total":397635555328,"free":328389529600,"threshold":10485760}}}
```

