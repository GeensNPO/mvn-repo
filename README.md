# Geens Maven Repository

This github repository is used as the Geens Maven repository and can be used by adding the following configuration in your pom.xml file:
```xml
    <repositories>
        <repository>
            <id>geens-releases</id>
            <url>https://github.com/geens-NPO/mvn-repo/raw/master/releases</url>
        </repository>
    </repositories>
```
or for snapshots
```xml
    <repositories>
        <repository>
            <id>geens-snapshots</id>
            <url>https://github.com/geens-NPO/mvn-repo/raw/master/snapshots</url>
        </repository>
    </repositories>
```

The dependency can be added as follows:
```xml
    <dependency>
        <groupId>com.geens</groupId>
        <artifactId>sdk</artifactId>
        <version>{geens.sdk.version}</version>
    </dependency>
```
