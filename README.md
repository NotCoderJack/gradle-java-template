# Gradle-Java Project Template

## Init
```
cd boxed-hello/
bash setup_project.sh
./gradlew --info tasks
./gradlew --quiet build && ./gradlew --quiet printJarPath
./gradlew --quiet :sayHelloWithJar
```

## Inside
- add gradle common script to repo

- gradle/wrapper/gradle-wrapper.jar
- gradle/wrapper/gradle-wrapper.properties
- gradlew and gradlew.bat(for Windows)

[Aboutn gradle-wrapper](https://docs.gradle.org/current/userguide/gradle_wrapper.html)

## Download Gradle
bash setup_project.sh

## Problems may block
- [gradle-sync-failed](https://stackoverflow.com/questions/42591546/gradle-sync-failed-cause-error-in-opening-zip-file-corrupt-dependency-cache/42600670)


## Respect
 - [github.com ben-wangz](https://github.com/ben-wangz)