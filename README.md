## Modules
Naming Convention: lower case 

project folder: bankwiz-${moduleName}  

version: x.y.z 

## Packages
Naming Convention: lower case 
 
prefix: com.iisigroup.product.bankwiz  

## Maven Pom Prototype
```xml
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>com.iisigroup.product.bankwiz</groupId>
	<artifactId>bankwiz-${moduleName}</artifactId>
	<version>x.y.z-SNAPSHOT</version>
</project>
```

## Project Structure
```
.
├── src  
│   ├── main  
│   │   ├── java  
│   │   │   └── com  
│   │   │       └── iisigroup  
│   │   │           └── product  
│   │   │               └── bankwiz  
│   │   │                   ├── annoation  
│   │   │                   ├── constant  
│   │   │                   ├── config  
│   │   │                   ├── controller  
│   │   │                   ├── service  
│   │   │                   ├── repository  
│   │   │                   ├── domain  
│   │   │                   ├── dto  
│   │   │                   └── util  
│   │   └── resources  
│   │       ├── i18n  
│   │       ├── static  
│   │       │   ├── css  
│   │       │   └── js  
│   │       └── template  
│   └── test  
│       ├── java  
│       │   └── com  
│       │       └── iisigroup  
│       │           └── product  
│       │               └── bankwiz  
│       └── resources  
└── pom.xml  
```

## Obfause Setting
```xml
<plugin>
  <groupId>com.github.wvengen</groupId>
  <artifactId>proguard-maven-plugin</artifactId>
  <!── 覆寫parent設定，指向自己的conf位置 ──>
  <configuration>
    <proguardInclude>${project.parent.basedir}/proguard.conf</proguardInclude>
  </configuration>
</plugin>
```





