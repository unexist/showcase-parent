Maven showcase parent
====
This project holds a bill-of-material (BOM) for my quarkus showcase projects, to ease
version handling and tool configs.

Instructions
----
To use it, just copy the following lines to your pom:

```xml
    <parent>
        <groupId>dev.unexist.showcase</groupId>
        <artifactId>java-parent</artifactId>
        <version>0.1</version>
    </parent>
```

Profiles
----
Also included is a list of different profiles:

- **quarkus** - Latest stable version
- **quarkus-testing** - Latest QS version
- **hg** - Enables mercurial properties
- **git** - Enables git properties
- **native** - Builds native version

The quarkus version can be toggled with the **testing** property:

```xml
    <properties>
        <testing>true</testing>
    </properties>
```

Git can be enabled with the **git** property:

```xml
    <properties>
        <git>true</git>
    </properties>
```
