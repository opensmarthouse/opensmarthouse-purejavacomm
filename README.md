[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.bidib.com.github.purejavacomm/purejavacomm/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.bidib.com.github.purejavacomm/purejavacomm)
[![Javadocs](https://www.javadoc.io/badge/org.bidib.com.github.purejavacomm/purejavacomm.svg)](https://www.javadoc.io/doc/org.bidib.com.github.purejavacomm/purejavacomm)

OpenSmartHouse fork of PureJavaComm to incorporate OSGi manifest headers and deploy to maven.

PureJavaComm is an Application Programmin Interface (API) for accessing serial ports from Java, so this is a library aimed at programmers, not end users.

PureJavaComm aims to be a drop-in replacement for Sun's (now Oracle) abandoned JavaComm and an easier to deploy alternative to RXTX.

PJC is written 100% in Java so it is easy for Java programmers to develop and debug and it requires no native libraries. Native access to the underlaying operating system's serial port programming interface is provided by the wonderful JNA library which takes away all the pain of compiling and deploying native code.

PJC is BSD licensed but please note it depends on JNA which is LGPL/ASL dual licensed.

## Obtaining a Copy

PureJavaComm is deployed to Maven Central. Here are a few examples using popular build frameworks.

Using Gradle:

```groovy
repositories {
    mavenCentral()
}

dependencies {
    compile "org.opensmarthouse:purejavacomm:1.0.5"
}
```

Using Maven:

```xml
<dependency>
    <groupId>org.opensmarthouse</groupId>
    <artifactId>purejavacomm</artifactId>
    <version>1.0.5</version>
</dependency>
```
