FROM jboss/wildfly
COPY maven /tmp/c36062a8-a651-4e52-95aa-60cdc3300021/opt/jboss/wildfly/standalone/deployments/
USER root
RUN chown -R jboss:jboss /tmp/c36062a8-a651-4e52-95aa-60cdc3300021 && cp -rp /tmp/c36062a8-a651-4e52-95aa-60cdc3300021/* / && rm -rf /tmp/c36062a8-a651-4e52-95aa-60cdc3300021
USER jboss
RUN chmod -R 777 /opt/jboss/wildfly
USER root
