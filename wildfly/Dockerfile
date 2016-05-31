FROM jboss/wildfly:latest
RUN /opt/jboss/wildfly/bin/add-user.sh admin admin --silent
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "--debug", "8787", "-b", "0.0.0.0", "-bmanagement","0.0.0.0"]
