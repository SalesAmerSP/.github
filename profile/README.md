# F5 Service Provider Sales — Americas

Community tools and automation built by the F5 Service Provider Sales team for the Americas region. This organization hosts open-source utilities focused on F5 BIG-IP, BIG-IQ, and related infrastructure — primarily written in Python, Shell, Ansible/Jinja, and HTML.

## Repositories

### BIG-IP Tools

| Repository | Description | Language |
| --- | --- | --- |
| [f5_bigip_cgnat_pba_stats](https://github.com/SalesAmerSP/f5_bigip_cgnat_pba_stats) | CLI tools for querying and collecting CGNAT Port Block Allocation (PBA) statistics on F5 BIG-IP — per-subscriber port block lookups, pool summaries, JSON export, and CSV/MySQL data collection. | Python |
| [f5_ssl_cipher_report](https://github.com/SalesAmerSP/f5_ssl_cipher_report) | Generates a list of VIPs, associated profiles, and cipher string/list for SSL profiles in use. | Python |
| [f5_data_group_manager](https://github.com/SalesAmerSP/f5_data_group_manager) | Python-based web application to manage BIG-IP data groups using iControl REST. | Python |
| [bigip_as3_change_report](https://github.com/SalesAmerSP/bigip_as3_change_report) | Reports manual changes to AS3 applications on BIG-IPs. | Python |
| [f5_tmos_high_availability_health_check](https://github.com/SalesAmerSP/f5_tmos_high_availability_health_check) | Ansible-based monitoring tool to ensure high availability (HA) of F5 BIG-IP systems running TMOS. | Shell |
| [Ansible_rSeries](https://github.com/SalesAmerSP/Ansible_rSeries) | Ansible playbooks tested on F5 rSeries r10900 appliances. | Jinja |

### BIG-IQ Tools

| Repository | Description | Language |
| --- | --- | --- |
| [bigiq-inventory-export](https://github.com/SalesAmerSP/bigiq-inventory-export) | Python CLI tool to export BIG-IQ inventory data (virtual servers, pools, pool members) via the F5 BIG-IQ REST API, with optional CSV output. | Python |
| [bigiq_auto_reconciliation](https://github.com/SalesAmerSP/bigiq_auto_reconciliation) | Automatically rediscovers and reimports all devices into F5's BIG-IQ Central Manager. | Python |
| [f5_big-iq_as3_rbac_export](https://github.com/SalesAmerSP/f5_big-iq_as3_rbac_export) | Exports all AS3 Applications and Services from BIG-IQ, along with full RBAC configuration. | Python |

### Support & Diagnostics

| Repository | Description | Language |
| --- | --- | --- |
| [f5_support_case_creation_api_tools](https://github.com/SalesAmerSP/f5_support_case_creation_api_tools) | Tools to interact with BIG-IPs for qkviews, MyF5 for support case creation/update, and iHealth for qkview uploads. | Python |
| [iHealth_py](https://github.com/SalesAmerSP/iHealth_py) | Python utilities for F5 iHealth. | Python |
| [robotframework-f5tmos](https://github.com/SalesAmerSP/robotframework-f5tmos) | Robot Framework library for F5 TMOS. | HTML |

### Kubernetes & Infrastructure

| Repository | Description | Language |
| --- | --- | --- |
| [kind-multus](https://github.com/SalesAmerSP/kind-multus) | Kind cluster with Multus and Calico. | Shell |
| [k8s-vpa](https://github.com/SalesAmerSP/k8s-vpa) | Covers aspects of Kubernetes Vertical Pod Autoscaler (VPA). | — |
| [mtls](https://github.com/SalesAmerSP/mtls) | Mutual TLS (mTLS) examples. | Shell |

### Observability

| Repository | Description | Language |
| --- | --- | --- |
| [alloyloki](https://github.com/SalesAmerSP/alloyloki) | Application Services Telemetry (AST) with Grafana Alloy and Loki. | — |

## Topics

`f5 · f5networks · big-iq · ssl · ciphers · network-automation-python`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request in the relevant repository.

## License

Licensing varies by repository. Check individual repos for details — common licenses include **Apache 2.0** and **MIT**.