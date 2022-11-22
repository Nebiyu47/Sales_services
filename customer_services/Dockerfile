FROM openjdk:8
EXPOSE 8080
ADD target/customer_services.jar customer_services.jar
ENTRYPOINT ["java" , "-jar" , "/customer_services.jar"]