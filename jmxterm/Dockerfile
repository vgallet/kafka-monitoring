FROM openjdk:8

RUN curl -sSL -o /bin/jmxterm.jar https://github.com/jiaqi/jmxterm/releases/download/v1.0.2/jmxterm-1.0.2-uber.jar

ENTRYPOINT ["java", "-jar", "/bin/jmxterm.jar"]