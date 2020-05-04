# Ot parent

#### 项目介绍
包含一些公共相关项目 如：统一Maven依赖版本

#### 使用方式

````
  git clone https://github.com/cuteJ/ot-server-parent.git
  cd ot-server-parent
  mvn clean install -Prelease
````

````
    <parent>
      <groupId>com.onlythinking</groupId>
      <artifactId>ot-server-parent</artifactId>
      <version>1.0</version>
    </parent>
  
    <repositories>
      <repository>
        <id>github</id>
        <name>github nexus</name>
        <url>https://maven.pkg.github.com/cuteJ/ot-server-parent</url>
      </repository>
    </repositories>
````
