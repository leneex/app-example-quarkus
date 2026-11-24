# Quarkus

Example [Quarkus](https://quarkus.io/) app. Quarkus is a Java framework built for containers, with fast startup and low memory use.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | `java -jar target/quarkus-app/quarkus-run.jar` |
| Application port | `8000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
./mvnw dependency:resolve

# run in development mode
./mvnw quarkus:dev

# build for production and run
./mvnw package
java -jar target/quarkus-app/quarkus-run.jar
```

Requires JDK 17 or later. `./mvnw` will automatically download the required Maven version.
