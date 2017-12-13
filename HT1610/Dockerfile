FROM 172.26.0.8:5000/tomcat:latest

RUN rm -rf $CATALINA_HOME/webapps/*
COPY HT1610-0.0.1-SNAPSHOT.war $CATALINA_HOME/webapps/ROOT/ROOT.war
RUN echo "Hello World" > $CATALINA_HOME/webapps/ROOT/index.html
