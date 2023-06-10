FROM tomcat:8-jre11
LABEL "author"="Punith"



RUN rm -rf /usr/local/tomcat/webapps/*

COPY vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
