#docker_images-0.0.1-SNAPSHOT.jar

# 以jdk8为基础镜像
FROM openjdk:8
# 描述
LABEL description="Java 8"

# 暴露接口
EXPOSE 8080
# 将主机中的jar包添加到镜像中
ADD /jar/app.jar app.jar
# 运行jar包
ENTRYPOINT ["java", "-jar","app.jar"]