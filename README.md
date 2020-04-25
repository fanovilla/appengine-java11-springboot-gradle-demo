# Spring Boot Application Google App Engine Standard with Java 11 using Gradle

## Running locally

```bash
$ ./gradlew bootRun
```

To view your app, navigate to `http://localhost:8080`.

## Deploying

```bash
$ ./gradlew appengineDeploy
```

To view your app, use command:
```
$ gcloud app browse
```
Or navigate to `https://<your-project-id>.appspot.com`.