# OpenMetrics_XCP_Grafana
This is a dashboard for XCP-NG/XOA with openmetrics plugins (Prometheus exporter)
this dashboard it's my version of infrastructure overview. 
all dashboard include recurency for VM, SR, HOST, POOL if is connect on the XOA source of prometheus telemetry.

It's curently in devellopement for added more Metrics and patch

Documentation : https://docs.xen-orchestra.com/advanced#openmetrics--prometheus-integration
forum link : https://xcp-ng.org/forum/topic/11856/openmetrics-powered-grafana-dashboards-for-xen-orchestra


## Cluster Overview 

![Cluster](/screenshot/cluster_view.png)

## Host Overview 

![Host](/screenshot/host_view.png)

## VM Overview 

![VM](/screenshot/vm_view.png)

## Storage Overview 

![Storage](/screenshot/storage_view.png)

# Feature curently in progress : 

- Collect Uptime from Host & VMs
- Collect storage capacity from VMs
- Adding Network name info for VMs with multiple interface

- more in a futures

If you have on other idea don't hesitate to ping me =)
