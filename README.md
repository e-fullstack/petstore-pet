# petstore-pet
petstore-pet microservice to deal with petstore/pets

### dependency
- postgres db

### build

```bash
./mvnw clean install

# TO generate docker Image using build pack (inbuild)
./mvnw spring-boot:build-image
```

### run
```bash
./mvnw spring-boot:run
```
