# Loki Configuration

This project uses the default `local-config.yaml` provided by the Loki release.

No custom modifications were required for this project.

Loki was configured to:

- Listen on port **3100**
- Receive logs from **Grafana Alloy**
- Store log data locally
- Serve log queries to **Grafana Explore**

If custom storage backends (Amazon S3, GCS, MinIO, etc.) are required, the `local-config.yaml` can be modified accordingly.
