FROM openjdk:16-alpine

RUN apk --no-cache add curl
RUN curl -L https://github.com/checkstyle/checkstyle/releases/download/checkstyle-8.43/checkstyle-8.43-all.jar > /checkstyle.jar

ENTRYPOINT [ "java","-jar","checkstyle.jar","-c","/sun_checks.xml"]


