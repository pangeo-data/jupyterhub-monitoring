# JupyterHub Monitoring Analysis

This repository holds various data and products for the monitoring
deployments on the AWS and GCP hubs from the
[Pangeo Cloud Federation repository](https://github.com/pangeo-data/pangeo-cloud-federation).

These monitoring deployments can be visited at the Grafana sites
for the respective hubs:
- [AWS Hub Grafana Site](http://grafana.staging.aws-uswest2.pangeo.io/grafana/?orgId=1)
- [GCP Hub Grafana Site](http://grafana.us-central1-b.gcp.pangeo.io/grafana/?orgId=1)

The `data/` folder contains data exported from these Grafana
endpoints.

The notebook file generates plots stored in the `plots/` folder.
These lots cover CPU and memory usage on each hub as well as
user session durations. The notebook can be used as a starting
point for further analysis, as it covers data import, cleaning,
transformation, and plotting.

There is also a provided `conda` environment that can be used to run
the notebook as-is.
