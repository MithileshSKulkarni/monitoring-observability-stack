# Use the official Prometheus image as the base image
FROM prom/prometheus:latest
# Set the working directory
CMD ["--config.file", "/etc/prometheus/prometheus.yml", "--web.config.file", "/etc/prometheus/web-config.yml"]
# Expose Prometheus port
EXPOSE 9090:9090