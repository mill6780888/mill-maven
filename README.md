# mill-maven
管理私有maven项目
> 添加远程仓库
```
 <repositories>
     <repository>
         <id>haoch-maven-release-repository</id>
         <name>haoch-maven-release-repository</name>
         <url>https://raw.github.com/${github_account}/maven/release/</url>
     </repository>
 </repositories>
```
> 添加依赖
```
<dependencies>
     <dependency>
         <artifactId>${artifactId}</artifactId>
         <groupId>com.github.${github_account}</groupId>
         <version>${version}</version>
     </dependency>
 </dependencies>
```
