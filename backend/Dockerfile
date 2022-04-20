FROM tomcat:9
LABEL maintainer='olga.a.grigorieva@gmail.com'
ADD backend.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]