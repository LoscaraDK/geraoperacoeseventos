FROM quay.intraservice.corp/b3/ubi8:openjdk-11-runtime
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} geraoperacoeseventovcp.jar
CMD ["java","-jar","geraoperacoeseventovcp.jar"]