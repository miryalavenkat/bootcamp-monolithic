FROM maven:3.6.3-adoptopenjdk-11 

# set working directory
WORKDIR /opt/demo

COPY target/*.jar app.jar

EXPOSE 8000

CMD ["java", "-jar", "app.jar"]