# What is it

Sample of a maven project creating a simple maven 3 plugin

## Requeriments

- Maven [3+](https://maven.apache.org/download.cgi)
- Java [8+](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

## Play

Installing plugin locally

```
mvn clean install
```

## Testing

```
cd hello-maven-plugin-test
mvn sample.plugin:hello-maven-plugin:hello -Dtest="parameter"
```

## Output

```
...
[INFO] Hello parameter
...
```

## References

- [Creating Maven plugin](https://dzone.com/articles/a-simple-maven-3-plugin)