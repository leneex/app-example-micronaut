# Micronaut

Example [Micronaut](https://micronaut.io/) app. Micronaut is a JVM framework for building lightweight microservices with fast startup and low memory use.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | leave empty |
| Application port | `8000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
./mvnw dependency:resolve

# run in development mode
./mvnw mn:run

# build for production and run
./mvnw package && java -jar target/app-example-micronaut-0.1.jar
```

Requires JDK 17 or later. `./mvnw` will automatically download the required Maven version.
