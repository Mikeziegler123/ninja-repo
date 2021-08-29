# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine

# Copy war file
COPY ninja-1.0.2.RELEASE.jar /Ninja_Client.war

# run the app
CMD ["/usr/bin/java", "-jar", "/Ninja_Client.war"]