# AEM examples

## Description

S

## Building

Project build is based on [Gradle](https://docs.gradle.org/current/userguide/userguide.html) and using [Gradle AEM Plugin](https://github.com/Cognifide/gradle-aem-plugin).

To build CRX package and deploy it on AEM instance, simply run command:

```bash
sh gradlew
```


## Cleaning content
gradlew packageSync -Ppackage.sync.mode=clean_only
