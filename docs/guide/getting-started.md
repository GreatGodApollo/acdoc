---
title: Getting Started
lang: en-US
permalink: /guide/getting-started
---


# Getting Started

## Installation

### Maven

```xml
<repository>
    <id>brettb-repo</id>
    <url>https://repo.brettb.xyz</url>
</repository>
```

```xml
<dependency>
    <groupId>xyz.brettb</groupId>
    <artifactId>ac</artifactId>
    <version>0.6.0</version>
    <scope>provided</scope>
</dependency>
```

### Gradle

```
repositories {
    maven {
        name = 'brettb-repo'
        url = 'https://repo.brettb.xyz'
    }
}

dependencies {
    compileOnly group: 'xyz.brettb', name: 'ac', version: '0.6.0'
}
```
