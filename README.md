An example Quarkus application that can be deployed to Hostman Cloud Apps with no configuration.

🎉 [Demo]

🚀 [Create your App](https://hostman.cloud/my/apps/create)

📚 [Hostman Cloud Apps Documentation](https://hostman.com/docs/app-platform/)

## <a name="dev"></a>Running the project locally

```bash
# install dependencies
./mvnw dependency:resolve

# run in dev mode
./mvnw quarkus:dev

# build for production
./mvnw package && java -jar target/quarkus-app/quarkus-run.jar
```
