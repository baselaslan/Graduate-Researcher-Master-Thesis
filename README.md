# Graduate-Researcher-Master-Thesis

**Emulation of a Spot Market for Interdomain Connectivity Using [GitHub Docs](https://docs.github.com).**



Emulated a distributed network of Autonomous Systems and cloud-based environments representing a spot market involving ISPs, transit providers, and IXPs, using Kathará, a container-based network emulation platform built on Docker and extensible to Kubernetes for larger-scale deployments. Implemented OSPF for intra-domain routing and BGP for interdomain routing.

Investigated the technical feasibility of routing money in the Internet ecosystem through a spot market, where transit providers sell excess capacity on a best-effort basis. Applied Economic Software-Defined Exchanges (ESDXs) as trusted intermediaries to tie the forwarding service to economic incentives. Analyzed technical and economic requirements, evaluated distributed network performance, and identified risks such as cascading failures and market imbalance.

**Advertisement Propagation Topology**

This topology represents a network designed with nine autonomous systems (AS), from AS10 to AS90. AS10 and AS70 indicate access networks A and B. AS20, AS40, AS60 and AS90 are internet exchange points (IXPs) marked with the letters W, X, Y and Z, respectively. AS30, AS50 and AS80 are transit networks tagged with the letters ‘α’, ‘β’, and ‘γ’.

![Advertisement Propagation Topology](https://github.com/user-attachments/assets/fec06f55-818e-4607-b122-422fc3059424)


**Scenario 5 - Emulation using BGP MED Attribute with ISP Failure on AS80**

This figure shows the broken of primary and backup links between AS80 and AS90. In addition to the best paths between A and B according to the choice of BGP. The red path indicates the best path from A to B. In contrast, both green and blue are available paths from B to A, where red indicates the best path.

![scenario 5](https://github.com/user-attachments/assets/7a83e52e-8ee8-4bff-ad2c-5d9e603e1150)
