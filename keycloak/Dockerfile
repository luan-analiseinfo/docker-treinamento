FROM jboss/keycloak
LABEL authors="Luan Lucas"
ENV KEYCLOAK_USER='admin' KEYCLOAK_PASSWORD='admin'
CMD ["/opt/jboss/keycloak/bin/add-user-keycloak.sh"] ["-b","0.0.0.0"] ["-u","${KEYCLOAK_USER}"] ["-u","${KEYCLOAK_PASSWORD}"]
EXPOSE 8080