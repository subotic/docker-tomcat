FROM tomcat:8-jre8

MAINTAINER Ivan Subotic "ivan.subotic@unibas.ch"

# Update base installation
RUN apt-get update && \
    apt-get install -y --no-install-recommends && \
    apt-get install -y openjdk-8-jdk

EXPOSE 8080
CMD ["catalina.sh", "run"]
