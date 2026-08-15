FROM grafana/grafana:12.4.8@sha256:7753ad493720e33560077e8bc5e05fbce4ade777f1387b19ab5050b6777111dd

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
