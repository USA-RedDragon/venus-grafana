FROM grafana/grafana:12.4.3@sha256:2e986801428cd689c2358605289c90ab37d2b39e24808874971f54c99bcdc412

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
