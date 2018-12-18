# Summary

This simple example lets you run a http server with Spring boot.

Here are good resources who inspired this current snippet :

- https://spring.io/guides/gs/rest-service/
- https://www.baeldung.com/spring-controller-vs-restcontroller

## How to

Build and run :

```
mvn clean package
mvn spring-boot:run
```

Open a browser at : localhost:8080/toto

result:

```
{
  "owner": "Marcus Miller",
  "id": 2,
  "xs": [
    "Houhou",
    "Haha"
  ]
}
```
