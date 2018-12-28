FROM frolvlad/alpine-oraclejdk8
#指定维护者信息
VOLUME /tmp
ADD docker-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
#指定执行启动spring boot小项目     ENTRYPOINT 为容器启动后执行的命令
ENTRYPOINT ["java","-jar","/app.jar"]
