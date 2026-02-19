# CLOUD-LINK NETWORKS  
## Routing and Redundancy Documentation

---

## 1.0 Overview
This document describes the **routing protocols** and **redundancy strategies** implemented in the CLOUD-LINK NETWORKS ISP enterprise network to ensure **high availability, failover, and optimal performance**.

---

## 2.0 Routing Protocols

### 2.1 Internal Routing – OSPF
- **Open Shortest Path First (OSPF)** is used for routing within the ISP network.  
- OSPF provides:
  - Fast convergence  
  - Loop-free routing  
  - Support for multiple areas if network scales  
- Each department VLAN subnet is advertised to OSPF for internal
