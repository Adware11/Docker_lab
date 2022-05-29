FROM tomcat:8-jre11
LABEL "Author"="AVL"
LABEL "Project"="VProfile"
EXPOSE 8080
ADD vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war
CMD rm -rf /usr/local/tomcat/webapps/ROOT && /usr/local/tomcat8/bin/catalina.sh
