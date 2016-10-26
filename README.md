# JCLEC Maven Repository

Java Class Library for Evolutionary Computation maven repo (unofficial).

## Usage

Add to your Maven project `pom.xml`:

```xml
<project>
  <!-- ... -->
  <dependencies>
    <!-- ... -->
    <dependency>
      <!-- JCLEC base -->
      <groupId>com.davidmiguel</groupId>
      <artifactId>jclec-base</artifactId>
      <version>4.0.0</version>
    </dependency>
    <dependency>
      <!-- JCLEC classification -->
      <groupId>com.davidmiguel</groupId>
      <artifactId>jclec-classification</artifactId>
      <version>4.0.0</version>
    </dependency>
    <!-- ... -->
  </dependencies>
  <!-- ... -->
  <repositories>
      <repository>
          <id>opencv-maven-repo</id>
          <url>https://raw.github.com/davidmigloz/jclec_maven_repo/master</url>
      </repository>
  </repositories>
</project>
```

## Versions supported

- JCLEC 4.0.0