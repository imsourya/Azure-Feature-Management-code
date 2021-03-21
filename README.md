Code is taken from Azure App Configuration Documentation and modified

- Create Azure App Configuration and a feature flag to it called `beta: false`.
- `export APP_CONFIGURATION_CONNECTION_STRING=...`
- `mvn clean install && mvn spring-boot:run`
-  Use this to try : http://localhost:8080/
