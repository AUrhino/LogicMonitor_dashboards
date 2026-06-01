# LogicMonitor Dashboards

This repository contains a collection of custom LogicMonitor dashboard configurations and templates designed to improve observability and monitoring efficiency.

## Infrastructure Overview
This dashboard provides a high-level view of core infrastructure health, including CPU utilization, memory pressure, and network throughput across the primary data center.

| Name | Code Link | Sample Image |
| :--- | :--- | :--- |
| Core Infrastructure Summary | [View Code](code/core-infra.json) | ![Sample](image/core-infra.png) |
| Cloud Provider Health | [View Code](code/cloud-health.json) | ![Sample](image/cloud-health.png) |

## Application Performance
Focused on application-tier metrics, this section tracks request latency, error rates, and throughput for production services.

| Name | Code Link | Sample Image |
| :--- | :--- | :--- |
| API Service Performance | [View Code](code/api-service.json) | ![Sample](image/api-service.png) |
| Database Transaction Metrics | [View Code](code/db-metrics.json) | ![Sample](image/db-metrics.png) |

## Network & Connectivity
Visualizing traffic patterns, VPN tunnel status, and switch health for internal network monitoring.

| Name | Code Link | Sample Image |
| :--- | :--- | :--- |
| Internal Network Traffic | [View Code](code/network-traffic.json) | ![Sample](image/network-traffic.png) |
| VPN Tunnel Monitor | [View Code](code/vpn-status.json) | ![Sample](image/vpn-status.png) |

---
*Note: Ensure your LogicMonitor API credentials have the necessary permissions to import these dashboard JSON files.*
"""
