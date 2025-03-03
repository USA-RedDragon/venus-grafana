FROM grafana/grafana:11.5.2

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
