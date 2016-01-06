FROM jboss/wildfly


RUN /opt/jboss/wildfly/bin/add-user.sh admin Admin#007 --silent
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]


ADD basicwildflyapp.war /opt/jboss/wildfly/standalone/deployments/
