# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM eclipse-temurin:17-jre

# Simply the artifact path
ARG artifact=target/jai-0.0.1-SNAPSHOT.jar.original



WORKDIR /opt/app

COPY ${artifact} app.jar

EXPOSE 8000

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
