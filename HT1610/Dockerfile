FROM alaudademo10-alaudademo10.customerindex.alauda.cn:5000/tomcat

RUN rm -rf $CATALINA_HOME/webapps/ROOT
COPY HT1610-0.0.1-SNAPSHOT.war $CATALINA_HOME/webapps/ROOT/ROOT.war
RUN jar xvf $CATALINA_HOME/webapps/ROOT/ROOT.war && rm -rf $CATALINA_HOME/webapps/ROOT/ROOT.war
