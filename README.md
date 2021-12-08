# NIC_PROJECT_DGMP

Containers:
Prometheus (metrics database) http://<host-ip>:9090
Prometheus-Pushgateway (push acceptor for ephemeral and batch jobs) http://<host-ip>:9091
AlertManager (alerts management) http://<host-ip>:9093
Grafana (visualize metrics) http://<host-ip>:3000
NodeExporter (host metrics collector)
cAdvisor (containers metrics collector)
Caddy (reverse proxy and basic auth provider for prometheus and alertmanager)
Url: http://prometheus:9090 #PROMETHEUS
url: http://<host-ip>:3000  #gRAFANA
Prometheus http://<host-ip>:9090 launching this request
