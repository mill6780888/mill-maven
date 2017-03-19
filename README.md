# mill-maven
管理私有maven项目
> 添加远程仓库
```
 <repositories>
     <repository>
         <id>haoch-maven-release-repository</id>
         <name>haoch-maven-release-repository</name>
         <url>https://raw.github.com/mill6780888/mill-maven/release/</url>
     </repository>
 </repositories>
```
> 添加依赖
```
<dependencies>
     <dependency>
         <artifactId>base-utils</artifactId>
         <groupId>mill.java.base</groupId>
         <version>1.0-SNAPSHOT</version>
     </dependency>
 </dependencies>
```
