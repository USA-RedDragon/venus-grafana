FROM grafana/grafana:10.4.19@sha256:a9043254ba16fb10945cc27333963dfd08eccbb43b51f1222d831cc564e3a1f4

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
