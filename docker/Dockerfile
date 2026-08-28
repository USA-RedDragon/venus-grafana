FROM grafana/grafana:12.4.9@sha256:9b58461280b4d2992d4399823c9427d0fcf5f0fd7f376c93f2dea876158b867b

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
