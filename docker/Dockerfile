FROM grafana/grafana:11.6.16@sha256:d67af92050b8d93b393dc741864752a69c9da1ffa39c1bb9af49ad5d9e47d2c3

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
