# base-neo4j-extension
base repo for neo4j extension projects

## using sqlserver JDBC connector
Adding the dependency with a variable for the java version; pulls the correct jar from the maven repository.
If you aren't using sqlserver, then remove the dependency.
```
<dependency>
    <groupId>com.microsoft.sqlserver</groupId>
    <artifactId>mssql-jdbc</artifactId>
    <version>10.2.1.jre${java.version}</version>
</dependency>
```