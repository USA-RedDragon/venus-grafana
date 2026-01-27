FROM grafana/grafana:12.3.2@sha256:ba93c9d192e58b23e064c7f501d453426ccf4a85065bf25b705ab1e98602bfb1

COPY grafana/provisioning /etc/grafana/provisioning
COPY docker/entrypoint.sh /

USER grafana
EXPOSE 3000

ENTRYPOINT ["/entrypoint.sh"]
