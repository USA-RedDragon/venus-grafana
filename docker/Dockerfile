FROM grafana/grafana:11.6.10@sha256:d7a51f730ee6c4fc095e5afdf3d11cbfe12a5a9a4f65b6333cd7357b634dd705

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
