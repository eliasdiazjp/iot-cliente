FROM grafana/grafana:8.5.3

VOLUME ./grafana:/var/lib/grafana

# Add plugins
ENV GF_INSTALL_PLUGINS=grafana-simple-json-datasource

ENV GF_AUTH_DISABLE_LOGIN_FORM=true
ENV GF_AUTH_ANONYMOUS_ENABLED=true
ENV GF_AUTH_ANONYMOUS_ORG_ROLE=Admin
ENV GF_SECURITY_ALLOW_EMBEDDING=true



