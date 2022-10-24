FROM maven:3.8.6-openjdk-11
EXPOSE 8761
ADD target/Eureka-0.0.1-SNAPSHOT.jar eureka.jar
ENTRYPOINT ["java","-jar","/eureka.jar"]