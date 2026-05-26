# MPLS-TE QoS Network Simulation using OPNET Modeler

This project presents the design and simulation of an advanced MPLS Traffic Engineering (MPLS-TE) network using OPNET Modeler (Riverbed Modeler). The implemented architecture focuses on providing efficient traffic forwarding, Quality of Service (QoS), intelligent traffic distribution, and fast failover recovery for real-time multimedia applications such as VoIP.

The network topology consists of multiple Label Switch Routers (LSRs) forming a resilient MPLS core between two edge Label Edge Routers (LERs) representing Site A and Site B. OSPF is used as the Interior Gateway Protocol (IGP) to establish network reachability and routing information exchange, while MPLS-TE with RSVP signaling is employed to create explicit Label Switched Paths (LSPs) for controlled traffic forwarding.

The project implements:

* MPLS Label Switching Architecture
* MPLS Traffic Engineering (TE)
* RSVP-based LSP establishment
* Explicit Route Configuration
* QoS-aware forwarding using WFQ scheduling
* VoIP traffic prioritization
* Dynamic traffic mapping using FECs
* Primary and secondary traffic paths
* Fast failover and traffic rerouting mechanisms
* Hybrid Voice/Data traffic management
* Performance monitoring and statistical analysis

The traffic engineering model prioritizes VoIP packets over standard data traffic to ensure low latency, low jitter, and improved Quality of Experience (QoE). Voice traffic is forwarded through a primary MPLS tunnel with the highest priority, while data traffic is distributed across available paths to optimize bandwidth utilization and reduce congestion.

The system is designed to maintain service continuity during link or path failures through MPLS-TE recovery mechanisms and backup path utilization. QoS mechanisms such as Weighted Fair Queuing (WFQ) are integrated to guarantee differentiated traffic handling and resource reservation.

Simulation results include:

* End-to-End Delay
* Packet Delay Variation (Jitter)
* MOS Evaluation
* Flows
Packet sent , received  
Throughput 
RSVP flows
Delay (ms)
* Tunnel Utilization
* RSVP Session Statistics
* OSPF Convergence Analysis
* Traffic Distribution Efficiency
* Failover Recovery Performance

This project demonstrates the practical integration of MPLS, Traffic Engineering, QoS, and dynamic routing protocols within a carrier-grade network simulation environment.
