FROM grafana/grafana:11.5.1

COPY --chown=grafana grafana/provisioning /etc/grafana/provisioning
COPY --chown=grafana grafana/plugins /var/lib/grafana/plugins
COPY docker/entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
