# Ashley "Patience" Hopkins | Cloud & Network Engineering Portfolio

I am a WGU Cloud and Network Engineering student on the AWS track, building toward security aware network and cloud engineering roles.

I learn best by building systems, breaking them in controlled ways, and tracing the evidence until I understand what actually happened.

## Featured Projects

### [Network Flight Recorder](https://github.com/PatienceEnoch/network-flight-recorder)

A local first Linux network troubleshooting and observability system that captures known good state, detects meaningful changes, correlates evidence into likely root causes, tracks incidents through recovery, and preserves evidence even when cloud connectivity is unavailable.

Current architecture includes:

- Python CLI and automated tests
- Docker based failure injection
- Terraform managed AWS infrastructure
- Private S3 evidence storage
- CloudWatch metrics, logs, and dashboarding
- Deterministic evidence redaction
- Approval gated remediation
- Post change verification and rollback
- GitHub Actions validation

### [Mini Internet](https://github.com/PatienceEnoch/mini-internet)

A three router FRRouting lab using three private autonomous systems.

I built it to observe BGP path selection and failover directly. The lab includes a controlled A to C link failure, an alternate route through B, and a timer comparison between default BGP behavior and shorter 3/9 second timers.

### [Shipment Tracker](https://github.com/PatienceEnoch/shipment-tracker)

A Python/FastAPI workflow application that tracks whether a sales order receives a shipping label and whether the carrier actually acquires the package within the expected time window.

It includes persistent state, overdue alerts, deduplication, API endpoints, a browser dashboard, and automated tests.

### [Site to Site IPsec VPN Lab](https://github.com/PatienceEnoch/Ubuntu-virtual-network-lab/blob/main/docs/local-site-to-site-ipsec-validation.md)

A routed Linux VPN lab connecting an Ubuntu client network to a simulated cloud network through strongSwan IKEv2/IPsec.

I validated the complete path across routing, NAT exemption, XFRM policy/state, encryption, forwarding, ARP, tcpdump, return routing, network namespaces, and reboot persistence. The finished build passes end to end traffic from `10.10.10.10` to `10.20.0.10` with 0% packet loss after rebooting both gateway sides.

### [Tor Middle Relay](https://github.com/PatienceEnoch/TOR_Relay)

A documented non exit Tor middle relay focused on Linux service administration, TCP/IP, ports, logging, and traffic validation.

## Architecture Journal

My [Cloud Network Architecture Journal](https://github.com/PatienceEnoch/Cloud-Network-Architecture-Journal) contains the engineering lessons behind the projects, including:

- BGP path selection and convergence
- Failure domains
- Local first observability
- Guarded remediation and rollback
- Distributed systems
- Cloud architecture
- Network failure analysis

> A backup path is architecture. Recovery time is behavior.

## Technical Skills

- **Networking:** TCP/IP, IPv4, subnetting, DNS, DHCP, NAT, VLANs, routing, BGP, firewalls, IKEv2/IPsec, strongSwan, XFRM, packet analysis
- **Linux:** Ubuntu, systemd, Bash, SSH, services, permissions, logs, network namespaces, veth pairs, troubleshooting
- **Cloud & Infrastructure:** AWS, VPC networking, S3, CloudWatch, IAM, Terraform
- **Development & Automation:** Python, FastAPI, SQLAlchemy, pytest, Ruff, GitHub Actions, JSON, CLI tooling
- **Containers:** Docker, Docker Compose
- **Security:** access control, evidence protection, dependency auditing, secure by default design

## Education & Certifications

**Western Governors University**  
B.S. Cloud and Network Engineering, AWS Track, in progress

- CompTIA Network+
- CompTIA A+
- LPI Linux Essentials
- ITIL 4 Foundation
- CompTIA IT Fundamentals

## Current Direction

I am currently focused on CCNA concepts, AWS networking, BGP and routing behavior, Python automation, network observability, and hybrid cloud connectivity.

The next major architecture build is a simulated on premises environment connected to AWS, followed by Transit Gateway, segmented VPCs, Terraform automation, and observability.

## Contact

- [GitHub](https://github.com/PatienceEnoch)
- [LinkedIn](https://www.linkedin.com/in/ashley-hopkins-432244329/)
- [Cloud Network Architecture Journal](https://github.com/PatienceEnoch/Cloud-Network-Architecture-Journal)
