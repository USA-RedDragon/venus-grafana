FROM grafana/grafana:11.6.14@sha256:ebe075cd4c4520f9d3af2403a1ddc830651ca7d009cbdfdcf21032db574dc3a7

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
