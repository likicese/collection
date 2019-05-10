
### maven-compiler-plugin
###### 功能：指定项目源码的jdk版本，编译后的jdk版本，以及编码


### maven-resources-plugin
###### 功能：处理资源文件;资源文件过滤。可针对不同环境通过命令行货Profile传入的属性值，实现灵活构建
###### 默认的主资源文件目录是 src/main/resources

### maven-surefire-plugin
###### 功能：执行测试

### maven-source-plugin
###### 功能：对maven工程的源代码进行源文件的打包
| 命令           | 功能                                                   |
| ---------------- | -------------------------------------------------------- |
|mvn test -Dtest=[ClassName]#[methodName]           | maven测试单个class文件或方法                             |


### jacoco-maven-plugin
###### 功能：测试单测代码覆盖率


### exec-maven-plugin
###### 功能：运行任何本地的系统程序；可配置相关的程序运行参数,可设置mainClass；
###### `<classpath/>` 这是exec插件最有价值的地方，关于工程的classpath并不需要手动指定，它将由exec自动计算得出
| 命令           | 功能                                                   |
| ---------------- | -------------------------------------------------------- |
|mvn exec:exec          | 运行Java程序（将配置参数写在pom中，简化启动命令）                             |


## Spotify Maven

| 命令           | 功能                                                   |
| ---------------- | -------------------------------------------------------- |
|mvn clean package docker:build          | 编译源码并在本地构建docker镜像                           |


