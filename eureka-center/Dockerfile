FROM java:8
VOLUME /tmp
ADD target/eureka-center-0.0.1-SNAPSHOT.war eureka.jar
RUN bash -c 'touch /eureka.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/eureka.jar"]
