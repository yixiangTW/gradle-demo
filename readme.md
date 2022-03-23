通过Gradle构建Java应用

初始化 `gradle init`

构建 `./gradlew build`

运行 `java -cp app.jar com.thoughtworks.tools.App`


Gradle Wrapper
自动下载对应版本的gradle，配置文件在gradle/wrapper/gradle-wrapper.properties,告诉你从哪里下载，下载到哪里


查看这个项目 gradle的版本：
1. `./gradlew -v`
2. 直接看gradle-wrapper.properties 文件

修改当前项目 gradle版本：
1. gradle wrapper --gradle-version 6.8.3
2. 手动修改gradle-wrapper.properties 文件


清理构建产物 `./gradlew clean`  放在 app/build 目录
执行构建 `./gradlew build` 把app/build目录清理掉  
运行测试 `./gradlew test`   
查看所有task `./gradlew tasks`   
