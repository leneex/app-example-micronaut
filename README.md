Пример приложения Micronaut, которое можно развернуть без настройки.

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
./mvnw dependency:resolve

# запуск в дев режиме
./mvnw mn:run

# сборка для продакшн
./mvnw package && java -jar target/app-example-micronaut-0.1.jar
```
