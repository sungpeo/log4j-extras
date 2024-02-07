# reload4j-extras

Forked from apache/log4j-extras to use with reload4j which fixes most pressing security issues.

**https://github.com/qos-ch/reload4j**

## Changes from log4j-extras

Features
 - Package don't include log4j(reload4j) anymore.
 - JVM support from 1.4+ to 1.8+
 - Change compile dependency from log4j to reload4j

Test
 - Explicitly use maven-surefire-plugin
   - Run `mvn test`
 - Bump junit from 3.8.1 to 4.13.2

## Using in your projects

### Maven

Add dependencies (you can also add other modules that you need):

```xml
<dependency>
    <groupId>io.github.sungpeo</groupId>
    <artifactId>reload4j-extras</artifactId>
    <version>1.2.22</version>
</dependency>
```

### Gradle

Add dependencies (you can also add other modules that you need):

```kotlin
dependencies {
    implementation("io.github.sungpeo:reload4j-extras:1.2.22")
}
```

Make sure that you have `mavenCentral()` in the list of repositories:

```kotlin
repositories {
    mavenCentral()
}
```

