### Dashboards for Memcached

#### Notes

This dashboard is based on Google's [Ops Agent](https://cloud.google.com/stackdriver/docs/solutions/agents/ops-agent).
Check the [full list of metrics](https://cloud.google.com/stackdriver/docs/solutions/agents/ops-agent/third-party/memcached#monitored-metrics) supported by the Ops Agent.


|Memcached GCE Overview|
|:------------------|
|Filename: [memcached-gce-overview.json](memcached-gce-overview.json)|
|This dashboard has charts displaying `Command Rate`, `Operation Rate`, `Connections Current`, `Connections Total`, `Evictions`, `Current Items`, `CPU Usage`, `Network`, `Threads` and `Bytes` from Memcached as well as charts of infrastructure related metrics for the running Memcached VMs: `CPU % Top 5 VMs`, `Memory % Top 5 VMs`, and `Hosts by Region`.
