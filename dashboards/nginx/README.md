### Dashboards for Nginx

#### Notes

This dashboard is based on Google's [Ops Agent](https://cloud.google.com/stackdriver/docs/solutions/agents/ops-agent).
Check the [full list of metrics](https://cloud.google.com/stackdriver/docs/solutions/agents/ops-agent/third-party/nginx#monitored-metrics) supported by the Ops Agent.

|Nginx Overview|
|:------------------|
|Filename: [overview.json](overview.json)|
|This dashboard has charts displaying `Request Rate`, `Current Connections`, and `Connections Rate` from NGINX as well as charts of infrastructure related metrics for the running NGINX VMs: `CPU % Top 5 VMs`, `Memory % Top 5 VMs`, and `NGINX VMs by Region` for a count of VMs over time. There is also a card with links to docs and NGINX log in Cloud Logging.|
