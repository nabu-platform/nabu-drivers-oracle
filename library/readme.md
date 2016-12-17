Install the file in maven using: 

```
$ mvn org.apache.maven.plugins:maven-install-plugin:2.5.2:install-file -Dfile=/home/alex/files/repository/nabu/drivers/oracle/library/com.oracle.jdbc-ojdbc7-12.1.0.1.jar -DgroupId=com.oracle.jdbc -DartifactId=ojdbc7 -Dversion=12.1.0.1 -Dpackaging=jar
```