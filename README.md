# material-colors
Java Material Design Colors (color/string)

[![](https://jitpack.io/v/fcannizzaro/material-colors.svg)](https://jitpack.io/#fcannizzaro/material-colors)

## Dependence

### Gradle
```gradle
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'com.github.fcannizzaro:material-colors:0.1.0'
}
```

### Maven
```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependencies>
    <dependency>
        <groupId>com.github.fcannizzaro</groupId>
        <artifactId>material-colors</artifactId>
        <version>0.1.0</version>
    </dependency>
</dependencies>
```

###  Download JAR
[Release 0.1.0](https://github.com/fcannizzaro/material-colors/releases/tag/0.1.0)

## Usage
```java
  // awt.Color
  Color primary = Colors.indigo_500.asColor();

  // String
  String primary_dark = Colors.indigo_700.asString();

```

## Usage with [Resourcer](https://github.com/fcannizzaro/resourcer)
Use color name in xml files!
```xml
<?xml version="1.0"?>
<resources>
    <color name="primary">@color/indigo_500</color>
    <color name="accent" >@color/pink_accent_400</color>
</resources>
```
