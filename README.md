Maven showcase parent
----
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