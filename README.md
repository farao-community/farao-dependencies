# farao-dependencies

This is a pom that defines FARAO related dependencies version. You can import it this way in your project :
```
<dependency>
    <groupId>com.farao-community.farao</groupId>
    <artifactId>farao-dependencies</artifactId>
    <version>**version**</version>
    <scope>import</scope>
    <type>pom</type>
</dependency>
```

It enables to import all the FARAO and PowSyBl jar dependencies without specifying their versions and ensures dependencies consistency for those modules.