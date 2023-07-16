# reload4j-extras

Forked from apache/log4j-extrac to use with reload4j which fixes most pressing security issues.

**https://github.com/qos-ch/reload4j**

## Changes from log4j-extras

Features
 - JVM support from 1.4+ to 11+
 - Change log4j to reload4j

Test
 - Explicitly use maven-surefire-plugin
   - Run `mvn test`
 - Bump junit from 3.8.1 to 4.13.2
