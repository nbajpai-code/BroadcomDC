# Broadcom Network Observability Resources

Broadcom provides end-to-end visibility from the switching silicon up to the user experience layer.

## 1. Digital Experience Monitoring (AppNeta)

**AppNeta by Broadcom** delivers visibility into the end-user experience of any application, from any location, over any network.

### Key Capabilities
*   **Active Monitoring:** Synthetically tests network performance (latency, loss, jitter) continuously.
*   **TruView:** Combined view of active and passive monitoring.
*   **Cloud & SaaS Visibility:** Insights into connectivity to Office 365, Zoom, Salesforce, etc., bypassing traditional blind spots.
*   **Work from Anywhere:** Monitoring points can be deployed on workstations (software) or offices (hardware).

### Resources
*   [AppNeta Product Page](https://www.broadcom.com/products/software/appneta)
*   [AppNeta Documentation](https://techdocs.broadcom.com/us/en/symantec-security-software/appneta-visibility/appneta.html)

---

## 2. Network Operations (DX NetOps)

**DX NetOps** constitutes a comprehensive platform for traditional and software-defined network monitoring.

### Components
*   **Performance Management:** High-scale SNMP and API-based monitoring.
*   **Fault Management (Spectrum):** Root cause analysis and alarm correlation.
*   **Network Flow Analysis:** Deep dive into traffic patterns using NetFlow/IPFIX/sFlow.
*   **Virtual Network Assurance:** Visibility into SD-WAN (VeloCloud, Cisco, Versa) and SDN architectures.

### Key Features
*   **Silicon-to-Service:** Correlation of hardware metrics with application performance.
*   **AIOps Integration:** Feeds data into Broadcom's AIOps platform for predictive insights.

### Resources
*   [DX NetOps Product Page](https://www.broadcom.com/products/software/netops)
*   [DX NetOps Documentation](https://techdocs.broadcom.com/us/en/ca-enterprise-software/it-operations-management/dx-netops/21-2.html)

---

## 3. Silicon Telemetry (BroadView™)

**BroadView** is an instrumentation software suite that exposes advanced analytics directly from Broadcom switching silicon (Tomahawk, Trident, Jericho).

### Key Features
*   **BST (Buffer Statistics Tracking):** Real-time visibility into microbursts and congestion at the queue level.
*   **Packet Tracing:** Hop-by-hop visibility of packet paths through the fabric.
*   **Flow Tracker:** Hardware-accelerated flow monitoring without performance penalties.

### Integration
*   BroadView agents run on the switch OS (e.g., SONiC, Broadcom ICOS).
*   Data is exported to collectors (like DX NetOps or third-party tools) via IPFIX or Google Protocol Buffers (GPB).

### Resources
*   [BroadView Instrumentation](https://www.broadcom.com/products/ethernet-connectivity/software/broadview)
