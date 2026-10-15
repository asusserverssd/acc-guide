# Introduction to ASUS Control Center

Welcome! The ASUS Control Center is a server management solution that gives a vital distinction to our servers, and is also compatible with our ASUS commercial products. In server management, system stability is a major factor, with efficiency, cost-effectiveness, and convenience following close behind. To comply with this, we have created a reliable and user-friendly monitoring tool. The ASUS Control Center is a web-based interface that allows system administrators to conveniently manage computers either locally or remotely using a web-browser. With its colorful, graphical, and informative interface, the ASUS Control Center makes server management a delightful experience!

## How ASUS Control Center works

The ASUS Control Center is composed of “agents” that generally act as data collectors, and a set of HTTPS web pages that serve as the user interface (UI). The data collected by the agent, which are essential for the continuous monitoring operations performed by ASUS Control Center, are displayed in the UI.

In the monitoring process, the agent basically keeps track of the hardware and software status of the system. The agent has “sensors” that monitor fan rotation speeds, working voltages, motherboard and CPU temperatures, and the backplane (if present).

In addition, the agent also monitors hard disk drives health status through the S.M.A.R.T. (Self-Monitoring, Analysis, and Reporting Technology) feature, space utilization of a file system, CPU or system memory loading, and even the traffic status of a network device.

The agent records the history of the detected status of all monitored hardware items. The status record includes the time of alert events (fan, voltage, or temperature), and the type of alert event (critical, warning, or normal).

You can also configure ASUS Control Center to react to exceptional situations. For example, the administrator can be automatically notified by e-mail when a hard drive starts to malfunction or when a chassis intrusion is detected. In this way, ASUS Control Center acts as an active guardian of the system’s key components.

## ASUS Control Center Licensing

ASUS Control Center provides two license editions:

- **Classic edition** for assisting management on ASUS servers and workstations.
- **Enterprise edition** for a comprehensive management on ASUS servers and workstations, and all supported ASUS commercial products.

> **NOTE:** For more information on the licensing options, please refer to <https://asuscontrolcenter.asus.com> and <https://www.asus.com/microsite/csm>.

| Category | Group | Feature | Classic | Enterprise |
| --- | --- | --- | --- | --- |
| **Banner** |  | Mission Center | √ | √ |
| **Monitor (Overview)** |  | System Overview | Partial functions unavailable | √ |
| **Monitor (Overview)** |  | VM Overview | - | √ |
| **Monitor (one node)** |  | Host Information | - | √ |
| **Monitor (one node)** |  | Device Information | √ | √ |
| **Monitor (one node)** |  | Hardware Sensor | Partial functions unavailable | √ |
| **Monitor (one node)** |  | Utilization | Partial functions unavailable | √ |
| **Monitor (one node)** |  | GPU | - | √ |
| **Monitor (one node)** |  | Inventory | Partial functions unavailable | √ |
| **Monitor (one node)** |  | Event Log | Partial functions unavailable | √ |
| **Monitor (one node)** |  | Software | Partial functions unavailable | √ |
| **Monitor (one node)** |  | BMC (BMC Required) | √ | √ |
| **Monitor (one node)** |  | BIOS | √ | √ |
| **Monitor (one node)** |  | Security | Partial functions unavailable | √ |
| **Monitor (one node)** |  | Configuration | Partial functions unavailable | √ |
| **Deployment** | Agent Management | Deploy Agents | √ | √ |
| **Deployment** | Agent Management | Remove Agents | √ | √ |
| **Deployment** | Agent Management | Scan and Deploy | √ | √ |
| **Deployment** | Agentless Management | Add vSphere | - | √ |
| **Deployment** | Agentless Management | Remove vSphere | - | √ |
| **Deployment** | Agentless Management | Add Redfish | - | √ |
| **Deployment** | Agentless Management | Remove Redfish | - | √ |
| **Centralized** |  | Metadata Management | √ | √ |
| **Centralized** | BIOS Flash Management | BIOS Cache | √ | √ |
| **Centralized** | BIOS Flash Management | BIOS Flash Task | - | √ |
| **Centralized** | BIOS Flash Management | BIOS Flash Task Report | - | √ |
| **Centralized** | Security Management | Device Access Control | - | √ |
| **Centralized** | Security Management | Software Blocklist | - | √ |
| **Centralized** | Software Dispatch | Software Pool | √ | √ |
| **Centralized** | Software Dispatch | Software Dispatch Task | - | √ |
| **Centralized** | Software Dispatch | Software Dispatch Task Report | - | √ |
| **Centralized** |  | Task Scheduler | - | √ |
| **Centralized** |  | Power Control | - | √ |
| **Report** | Software Report | Software Inventory | - | √ |
| **Report** | Software Report | Hotfix Report | - | √ |
| **Report** | Software Report | License Report | - | √ |
| **Report** | Software Report | Application Usage Analysis | - | √ |
| **Report** | Software Report | Service Report | - | √ |
| **Report** |  | Hardware Inventory | - | √ |
| **Report** | Task Report | Software Dispatch | - | √ |
| **Report** | Task Report | BIOS Dispatch | - | √ |
| **Report** | Task Report | Agent Update | √ | √ |
| **Report** | Task Report | Agent Deploy | √ | √ |
| **Notification** |  | Hardware & Utilization | √ | √ |
| **Notification** | Asset Changes | Trust Software Asset | - | √ |
| **Notification** | Asset Changes | Focus Software Asset | - | √ |
| **Notification** | Asset Changes | Hardware Asset | - | √ |
| **Notification** |  | Subscription Report | - | √ |
| **Account** |  | Role Privilege Management | - | √ |
| **Account** |  | Accounts Management | - | √ |
| **Options** |  | General Configuration | √ | √ |
| **Options** |  | Network Configuration | √ | √ |
| **Options** |  | Appearance Configuration | - | √ |
| **Options** |  | Security Configuration | Partial functions unavailable | √ |
| **Options** |  | SMTP Settings | √ | √ |
| **Options** |  | Backup & Restore | - | √ |
| **Options** |  | Maintenance | √ | √ |
| **Options** |  | DBExpose Configuration | - | √ |
| **Options** |  | Update | √ | √ |
| **Options** |  | Access Control List | - | √ |
| **Options** |  | Sensor Threshold | √ | √ |
| **Options** |  | Software List | - | √ |
| **License** |  | License | Partial functions unavailable | √ |

\* **Please contact your local ASUS Sales representative and/or TPM for more information on the availability of other functions this feature supports.**
