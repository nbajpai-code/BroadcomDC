# Broadcom VMware Data Center Resources

Following the acquisition, VMware is now "VMware by Broadcom," serving as the software-defined foundation for the modern data center.

## VMware Cloud Foundation (VCF)
*   The integrated software stack bundling Compute, Storage, Networking, and Management.
*   **Components:**
    *   **vSphere:** Server virtualization (ESXi + vCenter).
    *   **vSAN:** Software-Defined Storage (Hyper-Converged Infrastructure).
    *   **NSX:** Software-Defined Networking and Security.
    *   **Aria Suite (formerly vRealize):** Cloud management, automation, and operations.
*   **Documentation:** [VMware Cloud Foundation Documentation](https://docs.vmware.com/en/VMware-Cloud-Foundation/index.html)

## 1. Compute Virtualization (vSphere)
*   **Purpose:** The industry-standard hypervisor platform.
*   **Key Features:** vMotion, HA (High Availability), DRS (Distributed Resource Scheduler).
*   **Documentation:** [vSphere 8 Documentation](https://docs.vmware.com/en/VMware-vSphere/index.html)

## 2. Storage Virtualization (vSAN)
*   **Purpose:** Aggregates local storage devices into a shared datastore.
*   **Key Features:** Erasure Coding, Deduplication & Compression, HCI Mesh.
*   **Integration:** Often deployed with Broadcom HBA/RAID controllers (HBA 9500/9600) on the Hardware Compatibility List (HCL).
*   **Documentation:** [vSAN 8 Documentation](https://docs.vmware.com/en/VMware-vSAN/index.html)

## 3. Network Virtualization (NSX)
*   **Purpose:** Virtual networking and security entirely in software.
*   **Key Features:** Micro-segmentation, Distributed Firewall, Logical Switching/Routing.
*   **Documentation:** [NSX 4.x Documentation](https://docs.vmware.com/en/VMware-NSX/index.html)
