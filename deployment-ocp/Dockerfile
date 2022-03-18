FROM image-registry.openshift-image-registry.svc:5000/openshift/java:openjdk-11-ubi8

ADD target/*.jar app.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","app.jar"]