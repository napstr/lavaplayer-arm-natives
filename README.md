# lavaplayer-arm-natives
ARM natives for lavaplayer

# Usage

Maven:

```xml
<repositories>
  <!-- ... -->
  <repository>
    <id>whatever</id>
    <name>whatever</name>
    <url>https://dl.bintray.com/natanbc/mave</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>com.github.natanbc</groupId>
    <artifactId>lavaplayer-arm-natives</artifactId>
    <version>VERSION</version>
  </dependency>
</dependencies>
```

Gradle:

```gradle
repositories {
    //...
    maven { url 'https://dl.bintray.com/natanbc/maven' }
}

dependencies {
    //...
    compile 'com.github.natanbc:lavaplayer-arm-natives:1.3.10'
}
```
