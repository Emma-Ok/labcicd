FROM openjdk:24-ea-17-jdk-oraclelinux8
EXPOSE 8080
ADD target/labcicd-0.0.1-SNAPSHOT.jar labcicd-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/labcicd-0.0.1-SNAPSHOT.jar"]